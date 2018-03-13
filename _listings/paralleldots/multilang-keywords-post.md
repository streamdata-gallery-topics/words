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
  /multilang_keywords:
    post:
      summary: Multilang_Keywords
      description: |-
        # Introduction
        What does your API do?

        Extract Keywords from different languages using this API
      operationId: MultilangKeywordsPost
      parameters:
      - in: formData
        name: api_key
      - in: formData
        name: lang_code
      - in: formData
        name: text
      responses:
        200:
          description: OK
      tags:
      - machine learning
      - multilang_keywords
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