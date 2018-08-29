---
name: Wordnik
x-slug: wordnik
description: Wordnik is an online English dictionary and language resource that provides
  dictionary and thesaurus content, some of it based on print dictionaries such as
  the Century Dictionary, the American Heritage Dictionary, WordNet, and GCIDE. Wordnik
  has collected a corpus of billions of words which it uses to display example sentences,
  allowing it to provide information on a much larger set of words than a typical
  dictionary.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
x-kinRank: "8"
x-alexaRank: "46540"
tags: Words
created: "2018-08-28"
modified: "2018-08-28"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/words/master/_listings/wordnik/apis.md
specificationVersion: "0.14"
apis:
- name: Wordnik - Fetches WordList objects for the logged-in user.
  x-api-slug: account-jsonwordlists-get
  description: Fetches wordlist objects for the logged-in user..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4
  tags: Content, Dictionary, internet, Technology, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/words/master/_listings/wordnik/account-jsonwordlists-get-openapi.md
- name: Wordnik - Given a word as a string, returns the WordObject that represents
    it
  x-api-slug: word-jsonword-get
  description: Given a word as a string, returns the wordobject that represents it.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4
  tags: Content, Dictionary, internet, Technology, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/words/master/_listings/wordnik/word-jsonword-get-openapi.md
- name: Wordnik - Fetches audio metadata for a word.
  x-api-slug: word-jsonwordaudio-get
  description: The metadata includes a time-expiring fileUrl which allows reading
    the audio file directly from the API.  Currently only audio pronunciations from
    the American Heritage Dictionary in mp3 format are supported.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4
  tags: Content, Dictionary, internet, Technology, General Data
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/words/master/_listings/wordnik/word-jsonwordaudio-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/words/master/_listings/wordnik/word-jsonwordaudio-get-openapi.md
- name: Wordnik - Return definitions for a word
  x-api-slug: word-jsonworddefinitions-get
  description: Return definitions for a word.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4
  tags: Content, Dictionary, internet, Technology, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/words/master/_listings/wordnik/word-jsonworddefinitions-get-openapi.md
- name: Wordnik - Fetches etymology data
  x-api-slug: word-jsonwordetymologies-get
  description: Fetches etymology data.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4
  tags: Content, Dictionary, internet, Technology, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/words/master/_listings/wordnik/word-jsonwordetymologies-get-openapi.md
- name: Wordnik - Returns examples for a word
  x-api-slug: word-jsonwordexamples-get
  description: Returns examples for a word.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4
  tags: Content, Dictionary, internet, Technology, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/words/master/_listings/wordnik/word-jsonwordexamples-get-openapi.md
- name: Wordnik - Returns word usage over time
  x-api-slug: word-jsonwordfrequency-get
  description: Returns word usage over time.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4
  tags: Content, Dictionary, internet, Technology, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/words/master/_listings/wordnik/word-jsonwordfrequency-get-openapi.md
- name: Wordnik - Returns syllable information for a word
  x-api-slug: word-jsonwordhyphenation-get
  description: Returns syllable information for a word.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4
  tags: Content, Dictionary, internet, Technology, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/words/master/_listings/wordnik/word-jsonwordhyphenation-get-openapi.md
- name: Wordnik - Fetches bi-gram phrases for a word
  x-api-slug: word-jsonwordphrases-get
  description: Fetches bi-gram phrases for a word.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4
  tags: Content, Dictionary, internet, Technology, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/words/master/_listings/wordnik/word-jsonwordphrases-get-openapi.md
- name: Wordnik - Returns text pronunciations for a given word
  x-api-slug: word-jsonwordpronunciations-get
  description: Returns text pronunciations for a given word.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4
  tags: Content, Dictionary, internet, Technology, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/words/master/_listings/wordnik/word-jsonwordpronunciations-get-openapi.md
- name: Wordnik - Given a word as a string, returns relationships from the Word Graph
  x-api-slug: word-jsonwordrelatedwords-get
  description: Given a word as a string, returns relationships from the word graph.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4
  tags: Content, Dictionary, internet, Technology, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/words/master/_listings/wordnik/word-jsonwordrelatedwords-get-openapi.md
