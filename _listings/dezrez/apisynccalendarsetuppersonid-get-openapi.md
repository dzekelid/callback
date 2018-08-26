---
swagger: "2.0"
x-collection-name: Dezrez
x-complete: 0
info:
  title: Dezrez Initially Setup the Calendar, create Rezi Calendar, copy upto 16 Days
    prior into calendar, create a subscription channel for the callback
  version: 1.0.0
  description: Initially setup the calendar, create rezi calendar, copy upto 16 days
    prior into calendar, create a subscription channel for the callback.
host: api.dezrez.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /api/sync/calendarsetup/{personId}:
    get:
      summary: Initially Setup the Calendar, create Rezi Calendar, copy upto 16 Days
        prior into calendar, create a subscription channel for the callback
      description: Initially setup the calendar, create rezi calendar, copy upto 16
        days prior into calendar, create a subscription channel for the callback.
      operationId: Sync_CalendarBypersonId
      x-api-path-slug: apisynccalendarsetuppersonid-get
      parameters:
      - in: path
        name: personId
      - in: header
        name: Rezi-Api-Version
        description: Specifies which version of the API to call
      responses:
        200:
          description: OK
      tags:
      - Initially
      - Setup
      - Calendar
      - ""
      - Create
      - Rezi
      - Calendar
      - ""
      - Copy
      - Upto
      - "16"
      - Days
      - Prior
      - Into
      - Calendar
      - ""
      - Create
      - Subscription
      - Channelthe
      - Callback
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