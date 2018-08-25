---
swagger: "2.0"
x-collection-name: Strava
x-complete: 1
info:
  title: Strava API v3
  description: strava-api
  version: 1.0.0
host: www.strava.com
basePath: /api/v3
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /athlete/activities:
    get:
      summary: List Athlete Activities
      description: Returns the activities of an athlete for a specific identifier.
      operationId: getLoggedInAthleteActivities
      x-api-path-slug: athleteactivities-get
      parameters:
      - in: query
        name: after
        description: An epoch timestamp to use for filtering activities that have
          taken place after a certain time
      - in: query
        name: before
        description: An epoch timestamp to use for filtering activities that have
          taken place before a certain time
      - in: query
        name: No Name
      responses:
        200:
          description: Successful response
      tags:
      - Sports
      - List
      - Athlete
      - Activities
  /clubs/{id}/activities:
    get:
      summary: List Club Activities
      description: Retrieve recent activities from members of a specific club. The
        authenticated athlete must belong to the requested club in order to hit this
        endpoint. Pagination is supported. Enhanced Privacy Mode is respected for
        all activities.
      operationId: getClubActivitiesById
      x-api-path-slug: clubsidactivities-get
      parameters:
      - in: path
        name: id
        description: The identifier of the club
      - in: query
        name: No Name
      responses:
        200:
          description: Successful response
      tags:
      - Sports
      - List
      - Club
      - Activities
---