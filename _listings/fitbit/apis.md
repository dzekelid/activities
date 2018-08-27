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
created: "2018-08-27"
modified: "2018-08-27"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/apis.md
specificationVersion: "0.14"
apis:
- name: Fitbit - Get Activities .json
  x-api-slug: activitiesid-json-get
  description: Get the details of a specific activity in Fitbit activities database
    in the format requested. If activity has levels, also get list of activity level
    details.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/activitiesid-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/activitiesid-json-get-openapi.md
- name: Fitbit - Get User Activities Goals Weekly.json
  x-api-slug: useractivitiesgoalsweekly-json-get
  description: Get a user's current weekly activity goals in the format requested
    using units in the unit system which corresponds to the Accept-Language header
    provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitiesgoalsweekly-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitiesgoalsweekly-json-get-openapi.md
- name: Fitbit - Get User Activities Goals Daily.json
  x-api-slug: useractivitiesgoalsdaily-json-get
  description: Get a user's current daily activity goals in the format requested using
    units in the unit system which corresponds to the Accept-Language header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitiesgoalsdaily-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitiesgoalsdaily-json-get-openapi.md
- name: Fitbit - Delete User Activities Log Favorite .json
  x-api-slug: useractivitieslogfavoriteid-json-delete
  description: Delete the activity with the given id from user's list of favorite
    activities.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitieslogfavoriteid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitieslogfavoriteid-json-delete-openapi.md
- name: Fitbit - Post User Activities Log Favorite .json
  x-api-slug: useractivitieslogfavoriteid-json-post
  description: Adds the activity with the given id to user's list of favorite activities.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitieslogfavoriteid-json-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitieslogfavoriteid-json-post-openapi.md
- name: Fitbit - Get User Activities Favorite.json
  x-api-slug: useractivitiesfavorite-json-get
  description: Get a list of a user's favorite activities in the format requested.
    A user marks an activity as favorite on the user's Activities Tab. The activity
    ids in the list can be used to create a new activity log entry via the Log Activity.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitiesfavorite-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitiesfavorite-json-get-openapi.md
- name: Fitbit - Get User Activities Frequent.json
  x-api-slug: useractivitiesfrequent-json-get
  description: Get a list of a user's frequent activities in the format requested
    using units in the unit system which corresponds to the Accept-Language header
    provided. A frequent activity record contains the distance and duration values
    recorded the last time the activity was logged. The record retrieved can therefore
    be used to log the activity via the Log Activity with the same or adjusted values
    for distance and duration.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitiesfrequent-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitiesfrequent-json-get-openapi.md
- name: Fitbit - Get User Activities Recent.json
  x-api-slug: useractivitiesrecent-json-get
  description: Get a list of a user's recent activities in the format requested using
    units in the unit system which corresponds to the Accept-Language header provided.
    A recent activity record contains the distance and duration values recorded the
    last time the activity was logged. The record retrieved can therefore be used
    to log the activity via the Log Activity with the same or adjusted values for
    distance and duration.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitiesrecent-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitiesrecent-json-get-openapi.md
- name: Fitbit - Get User User Activities Calories Date Start Date Or End Date End
    Date Or Period .json
  x-api-slug: useruseridactivitiescaloriesdatestartdateorenddateenddateorperiod-json-get
  description: Get time series in the specified range for a given resource in the
    format requested using units in the unit system which corresponds to the Accept-Language
    header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useruseridactivitiescaloriesdatestartdateorenddateenddateorperiod-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useruseridactivitiescaloriesdatestartdateorenddateenddateorperiod-json-get-openapi.md
- name: Fitbit - Delete User Activities Activity Log .json
  x-api-slug: useractivitiesactivitylogid-json-delete
  description: Delete user's activity log entry with the given id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitiesactivitylogid-json-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useractivitiesactivitylogid-json-delete-openapi.md
- name: Fitbit - Get User User Activities Date Date .json
  x-api-slug: useruseridactivitiesdatedate-json-get
  description: Get a summary and list of a user's activities and activity log entries
    for a given day in the format requested using units in the unit system which corresponds
    to the Accept-Language header provided.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useruseridactivitiesdatedate-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/useruseridactivitiesdatedate-json-get-openapi.md
- name: Fitbit - Get Activities.json
  x-api-slug: activities-json-get
  description: Get a tree of all valid Fitbit public activities from the activities
    catalog as well as private custom activities the user created in the format requested.
    If activity has levels, also get a list of activity level details.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/200-fitbit.jpg
  humanURL: http://fitbit.com
  baseURL: https://api.fitbit.com//1
  tags: Sports, Excercise, Devices, Fitness, Wearables, Indie EdTech Data Jam, Stack,
    Mobile, Technology, API Provider, , Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/activities-json-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/activities/master/_listings/fitbit/activities-json-get-openapi.md
x-common:
- type: x-api-json--authoritative
  url: https://www.fitbit.com/apis.json
- type: x-openapi
  url: https://dev.fitbit.com/reference/web-api/explore/fitbit-web-api.swagger.json
- type: x-api-gallery
  url: http://first.trust.bank.api.gallery.streamdata.io
- type: x-api-stack
  url: http://fitbit.stack.network
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