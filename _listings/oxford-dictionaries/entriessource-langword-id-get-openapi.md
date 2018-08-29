---
swagger: "2.0"
x-collection-name: Oxford Dictionaries
x-complete: 0
info:
  title: Oxford Dictionaries Retrieve dictionary information for a given word
  description: Use this to retrieve definitions, [pronunciations](documentation/glossary?term=pronunciation),
    example sentences, [grammatical information](documentation/glossary?term=grammaticalfeatures)
    and [word origins](documentation/glossary?term=etymology). It only works for dictionary
    [headwords](documentation/glossary?term=headword), so you may need to use the
    [Lemmatron](documentation/glossary?term=lemma) first if your input is likely to
    be an [inflected](documentation/glossary?term=inflection) form (e.g., 'swimming').
    This would return the linked [headword](documentation/glossary?term=headword)
    (e.g., 'swim') which you can then use in the Entries endpoint. Unless specified
    using a region filter, the default lookup will be the Oxford Dictionary of English
    (GB).
  termsOfService: http://helloreverb.com/terms/
  version: 1.8.0
host: od-api-demo.oxforddictionaries.com:443
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /stats/frequency/words/{source_lang}/:
    get:
      summary: Retrieve a list of frequencies of a word/words derived from a corpus.
      description: |-
        This endpoint provides a list of frequencies for a given word or words. Unlike the /word/ endpoint, the results are split into the smallest units.   To exclude a specific value, prepend it with the minus sign ('-'). For example, to get frequencies of the lemma 'happy' but exclude superlative forms (i.e., happiest) you could use options 'lemma=happy;grammaticalFeatures=-degreeType:superlative'.   Parameters can be provided in PATH, GET or POST (form or json). The parameters in PATH are overriden by parameters in GET, POST and json (in that order). In PATH, individual options are separated by semicolon and values are separated by commas (where multiple values can be used).   The parameters wordform/trueCase/lemma/lexicalCategory also exist in a plural form, taking a lists of items. Examples:
        * PATH: /wordforms=happy,happier,happiest
        * GET: /?wordforms=happy&wordforms=happier&wordforms=happiest
        * POST (json):
        ```javascript
          {
            "wordforms": ["happy", "happier", "happiest"]
          }
        ```
         Aside from individual frequency requests, users can also post a list of items for which they would like to get frequencies. The list has to be uploaded in json and the required fields are "items" and "collate".   The field "items" is a list of items for which you want the frequencies. The content of the items depends on the option for "collate". The value of "collate" should be a list of "columns" that the items contain. The list is limited to combinations of "wordform", "lemma", "trueCase" and "lexicalCategory". The fields that are listed in the "collate" options have to be present in each item. Here are some examples of queries:
        * ### Get frequencies of provided wordforms:
        ```javascript
          {
              "collate": ["wordform"],
              "items": [{"wordform": "test"}, {"wordform": "Test"}]
          }
        ```
        * ### Get frequencies of provided lemmas:
        ```javascript
          {
              "collate": ["lemma"],
              "items": [{"lemma": "test"}, {"lemma": "Test"}]
          }
        ```
        * ### Get frequencies of provided lemmas per lexical category:
        ```javascript
          {
              "collate": ["lemma", "lexicalCategory"],
              "items": [
                  {"lemma": "test", "lexicalCategory": "verb"},
                  {"lemma": "test", "lexicalCategory": "noun"}
              ]
          }
        ```
      operationId: getStatsFrequencyWordsSourceLang
      x-api-path-slug: statsfrequencywordssource-lang-get
      parameters:
      - in: query
        name: corpus
        description: For corpora other than nmc (New Monitor Corpus) please contact
          api@oxforddictionaries
      - in: query
        name: grammaticalFeatures
        description: The grammatical features of the word(s) to look up entered as
          a list of k:v (e
      - in: query
        name: lemma
        description: The lemma of the word to look up (e
      - in: query
        name: lexicalCategory
        description: The lexical category of the word(s) to look up (e
      - in: query
        name: limit
        description: pagination - results limit
      - in: query
        name: maxFrequency
        description: Restrict the query to entries with frequency of at most `maxFrequency`
      - in: query
        name: maxNormalizedFrequency
        description: Restrict the query to entries with frequency of at most `maxNormalizedFrequency`
      - in: query
        name: minFrequency
        description: Restrict the query to entries with frequency of at least `minFrequency`
      - in: query
        name: minNormalizedFrequency
        description: Restrict the query to entries with frequency of at least `minNormalizedFrequency`
      - in: query
        name: No Name
      - in: query
        name: offset
        description: pagination - results offset
      - in: query
        name: sort
        description: sort the resulting list by wordform, trueCase, lemma, lexicalCategory,
          frequency, normalizedFrequency
      - in: path
        name: source_lang
        description: IANA language code
      - in: query
        name: trueCase
        description: The written form of the word to look up with normalised case
          (Books --> books)
      - in: query
        name: wordform
        description: The written form of the word to look up (preserving case e
      responses:
        200:
          description: OK
      tags:
      - Stats
      - Frequency
      - Words
      - Source
      - Lang
  /entries/{source_language}/{word_id}/sentences:
    get:
      summary: Retrieve corpus sentences for a given word
      description: Use this to retrieve sentences extracted from  corpora which show
        how a word is used in the language. This is available for English and Spanish.
        For English, the sentences are linked to the correct [sense](documentation/glossary?term=sense)
        of the word in the dictionary. In Spanish, they are linked at the [headword](documentation/glossary?term=headword)
        level.
      operationId: getEntriesSourceLanguageWordSentences
      x-api-path-slug: entriessource-languageword-idsentences-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: source_language
        description: IANA language code
      responses:
        200:
          description: OK
      tags:
      - Entries
      - Source
      - Language
      - Word
      - Id
      - Sentences
  /entries/{source_lang}/{word_id}:
    get:
      summary: Retrieve dictionary information for a given word
      description: Use this to retrieve definitions, [pronunciations](documentation/glossary?term=pronunciation),
        example sentences, [grammatical information](documentation/glossary?term=grammaticalfeatures)
        and [word origins](documentation/glossary?term=etymology). It only works for
        dictionary [headwords](documentation/glossary?term=headword), so you may need
        to use the [Lemmatron](documentation/glossary?term=lemma) first if your input
        is likely to be an [inflected](documentation/glossary?term=inflection) form
        (e.g., 'swimming'). This would return the linked [headword](documentation/glossary?term=headword)
        (e.g., 'swim') which you can then use in the Entries endpoint. Unless specified
        using a region filter, the default lookup will be the Oxford Dictionary of
        English (GB).
      operationId: getEntriesSourceLangWord
      x-api-path-slug: entriessource-langword-id-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Entries
      - Source
      - Lang
      - Word
      - Id
  /entries/{source_lang}/{word_id}/antonyms:
    get:
      summary: Retrieve words that mean the opposite
      description: Retrieve words that are opposite in meaning to the input word ([antonym](documentation/glossary?term=thesaurus)).
      operationId: getEntriesSourceLangWordAntonyms
      x-api-path-slug: entriessource-langword-idantonyms-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Entries
      - Source
      - Lang
      - Word
      - Id
      - Antonyms
  /entries/{source_lang}/{word_id}/regions={region}:
    get:
      summary: Specify GB or US dictionary for English entry search
      description: USe this filter to restrict the lookup to either our Oxford Dictionary
        of English (GB) or New Oxford American Dictionary (US).
      operationId: getEntriesSourceLangWordRegionsRegion
      x-api-path-slug: entriessource-langword-idregionsregion-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: region
        description: Region filter parameter
      - in: path
        name: source_lang
        description: IANA language code
      responses:
        200:
          description: OK
      tags:
      - Entries
      - Source
      - Lang
      - Word
      - Id
      - Regions=region
  /entries/{source_lang}/{word_id}/synonyms:
    get:
      summary: Retrieve words that are similar
      description: Use this to retrieve words that are similar in meaning to the input
        word ([synonym](documentation/glossary?term=synonym)).
      operationId: getEntriesSourceLangWordSynonyms
      x-api-path-slug: entriessource-langword-idsynonyms-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Entries
      - Source
      - Lang
      - Word
      - Id
      - Synonyms
  /entries/{source_lang}/{word_id}/synonyms;antonyms:
    get:
      summary: Retrieve synonyms and antonyms for a given word
      description: Retrieve available [synonyms](documentation/glossary?term=thesaurus)
        and [antonyms](documentation/glossary?term=thesaurus) for a given word and
        language.
      operationId: getEntriesSourceLangWordSynonyms;antonyms
      x-api-path-slug: entriessource-langword-idsynonymsantonyms-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Entries
      - Source
      - Lang
      - Word
      - Id
      - Synonyms;antonyms
  /entries/{source_lang}/{word_id}/{filters}:
    get:
      summary: Apply filters to response
      description: Use filters to limit the [entry](documentation/glossary?term=entry)
        information that is returned. For example, you may only require definitions
        and not everything else, or just [pronunciations](documentation/glossary?term=pronunciation).
        The full list of filters can be retrieved from the filters Utility endpoint.
        You can also specify values within the filter using '='. For example 'grammaticalFeatures=singular'.
        Filters can also be combined using a semicolon.
      operationId: getEntriesSourceLangWordFilters
      x-api-path-slug: entriessource-langword-idfilters-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Entries
      - Source
      - Lang
      - Word
      - Id
      - Filters
  /entries/{source_translation_language}/{word_id}/translations={target_translation_language}:
    get:
      summary: Retrieve translation for a given word
      description: Use this to return translations for a given word. In the event
        that a word in the dataset does not have a direct translation, the response
        will be a [definition](documentation/glossary?term=entry) in the target language.
      operationId: getEntriesSourceTranslationLanguageWordTranslationsTargetTranslationLanguage
      x-api-path-slug: entriessource-translation-languageword-idtranslationstarget-translation-language-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: source_translation_language
        description: IANA language code
      - in: path
        name: target_translation_language
        description: IANA language code
      - in: path
        name: word_id
        description: The source word
      responses:
        200:
          description: OK
      tags:
      - Entries
      - Source
      - Translation
      - Language
      - Word
      - Id
      - Translations=target
      - Translation
      - Language
  /inflections/{source_lang}/{word_id}:
    get:
      summary: Check a word exists in the dictionary and retrieve its root form
      description: Use this to check if a word exists in the dictionary, or what 'root'
        form it links to (e.g., swimming > swim). The response tells you the possible
        [lemmas](documentation/glossary?term=lemma) for a given [inflected](documentation/glossary?term=inflection)
        word. This can then be combined with other endpoints to retrieve more information.
      operationId: getInflectionsSourceLangWord
      x-api-path-slug: inflectionssource-langword-id-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: word_id
        description: The input word
      responses:
        200:
          description: OK
      tags:
      - Inflections
      - Source
      - Lang
      - Word
      - Id
  /inflections/{source_lang}/{word_id}/{filters}:
    get:
      summary: Apply optional filters to Lemmatron response
      description: Retrieve available [lemmas](documentation/glossary?term=lemma)
        for a given [inflected](documentation/glossary?term=inflection) wordform.
        Filter results by categories.
      operationId: getInflectionsSourceLangWordFilters
      x-api-path-slug: inflectionssource-langword-idfilters-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: word_id
        description: The input word
      responses:
        200:
          description: OK
      tags:
      - Inflections
      - Source
      - Lang
      - Word
      - Id
      - Filters
  /stats/frequency/word/{source_lang}/:
    get:
      summary: Retrieve the frequency of a word derived from a corpus.
      description: |-
        This endpoint provides the frequency of a given word. When multiple database records match the query parameters, the returned frequency is the sum of the individual frequencies. For example, if the query parameters are lemma=test, the returned frequency will include the verb "test", the noun "test" and the adjective "test" in all forms (Test, tested, testing, etc.)   If you are interested in the frequency of the word "test" but want to exclude other forms (e.g., tested) use the option trueCase=test. Normally, the word "test" will be spelt with a capital letter at the beginning of a sentence. The option trueCase will ignore this and it will count "Test" and "test" as the same token. If you are interested in frequencies of "Test" and "test", use the option wordform=test or wordform=Test. Note that trueCase is not just a lower case of the word as some words are genuinely spelt with a capital letter such as the word "press" in Oxford University Press.   Parameters can be provided in PATH, GET or POST (form or json). The parameters in PATH are overriden by parameters in GET, POST and json (in that order). In PATH, individual options are separated by semicolon and values are separated by commas (where multiple values can be used). Examples:
        * PATH: /lemma=test;lexicalCategory=noun
        * GET: /?lemma=test&lexicalCategory=noun
        * POST (json):

          ```javascript
            {
              "lemma": "test",
              "lexicalCategory": "noun"
            }
          ```

         One of the options wordform/trueCase/lemma/lexicalCategory has to be provided.
      operationId: getStatsFrequencyWordSourceLang
      x-api-path-slug: statsfrequencywordsource-lang-get
      parameters:
      - in: query
        name: corpus
        description: For corpora other than nmc (New Monitor Corpus) please contact
          api@oxforddictionaries
      - in: query
        name: lemma
        description: The lemma of the word to look up (e
      - in: query
        name: lexicalCategory
        description: The lexical category of the word(s) to look up (e
      - in: query
        name: No Name
      - in: path
        name: source_lang
        description: IANA language code
      - in: query
        name: trueCase
        description: The written form of the word to look up with normalised case
          (Books --> books)
      - in: query
        name: wordform
        description: The written form of the word to look up (preserving case e
      responses:
        200:
          description: OK
      tags:
      - Stats
      - Frequency
      - Word
      - Source
      - Lang
  /entries/{source_lang}/{word_id}/definitions:
    get:
      summary: Retrieve only definitions in entry search.
      description: Find available [dictionary entries](/glossary?tag=#entry&expand)
        for given word and language. Filter results by categories.
      operationId: getEntriesSourceLangWordDefinitions
      x-api-path-slug: entriessource-langword-iddefinitions-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Entries
      - Source
      - Lang
      - Word
      - Id
      - Definitions
  /entries/{source_lang}/{word_id}/examples:
    get:
      summary: Retrieve only example sentences in entry search.
      description: Find available [dictionary entries](/glossary?tag=#entry&expand)
        for given word and language. Filter results by categories.
      operationId: getEntriesSourceLangWordExamples
      x-api-path-slug: entriessource-langword-idexamples-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Entries
      - Source
      - Lang
      - Word
      - Id
      - Examples
  /entries/{source_lang}/{word_id}/pronunciations:
    get:
      summary: Retrieve only pronunciations in entry search.
      description: Find available [dictionary entries](/glossary?tag=#entry&expand)
        for given word and language. Filter results by categories.
      operationId: getEntriesSourceLangWordPronunciations
      x-api-path-slug: entriessource-langword-idpronunciations-get
      parameters:
      - in: query
        name: No Name
      responses:
        200:
          description: OK
      tags:
      - Entries
      - Source
      - Lang
      - Word
      - Id
      - Pronunciations
  /entries/{source_lang}/{word_id}/translations={target_lang}:
    get:
      summary: Find translation for a given word.
      description: "Returns target language translations for a given word ID and source
        language. \nIn the event that a word in the dataset does not have a direct
        translation, the response will be a [definition](/glossary?tag=#entry&expand)
        in the target language."
      operationId: getEntriesSourceLangWordTranslationsTargetLang
      x-api-path-slug: entriessource-langword-idtranslationstarget-lang-get
      parameters:
      - in: query
        name: No Name
      - in: path
        name: word_id
        description: An Entry identifier
      responses:
        200:
          description: OK
      tags:
      - Entries
      - Source
      - Lang
      - Word
      - Id
      - Translations=target
      - Lang
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---