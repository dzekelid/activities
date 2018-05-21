{
  "info": {
    "name": "Yammer API",
    "_postman_id": "6e51da09-22d0-428f-9a09-7930841e08dc",
    "description": "TODO: Add Description",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "activities",
      "item": [
        {
          "id": "42cd1911-8604-449a-86cc-8a8fb5beb134",
          "name": "Get_View Activities_",
          "request": {
            "url": {
              "protocol": "http",
              "host": "example.com",
              "path": [
                ":yamURI/streams/activities.json"
              ],
              "variable": [
                {
                  "id": "yamURI",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get View Activities"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1b42ba2d-c161-4a39-9c85-29f1da8f4fe5"
            }
          ]
        }
      ]
    }
  ]
}