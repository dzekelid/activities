---
name: Fitbit
x-slug: fitbit
description: Find your fit with Fitbits family of fitness products that help you stay
  motivated and improve your health by tracking your activity, exercise, food, weight
  and sleep.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
x-kinRank: "9"
x-alexaRank: "2266"
tags: Activities
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/apis.md
specificationVersion: "0.14"
apis:
- name: Fitbit Get Activities .json
  x-api-slug: fitbit
  description: Get the details of a specific activity in Fitbit activities database
    in the format requested. If activity has levels, also get list of activity level
    details.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1//activities/{id}.json
  tags: Activities,Id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/activitiesid-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/activitiesid-json-get-openapi.md
- name: Fitbit Get Activities.json
  x-api-slug: fitbit
  description: Get a tree of all valid Fitbit public activities from the activities
    catalog as well as private custom activities the user created in the format requested.
    If activity has levels, also get a list of activity level details.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1//activities.json
  tags: Activities.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/activities-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/activities-json-get-openapi.md
- name: Fitbit Get User Activities Goals Weekly.json
  x-api-slug: fitbit
  description: Get a user's current weekly activity goals in the format requested
    using units in the unit system which corresponds to the Accept-Language header
    provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities/goals/weekly.json
  tags: User,-,Activities,Goals,Weekly.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitiesgoalsweekly-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitiesgoalsweekly-json-get-openapi.md
- name: Fitbit Get User Activities Goals Daily.json
  x-api-slug: fitbit
  description: Get a user's current daily activity goals in the format requested using
    units in the unit system which corresponds to the Accept-Language header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities/goals/daily.json
  tags: User,-,Activities,Goals,Daily.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitiesgoalsdaily-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitiesgoalsdaily-json-get-openapi.md
- name: Fitbit Delete User Activities Log Favorite .json
  x-api-slug: fitbit
  description: Delete the activity with the given id from user's list of favorite
    activities.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities/log/favorite/{id}.json
  tags: User,-,Activities,Log,Favorite,Id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitieslogfavoriteid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitieslogfavoriteid-json-delete-openapi.md
- name: Fitbit Post User Activities Log Favorite .json
  x-api-slug: fitbit
  description: Adds the activity with the given id to user's list of favorite activities.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities/log/favorite/{id}.json
  tags: User,-,Activities,Log,Favorite,Id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitieslogfavoriteid-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitieslogfavoriteid-json-post-openapi.md
- name: Fitbit Get User Activities Favorite.json
  x-api-slug: fitbit
  description: Get a list of a user's favorite activities in the format requested.
    A user marks an activity as favorite on the user's Activities Tab. The activity
    ids in the list can be used to create a new activity log entry via the Log Activity.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities/favorite.json
  tags: User,-,Activities,Favorite.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitiesfavorite-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitiesfavorite-json-get-openapi.md
- name: Fitbit Get User Activities Frequent.json
  x-api-slug: fitbit
  description: Get a list of a user's frequent activities in the format requested
    using units in the unit system which corresponds to the Accept-Language header
    provided. A frequent activity record contains the distance and duration values
    recorded the last time the activity was logged. The record retrieved can therefore
    be used to log the activity via the Log Activity with the same or adjusted values
    for distance and duration.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities/frequent.json
  tags: User,-,Activities,Frequent.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitiesfrequent-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitiesfrequent-json-get-openapi.md
- name: Fitbit Get User Activities Recent.json
  x-api-slug: fitbit
  description: Get a list of a user's recent activities in the format requested using
    units in the unit system which corresponds to the Accept-Language header provided.
    A recent activity record contains the distance and duration values recorded the
    last time the activity was logged. The record retrieved can therefore be used
    to log the activity via the Log Activity with the same or adjusted values for
    distance and duration.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities/recent.json
  tags: User,-,Activities,Recent.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitiesrecent-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitiesrecent-json-get-openapi.md
- name: Fitbit Get User User Activities Calories Date Start Date Or End Date End Date
    Or Period .json
  x-api-slug: fitbit
  description: Get time series in the specified range for a given resource in the
    format requested using units in the unit system which corresponds to the Accept-Language
    header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1//user/{user-id}/activities/calories/date/{start-date-or-end-date}/{end-date-or-period}.json
  tags: User,User-id,Activities,Calories,Date,Start-date-or-end-date,End-date-or-period.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useruseridactivitiescaloriesdatestartdateorenddateenddateorperiod-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useruseridactivitiescaloriesdatestartdateorenddateenddateorperiod-json-get-openapi.md
- name: Fitbit Delete User Activities Activity Log .json
  x-api-slug: fitbit
  description: Delete user's activity log entry with the given id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities/{activity-log-id}.json
  tags: User,-,Activities,Activity-log-id.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitiesactivitylogid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitiesactivitylogid-json-delete-openapi.md
- name: Fitbit Get User Activities.json
  x-api-slug: fitbit
  description: Get user's activity statistics in the format requested using units
    in the unit system which corresponds to the Accept-Language header provided. Response
    contains both lifetime statistics from the tracker device and total numbers including
    the manual activity log entries as seen on the Fitbit website dashboard.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities.json
  tags: User,-,Activities.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivities-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivities-json-get-openapi.md
- name: Fitbit Post User Activities.json
  x-api-slug: fitbit
  description: Create log entry for an activity using units in the unit system which
    corresponds to the Accept-Language header provided (or using optional custom distanceUnit).
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1//user/-/activities.json
  tags: User,-,Activities.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivities-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivities-json-post-openapi.md
- name: Fitbit Get User User Activities Date Date .json
  x-api-slug: fitbit
  description: Get a summary and list of a user's activities and activity log entries
    for a given day in the format requested using units in the unit system which corresponds
    to the Accept-Language header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1//user/{user-id}/activities/date/{date}.json
  tags: User,User-id,Activities,Date,Date.json
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useruseridactivitiesdatedate-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useruseridactivitiesdatedate-json-get-openapi.md
- name: Fitbit
  x-api-slug: fitbit
  description: Find your fit with Fitbits family of fitness products that help you
    stay motivated and improve your health by tracking your activity, exercise, food,
    weight and sleep.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Activities
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/openapi.md
x-common:
- type: x-api-json--authoritative
  url: https://www.fitbit.com/apis.json
- type: x-apigee-console
  url: https://wiki.fitbit.com/display/API/API+Explorer
- type: x-blog
  url: http://blog.fitbit.com
- type: x-blog-rss
  url: http://blog.fitbit.com/feed/
- type: x-crunchbase
  url: http://www.crunchbase.com/company/fitbit
- type: x-crunchbase
  url: https://crunchbase.com/organization/fitbit
- type: x-email
  url: privacy@fitbit.com
- type: x-github
  url: https://github.com/fitbit
- type: x-rate-limits
  url: https://wiki.fitbit.com/display/API/Rate+Limit
- type: x-twitter
  url: https://twitter.com/fitbit
- type: x-website
  url: http://fitbit.com
- type: x-website
  url: http://dev.fitbit.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---