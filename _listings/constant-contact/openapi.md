---
swagger: "2.0"
x-collection-name: Constant Contact
x-complete: 1
info:
  title: Constant Contact
  description: make-constant-contacts-leading-email-and-event-marketing-services-accessible-directly-from-your-app-
  version: 1.0.0
host: api.constantcontact.com
basePath: /ws/customers/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /{username}/activities:
    get:
      summary: List Activities
      description: List Activities
      operationId: list-activities
      x-api-path-slug: usernameactivities-get
      parameters:
      - in: path
        name: username
      responses:
        200:
          description: OK
      tags:
      - List
      - Activities
---