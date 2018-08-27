---
swagger: "2.0"
x-collection-name: MotaWord
x-complete: 0
info:
  title: Mota Word Trigger a call to your callback URL related to this project.
  description: Trigger a call to your callback url related to this project..
  version: alpha-0.1.0
host: api.motaword.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /projects/{id}/callback/{actionType}:
    get:
      summary: Trigger a call to your callback URL related to this project.
      description: Trigger a call to your callback url related to this project..
      operationId: triggerCallback
      x-api-path-slug: projectsidcallbackactiontype-get
      parameters:
      - in: path
        name: actionType
        description: Callback type
      - in: path
        name: id
        description: Project ID
      responses:
        200:
          description: OK
      tags:
      - Projects
      - Callback
      - ActionType
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