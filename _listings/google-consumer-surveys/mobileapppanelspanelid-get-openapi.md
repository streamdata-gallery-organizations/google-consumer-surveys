---
swagger: "2.0"
x-collection-name: Google Consumer Surveys
x-complete: 0
info:
  title: Google Surveys API Get Mobile App Panel
  description: Retrieves a MobileAppPanel that is available to the authenticated user.
  contact:
    name: Google
    url: https://google.com
  version: v2
host: www.googleapis.com
basePath: /consumersurveys/v2
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /mobileAppPanels:
    get:
      summary: Get Mobile App Panels
      description: Lists the MobileAppPanels available to the authenticated user.
      operationId: consumersurveys.mobileapppanels.list
      x-api-path-slug: mobileapppanels-get
      parameters:
      - in: query
        name: maxResults
      - in: query
        name: startIndex
      - in: query
        name: token
      responses:
        200:
          description: OK
      tags:
      - Mobile Application
  /mobileAppPanels/{panelId}:
    get:
      summary: Get Mobile App Panel
      description: Retrieves a MobileAppPanel that is available to the authenticated
        user.
      operationId: consumersurveys.mobileapppanels.get
      x-api-path-slug: mobileapppanelspanelid-get
      parameters:
      - in: path
        name: panelId
        description: External URL ID for the panel
      responses:
        200:
          description: OK
      tags:
      - Mobile Application
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