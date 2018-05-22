---
name: Google Consumer Surveys
x-slug: google-consumer-surveys
description: Google Consumer Surveys brings journalists the latest data on elections
  and political opinions. Create your own surveys for custom insights specific to
  your audience for free. Faster and more accurate online polling. Imagine surveying
  public opinion with a tool so precise, it could predict the nation&rsquo;s next
  president. That tool is Google Consumer Surveys.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Consumer-Surveys-earn-money-payment.jpg
x-kinRank: "9"
x-alexaRank: ""
tags: Google Consumer Surveys
created: "2018-05-21"
modified: "2018-05-21"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-consumer-surveys/master/_listings/google-consumer-surveys/apis.md
specificationVersion: "0.14"
apis:
- name: Google Surveys API Get Mobile App Panels
  x-api-slug: google-surveys-api
  description: Lists the MobileAppPanels available to the authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Consumer-Surveys-earn-money-payment.jpg
  humanURL: https://surveys.withgoogle.com/
  baseURL: ://www.googleapis.com//consumersurveys/v2//mobileAppPanels
  tags: Mobile Application
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-consumer-surveys/master/_listings/google-consumer-surveys/mobileapppanels-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-consumer-surveys/master/_listings/google-consumer-surveys/mobileapppanels-get-openapi.md
- name: Google Surveys API Get Mobile App Panel
  x-api-slug: google-surveys-api
  description: Retrieves a MobileAppPanel that is available to the authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Consumer-Surveys-earn-money-payment.jpg
  humanURL: https://surveys.withgoogle.com/
  baseURL: ://www.googleapis.com//consumersurveys/v2//mobileAppPanels/{panelId}
  tags: Mobile Application
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-consumer-surveys/master/_listings/google-consumer-surveys/mobileapppanelspanelid-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-consumer-surveys/master/_listings/google-consumer-surveys/mobileapppanelspanelid-get-openapi.md
- name: Google Surveys API Update Mobile App Panel
  x-api-slug: google-surveys-api
  description: Updates a MobileAppPanel. Currently the only property that can be updated
    is the owners property.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Consumer-Surveys-earn-money-payment.jpg
  humanURL: https://surveys.withgoogle.com/
  baseURL: ://www.googleapis.com//consumersurveys/v2//mobileAppPanels/{panelId}
  tags: Mobile Application
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-consumer-surveys/master/_listings/google-consumer-surveys/mobileapppanelspanelid-put-openapi.md
- name: Google Surveys API Get Surveys
  x-api-slug: google-surveys-api
  description: Lists the surveys owned by the authenticated user.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Consumer-Surveys-earn-money-payment.jpg
  humanURL: https://surveys.withgoogle.com/
  baseURL: ://www.googleapis.com//consumersurveys/v2//surveys
  tags: Survey
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-consumer-surveys/master/_listings/google-consumer-surveys/surveys-get-openapi.md
- name: Google Surveys API Create Survey
  x-api-slug: google-surveys-api
  description: Creates a survey.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Consumer-Surveys-earn-money-payment.jpg
  humanURL: https://surveys.withgoogle.com/
  baseURL: ://www.googleapis.com//consumersurveys/v2//surveys
  tags: Survey
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-consumer-surveys/master/_listings/google-consumer-surveys/surveys-post-openapi.md
- name: Google Surveys API Begin Survey
  x-api-slug: google-surveys-api
  description: Begins running a survey.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Consumer-Surveys-earn-money-payment.jpg
  humanURL: https://surveys.withgoogle.com/
  baseURL: ://www.googleapis.com//consumersurveys/v2//surveys/{resourceId}/start
  tags: Survey
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-consumer-surveys/master/_listings/google-consumer-surveys/surveysresourceidstart-post-openapi.md
- name: Google Surveys API Stop Survey
  x-api-slug: google-surveys-api
  description: Stops a running survey.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Consumer-Surveys-earn-money-payment.jpg
  humanURL: https://surveys.withgoogle.com/
  baseURL: ://www.googleapis.com//consumersurveys/v2//surveys/{resourceId}/stop
  tags: Survey
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-consumer-surveys/master/_listings/google-consumer-surveys/surveysresourceidstop-post-openapi.md
- name: Google Surveys API Remove Survey
  x-api-slug: google-surveys-api
  description: Removes a survey from view in all user GET requests.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Consumer-Surveys-earn-money-payment.jpg
  humanURL: https://surveys.withgoogle.com/
  baseURL: ://www.googleapis.com//consumersurveys/v2//surveys/{surveyUrlId}
  tags: Survey
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-consumer-surveys/master/_listings/google-consumer-surveys/surveyssurveyurlid-delete-openapi.md
- name: Google Surveys API Get Survey
  x-api-slug: google-surveys-api
  description: Retrieves information about the specified survey.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Consumer-Surveys-earn-money-payment.jpg
  humanURL: https://surveys.withgoogle.com/
  baseURL: ://www.googleapis.com//consumersurveys/v2//surveys/{surveyUrlId}
  tags: Survey
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-consumer-surveys/master/_listings/google-consumer-surveys/surveyssurveyurlid-get-openapi.md
- name: Google Surveys API Update Survey
  x-api-slug: google-surveys-api
  description: Updates a survey. Currently the only property that can be updated is
    the owners property.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Consumer-Surveys-earn-money-payment.jpg
  humanURL: https://surveys.withgoogle.com/
  baseURL: ://www.googleapis.com//consumersurveys/v2//surveys/{surveyUrlId}
  tags: Survey
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-consumer-surveys/master/_listings/google-consumer-surveys/surveyssurveyurlid-put-openapi.md
- name: Google Surveys API Get Survey Results
  x-api-slug: google-surveys-api
  description: Retrieves any survey results that have been produced so far. Results
    are formatted as an Excel file. You must add "?alt=media" to the URL as an argument
    to get results.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Consumer-Surveys-earn-money-payment.jpg
  humanURL: https://surveys.withgoogle.com/
  baseURL: ://www.googleapis.com//consumersurveys/v2//surveys/{surveyUrlId}/results
  tags: Survey
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-consumer-surveys/master/_listings/google-consumer-surveys/surveyssurveyurlidresults-get-openapi.md
- name: Google Surveys API
  x-api-slug: google-surveys-api
  description: Google Consumer Surveys brings journalists the latest data on elections
    and political opinions. Create your own surveys for custom insights specific to
    your audience for free. Faster and more accurate online polling. Imagine surveying
    public opinion with a tool so precise, it could predict the nation&rsquo;s next
    president. That tool is Google Consumer Surveys.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Google-Consumer-Surveys-earn-money-payment.jpg
  humanURL: https://surveys.withgoogle.com/
  baseURL: ://www.googleapis.com//consumersurveys/v2
  tags: Google Consumer Surveys
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/google-consumer-surveys/master/_listings/google-consumer-surveys/openapi.md
x-common:
- type: x-developer
  url: https://developers.google.com/surveys/
- type: x-getting-started
  url: https://developers.google.com/surveys/v2/guides/getting-started-guide
- type: x-pricing
  url: https://developers.google.com/surveys/v2/guides/incidence-pricing
- type: x-rate-limits
  url: https://developers.google.com/surveys/v2/limits
- type: x-samples
  url: https://github.com/google/surveys
- type: x-terms-of-service
  url: https://developers.google.com/surveys/terms
- type: x-website
  url: https://surveys.withgoogle.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---