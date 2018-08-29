---
swagger: "2.0"
x-collection-name: Wordnik
x-complete: 0
info:
  title: Wordnik Return definitions for a word
  description: Return definitions for a word.
  version: "4.0"
host: api.wordnik.com
basePath: /v4
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /account.json/wordLists:
    get:
      summary: Fetches WordList objects for the logged-in user.
      description: Fetches wordlist objects for the logged-in user..
      operationId: getWordListsForLoggedInUser
      x-api-path-slug: account-jsonwordlists-get
      parameters:
      - in: header
        name: auth_token
        description: auth_token of logged-in user
      - in: query
        name: limit
        description: Maximum number of results to return
      - in: query
        name: skip
        description: Results to skip
      responses:
        200:
          description: OK
      tags:
      - Account
      - Words
      - Lists
  /word.json/{word}:
    get:
      summary: Given a word as a string, returns the WordObject that represents it
      description: Given a word as a string, returns the wordobject that represents
        it.
      operationId: getWord
      x-api-path-slug: word-jsonword-get
      parameters:
      - in: query
        name: includeSuggestions
        description: Return suggestions (for correct spelling, case variants, etc
      - in: query
        name: useCanonical
        description: If true will try to return the correct word root (cats -> cat)
      - in: path
        name: word
        description: String value of WordObject to return
      responses:
        200:
          description: OK
      tags:
      - Words
  /word.json/{word}/audio:
    get:
      summary: Fetches audio metadata for a word.
      description: The metadata includes a time-expiring fileUrl which allows reading
        the audio file directly from the API.  Currently only audio pronunciations
        from the American Heritage Dictionary in mp3 format are supported.
      operationId: getAudio
      x-api-path-slug: word-jsonwordaudio-get
      parameters:
      - in: query
        name: limit
        description: Maximum number of results to return
      - in: query
        name: useCanonical
        description: Use the canonical form of the word
      - in: path
        name: word
        description: Word to get audio for
      responses:
        200:
          description: OK
      tags:
      - Words
      - Audio
  /word.json/{word}/definitions:
    get:
      summary: Return definitions for a word
      description: Return definitions for a word.
      operationId: getDefinitions
      x-api-path-slug: word-jsonworddefinitions-get
      parameters:
      - in: query
        name: includeRelated
        description: Return related words with definitions
      - in: query
        name: includeTags
        description: Return a closed set of XML tags in response
      - in: query
        name: limit
        description: Maximum number of results to return
      - in: query
        name: partOfSpeech
        description: CSV list of part-of-speech types
      - in: query
        name: sourceDictionaries
        description: Source dictionary to return definitions from
      - in: query
        name: useCanonical
        description: If true will try to return the correct word root (cats -> cat)
      - in: path
        name: word
        description: Word to return definitions for
      responses:
        200:
          description: OK
      tags:
      - Words
      - Definitions
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