- name: Wordnik - Returns a top example for a word
  x-api-slug: word-jsonwordtopexample-get
  description: Returns a top example for a word.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4
  tags: Content, Dictionary, internet, Technology, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/words/master/_listings/wordnik/word-jsonwordtopexample-get-openapi.md
- name: Wordnik - Fetches words in a WordList
  x-api-slug: wordlist-jsonpermalinkwords-get
  description: Fetches words in a wordlist.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4
  tags: Content, Dictionary, internet, Technology, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/words/master/_listings/wordnik/wordlist-jsonpermalinkwords-get-openapi.md
- name: Wordnik - Adds words to a WordList
  x-api-slug: wordlist-jsonpermalinkwords-post
  description: Adds words to a wordlist.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4
  tags: Content, Dictionary, internet, Technology, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/words/master/_listings/wordnik/wordlist-jsonpermalinkwords-post-openapi.md
- name: Wordnik - Creates a WordList.
  x-api-slug: wordlists-json-post
  description: Creates a wordlist..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4
  tags: Content, Dictionary, internet, Technology, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/words/master/_listings/wordnik/wordlists-json-post-openapi.md
- name: Wordnik - Returns a single random WordObject
  x-api-slug: words-jsonrandomword-get
  description: Returns a single random wordobject.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4
  tags: Content, Dictionary, internet, Technology, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/words/master/_listings/wordnik/words-jsonrandomword-get-openapi.md
- name: Wordnik - Returns an array of random WordObjects
  x-api-slug: words-jsonrandomwords-get
  description: Returns an array of random wordobjects.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4
  tags: Content, Dictionary, internet, Technology, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/words/master/_listings/wordnik/words-jsonrandomwords-get-openapi.md
- name: Wordnik - Reverse dictionary search
  x-api-slug: words-jsonreversedictionary-get
  description: Reverse dictionary search.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4
  tags: Content, Dictionary, internet, Technology, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/words/master/_listings/wordnik/words-jsonreversedictionary-get-openapi.md
- name: Wordnik - Searches words
  x-api-slug: words-jsonsearchquery-get
  description: Searches words.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4
  tags: Content, Dictionary, internet, Technology, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/words/master/_listings/wordnik/words-jsonsearchquery-get-openapi.md
- name: Wordnik - Returns a specific WordOfTheDay
  x-api-slug: words-jsonwordoftheday-get
  description: Returns a specific wordoftheday.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4
  tags: Content, Dictionary, internet, Technology, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/words/master/_listings/wordnik/words-jsonwordoftheday-get-openapi.md
- name: Wordnik - Fetches WordList objects for the logged-in user.
  x-api-slug: account-jsonwordlists-get
  description: Fetches wordlist objects for the logged-in user..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4
  tags: Content, Dictionary, internet, Technology, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/words/master/_listings/wordnik/account-jsonwordlists-get-openapi.md
- name: Wordnik - Fetches WordList objects for the logged-in user.
  x-api-slug: account-jsonwordlists-get
  description: Fetches wordlist objects for the logged-in user..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/2708-wordnik.jpg
  humanURL: http://wordnik.com
  baseURL: https://api.wordnik.com//v4
  tags: Content, Dictionary, internet, Technology, General Data
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/words/master/_listings/wordnik/account-jsonwordlists-get-openapi.md
x-common:
- type: x-api-gallery
  url: http://wikipedia.api.gallery.streamdata.io
- type: x-api-stack
  url: http://wordnik.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/wordnik
- type: x-developer
  url: http://developer.wordnik.com/
- type: x-documentation
  url: http://developer.wordnik.com/docs.html
- type: x-email
  url: feedback@wordnik.com
- type: x-email
  url: support@wordnik.com
- type: x-email
  url: privacy@wordnik.com
- type: x-email
  url: dmca@wordnik.com
- type: x-github
  url: https://github.com/wordnik
- type: x-twitter
  url: https://twitter.com/wordnik
- type: x-website
  url: http://wordnik.com
- type: x-website
  url: https://www.wordnik.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---