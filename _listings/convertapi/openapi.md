swagger: "2.0"
x-collection-name: ConvertAPI
x-complete: 1
info:
  title: Convert API
  description: the-convertapi-provides-online-api-for-creating-pdf-and-images-from-various-sources-like-word-document-web-pages-or-raw-html-codes--in-just-few-minutes-you-can-integrate-it-into-your-application-and-use-it-easily--return-to-apis-list-
  version: v1
host: do.convertapi.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Word2Image:
    post:
      summary: Word to Image
      description: The API for converting Word documents to PDF files and Images.
        These file formats doc, docx, dot, dotx, wpd, wps, wri can be converted to
        png, jpg, tif.
      operationId: word2image
      x-api-path-slug: word2image-post
      parameters:
      - in: query
        name: AlternativeParser
        description: If some objects are missing in converted Pdf files from original
          source files this option can be enabled to improve conversion
      - in: query
        name: ApiKey
        description: API Key should be passed if you purchased membership with credits
      - in: query
        name: File
        description: 'Supported source file formats: doc, docx, dot, dotx, wpd, wps,
          wri'
      - in: query
        name: ImageResolutionH
        description: Image horizontal resolution (DPI)
      - in: query
        name: ImageResolutionV
        description: Image vertical resolution (DPI)
      - in: query
        name: JpgQuality
        description: Jpg image quality
      - in: query
        name: OutputFormat
        description: Supported output file formats png, jpg, tif
      - in: query
        name: StoreFile
        description: Store file on server and return url to file instead of file stream
          response
      - in: query
        name: Timeout
        description: Conversion timeout in seconds
      responses:
        200:
          description: OK
      tags:
      - Word
      - Image
  /Word2Pdf:
    post:
      summary: Word to PDF
      description: The API for converting Word documents to PDF files and Images.
        These file formats doc, docx, dot, dotx, wpd, wps, wri can be converted to
        pdf, pdfa, png, jpg, tif.
      operationId: word2pdf
      x-api-path-slug: word2pdf-post
      parameters:
      - in: query
        name: AlternativeParser
        description: If some objects are missing in converted Pdf files from original
          source files this option can be enabled to improve conversion
      - in: query
        name: ApiKey
        description: API Key should be passed if you purchased membership with credits
      - in: query
        name: DocumentAuthor
        description: Set the author of the generated Pdf file
      - in: query
        name: DocumentKeywords
        description: Set the keywords of the generated Pdf file
      - in: query
        name: DocumentSubject
        description: Set the subject of the generated Pdf file
      - in: query
        name: DocumentTitle
        description: Set the title of the generated Pdf file
      - in: query
        name: File
        description: 'Supported source file formats: doc, docx, dot, dotx, wpd, wps,
          wri'
      - in: query
        name: OutputFormat
        description: Supported output file formats pdf, pdfa, png, jpg, tif
      - in: query
        name: StoreFile
        description: Store file on server and return url to file instead of file stream
          response
      - in: query
        name: Timeout
        description: Conversion timeout in seconds
      responses:
        200:
          description: OK
      tags:
      - Word
      - PDF