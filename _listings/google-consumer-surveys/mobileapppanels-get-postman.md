{
  "info": {
    "name": "Google Surveys API Get Mobile App Panels",
    "_postman_id": "83ed40b5-ed85-4d04-8a03-78337e903922",
    "description": "Lists the MobileAppPanels available to the authenticated user.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Mobile Application",
      "item": [
        {
          "id": "26c1c37d-eb01-417b-bc9a-0a70beb3e154",
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
              "id": "e6a0c9f2-e6db-492c-bbab-a42df7f7a662"
            }
          ]
        }
      ]
    }
  ]
}