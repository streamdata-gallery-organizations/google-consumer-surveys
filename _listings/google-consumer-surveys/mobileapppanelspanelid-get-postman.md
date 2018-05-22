{
  "info": {
    "name": "Google Surveys API Get Mobile App Panel",
    "_postman_id": "c88ef70f-a2ea-403c-9eb2-195b6c55c5db",
    "description": "Retrieves a MobileAppPanel that is available to the authenticated user.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Mobile Application",
      "item": [
        {
          "id": "042fb779-bb14-49f7-bfb9-55d37c32e824",
          "name": "consumersurveys.mobileapppanels.list",
          "request": {
            "url": "http://www.googleapis.com/consumersurveys/v2/mobileAppPanels?maxResults=%7B%7D&startIndex=%7B%7D&token=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists the MobileAppPanels available to the authenticated user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f79fe744-a92b-4368-8080-897a560264cc"
            }
          ]
        },
        {
          "id": "ca5fd4d2-22c3-45d4-8798-b566331be7fd",
          "name": "consumersurveys.mobileapppanels.get",
          "request": {
            "url": {
              "protocol": "http",
              "host": "www.googleapis.com",
              "path": [
                "consumersurveys",
                "v2",
                "mobileAppPanels/:panelId"
              ],
              "variable": [
                {
                  "id": "panelId",
                  "value": "{}",
                  "type": "string"
                }
              ]
            },
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves a MobileAppPanel that is available to the authenticated user."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3a6f34dd-deb2-4073-8a8e-5cc2b620eabc"
            }
          ]
        }
      ]
    }
  ]
}