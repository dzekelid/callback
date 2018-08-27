{
  "info": {
    "name": "Dezrez Initially Setup the Calendar, create Rezi Calendar, copy upto 16 Days prior into calendar, create a subscription channel for the callback",
    "_postman_id": "1815b16e-f6cb-42ce-888f-4e07925eb16d",
    "description": "Initially setup the calendar, create rezi calendar, copy upto 16 days prior into calendar, create a subscription channel for the callback.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Initially",
      "item": [
        {
          "id": "1e4c6ae6-faad-4831-afaa-03873ebabfd7",
          "name": "Sync_CalendarBypersonId",
          "request": {
            "url": {
              "protocol": "http",
              "host": "api.dezrez.com",
              "path": [
                "api/sync/calendarsetup/:personId"
              ],
              "variable": [
                {
                  "id": "personId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "header": [
              {
                "key": "Rezi-Api-Version",
                "value": "{}",
                "description": "Specifies which version of the API to call",
                "disabled": false
              },
              {
                "key": "Accept",
                "value": "*/*",
                "disabled": false
              }
            ],
            "body": {
              "mode": "raw"
            },
            "description": "Initially setup the calendar, create rezi calendar, copy upto 16 days prior into calendar, create a subscription channel for the callback."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9cd16871-23c7-4a9f-a2d5-d73b734e2f45"
            }
          ]
        }
      ]
    }
  ]
}