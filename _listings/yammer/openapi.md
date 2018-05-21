---
swagger: "2.0"
x-collection-name: Yammer
x-complete: 1
info:
  title: Yammer API
  description: todo-add-description
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
---