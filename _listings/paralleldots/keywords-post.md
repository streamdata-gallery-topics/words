---
swagger: "2.0"
info:
  title: ParallelDots AI APIs Docs
  description: Our powerful Deep Learning powered APIs can comprehend a huge amount
    of unstructured text and visual content to empower your products.
  version: 1.0.0
host: apis.paralleldots.com
basePath: /v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /keywords:
    post:
      summary: Keywords
      description: |-
        # Introduction
        What does your API do?

        Keyword Generator are powerful tools in text analysis that can be used to index data, generate tag clouds and accelerate the searching time
      operationId: KeywordsPost
      parameters:
      - in: formData
        name: api_key
      - in: formData
        name: text
      responses:
        200:
          description: OK
      tags:
      - machine learning
      - keywords
      - analysis
definitions: []
x-collection-name: ParallelDots
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