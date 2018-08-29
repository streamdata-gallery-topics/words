{
  "info": {
    "name": "Wordnik Fetches audio metadata for a word.",
    "_postman_id": "be557239-0cbd-4a99-832b-8124040327ff",
    "description": "The metadata includes a time-expiring fileUrl which allows reading the audio file directly from the API.  Currently only audio pronunciations from the American Heritage Dictionary in mp3 format are supported.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Words",
      "item": [
        {
          "id": "fafe63a6-bcfe-4f87-9684-d463baf55baa",
          "name": "getAudio",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.wordnik.com",
              "path": [
                "v4",
                "word.json/:word/audio"
              ],
              "query": [
                {
                  "key": "limit",
                  "value": "%7B%7D",
                  "disabled": false
                },
                {
                  "key": "useCanonical",
                  "value": "%7B%7D",
                  "disabled": false
                }
              ],
              "variable": [
                {
                  "id": "word",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "The metadata includes a time-expiring fileUrl which allows reading the audio file directly from the API.  Currently only audio pronunciations from the American Heritage Dictionary in mp3 format are supported."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "90154a4b-1e54-494b-a2aa-0e053b6b5605"
            }
          ]
        }
      ]
    }
  ]
}