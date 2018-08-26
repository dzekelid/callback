---
swagger: "2.0"
x-collection-name: MotaWord
x-complete: 1
info:
  title: Mota Word
  description: use-motaword-api-to-post-and-track-your-translation-projects-
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
---