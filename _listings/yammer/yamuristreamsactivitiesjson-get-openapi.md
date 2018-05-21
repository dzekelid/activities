---
swagger: "2.0"
x-collection-name: Yammer
x-complete: 0
info:
  title: Yammer API Get View Activities
  description: Get View Activities
  version: 1.0.0
host: example.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  '{yamURI}/streams/activities.json':
    get:
      summary: Get View Activities
      description: Get View Activities
      operationId: Get_View Activities_
      x-api-path-slug: yamuristreamsactivitiesjson-get
      parameters:
      - in: formData
        name: pending_attachment1
      - in: path
        name: yamURI
      responses:
        200:
          description: OK
      tags:
      - Activities
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