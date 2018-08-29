---
swagger: "2.0"
x-collection-name: Oxford Dictionaries
x-complete: 0
info:
  title: Oxford Dictionaries Retrieve a list of frequencies of a word/words derived
    from a corpus.
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