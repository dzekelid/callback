{
  "info": {
    "name": "3scale Google Callback",
    "_postman_id": "73a60865-5c77-41a4-af3d-afef871e0a54",
    "description": "This endpoint should never be accessed directly by clients, it is only ever used during the google oauth process during oauth.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "id": "007c749b-eb1e-4ff0-a93f-9b7966175f7a",
      "name": "OauthGoogleAuthByHostnameGet",
      "request": {
        "url": {
          "protocol": "http",
          "host": "http",
          "path": [
            ":hostname/oauth/google/auth"
          ],
          "variable": [
            {
              "id": "hostname",
              "value": "{}",
              "type": "string"
            }
          ]
        },
        "method": "GET",
        "header": [
          {
            "key": "Accept",
            "value": "*/*",
            "disabled": false
          }
        ],
        "body": {
          "mode": "raw"
        },
        "description": "This endpoint should never be accessed directly by clients, it is only ever used during the google oauth process during oauth."
      },
      "response": [
        {
          "status": "OK",
          "code": 200,
          "name": "Response_200",
          "id": "11448d4e-11c6-4e9c-90c8-ef450faa7603"
        }
      ]
    }
  ]
}