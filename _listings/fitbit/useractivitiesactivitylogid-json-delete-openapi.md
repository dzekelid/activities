---
swagger: "2.0"
x-collection-name: Fitbit
x-complete: 0
info:
  title: Fitbit Delete User Activities Activity Log .json
  description: Delete user's activity log entry with the given id.
  version: 1.0.0
host: api.fitbit.com
basePath: /1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /activities/{id}.json:
    get:
      summary: Get Activities .json
      description: Get the details of a specific activity in Fitbit activities database
        in the format requested. If activity has levels, also get list of activity
        level details.
      operationId: getActivities.json
      x-api-path-slug: activitiesid-json-get
      responses:
        200:
          description: OK
      tags:
      - Activities
      - Id.json
  /activities.json:
    get:
      summary: Get Activities.json
      description: Get a tree of all valid Fitbit public activities from the activities
        catalog as well as private custom activities the user created in the format
        requested. If activity has levels, also get a list of activity level details.
      operationId: getActivities.json
      x-api-path-slug: activities-json-get
      responses:
        200:
          description: OK
      tags:
      - Activities.json
  /user/-/activities/goals/weekly.json:
    get:
      summary: Get User Activities Goals Weekly.json
      description: Get a user's current weekly activity goals in the format requested
        using units in the unit system which corresponds to the Accept-Language header
        provided.
      operationId: getUserActivitiesGoalsWeekly.json
      x-api-path-slug: useractivitiesgoalsweekly-json-get
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Activities
      - Goals
      - Weekly.json
  /user/-/activities/goals/daily.json:
    get:
      summary: Get User Activities Goals Daily.json
      description: Get a user's current daily activity goals in the format requested
        using units in the unit system which corresponds to the Accept-Language header
        provided.
      operationId: getUserActivitiesGoalsDaily.json
      x-api-path-slug: useractivitiesgoalsdaily-json-get
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Activities
      - Goals
      - Daily.json
  /user/-/activities/log/favorite/{id}.json:
    delete:
      summary: Delete User Activities Log Favorite .json
      description: Delete the activity with the given id from user's list of favorite
        activities.
      operationId: deleteUserActivitiesLogFavorite.json
      x-api-path-slug: useractivitieslogfavoriteid-json-delete
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Activities
      - Log
      - Favorite
      - Id.json
    post:
      summary: Post User Activities Log Favorite .json
      description: Adds the activity with the given id to user's list of favorite
        activities.
      operationId: postUserActivitiesLogFavorite.json
      x-api-path-slug: useractivitieslogfavoriteid-json-post
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Activities
      - Log
      - Favorite
      - Id.json
  /user/-/activities/favorite.json:
    get:
      summary: Get User Activities Favorite.json
      description: Get a list of a user's favorite activities in the format requested.
        A user marks an activity as favorite on the user's Activities Tab. The activity
        ids in the list can be used to create a new activity log entry via the Log
        Activity.
      operationId: getUserActivitiesFavorite.json
      x-api-path-slug: useractivitiesfavorite-json-get
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Activities
      - Favorite.json
  /user/-/activities/frequent.json:
    get:
      summary: Get User Activities Frequent.json
      description: Get a list of a user's frequent activities in the format requested
        using units in the unit system which corresponds to the Accept-Language header
        provided. A frequent activity record contains the distance and duration values
        recorded the last time the activity was logged. The record retrieved can therefore
        be used to log the activity via the Log Activity with the same or adjusted
        values for distance and duration.
      operationId: getUserActivitiesFrequent.json
      x-api-path-slug: useractivitiesfrequent-json-get
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Activities
      - Frequent.json
  /user/-/activities/recent.json:
    get:
      summary: Get User Activities Recent.json
      description: Get a list of a user's recent activities in the format requested
        using units in the unit system which corresponds to the Accept-Language header
        provided. A recent activity record contains the distance and duration values
        recorded the last time the activity was logged. The record retrieved can therefore
        be used to log the activity via the Log Activity with the same or adjusted
        values for distance and duration.
      operationId: getUserActivitiesRecent.json
      x-api-path-slug: useractivitiesrecent-json-get
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Activities
      - Recent.json
  /user/{user-id}/activities/calories/date/{start-date-or-end-date}/{end-date-or-period}.json:
    get:
      summary: Get User User Activities Calories Date Start Date Or End Date End Date
        Or Period .json
      description: Get time series in the specified range for a given resource in
        the format requested using units in the unit system which corresponds to the
        Accept-Language header provided.
      operationId: getUserUserActivitiesCaloriesDateStartDateOrEndDateEndDateOrPeriod.json
      x-api-path-slug: useruseridactivitiescaloriesdatestartdateorenddateenddateorperiod-json-get
      responses:
        200:
          description: OK
      tags:
      - User
      - User-id
      - Activities
      - Calories
      - Date
      - Start-date-or-end-date
      - End-date-or-period.json
  /user/-/activities/{activity-log-id}.json:
    delete:
      summary: Delete User Activities Activity Log .json
      description: Delete user's activity log entry with the given id.
      operationId: deleteUserActivitiesActivityLog.json
      x-api-path-slug: useractivitiesactivitylogid-json-delete
      responses:
        200:
          description: OK
      tags:
      - User
      - '-'
      - Activities
      - Activity-log-id.json
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