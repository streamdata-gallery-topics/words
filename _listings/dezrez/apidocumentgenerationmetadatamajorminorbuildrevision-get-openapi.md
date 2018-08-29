---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Returns the data contract to configure the word plugin for creating
    templates
  version: 1.0.0
  description: Returns the data contract to configure the word plugin for creating
    templates.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/documentgeneration/metadata/{major}/{minor}/{build}/{revision}:
    get:
      summary: Returns the data contract to configure the word plugin for creating
        templates
      description: Returns the data contract to configure the word plugin for creating
        templates.
      operationId: DocumentGeneration_GetLetterEditorDataContractBymajorByminorBybuildByrevision
      x-api-path-slug: apidocumentgenerationmetadatamajorminorbuildrevision-get
      parameters:
      - in: path
        name: build
      - in: path
        name: major
      - in: path
        name: minor
      - in: path
        name: revision
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Returns
      - Data
      - Contract
      - To
      - Configure
      - Word
      - Plugincreating
      - Templates
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