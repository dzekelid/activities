swagger: "2.0"
x-collection-name: Pivotal Tracker
x-complete: 1
info:
  title: Pivotal Tracker
  description: access-and-manipulate-agile-project-management-data-including-projects-stories-and-tasks-
  version: 1.0.0
host: www.pivotaltracker.com
basePath: /services/v3/
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /activities:
    get:
      summary: Get Activities
      description: Retrieves the recent activity of all your projects.
      operationId: getActivities
      x-api-path-slug: activities-get
      parameters:
      - in: query
        name: limit
        description: Limits the number of activity feed items
      - in: query
        name: newer_than_version
        description: Restricts the activity feed to only those items that have a greater
          than supplied version
      - in: query
        name: occurred_since_date
        description: 'Restricts the activity feed to only those items that occurred
          after a supplied date (example format: 2009/12/18 21:00:00 UTC)'
      responses:
        200:
          description: OK
      tags:
      - Activities
  /projects/{PROJECT_ID}/activities:
    get:
      summary: Get Projects Project Activities
      description: Retrieves the recent activity of a specific project.
      operationId: getProjectsProjectActivities
      x-api-path-slug: projectsproject-idactivities-get
      parameters:
      - in: query
        name: limit
        description: Limits the number of activity feed items
      - in: query
        name: occurred_since_date
        description: 'Restricts the activity feed to only those items that occurred
          after a supplied date (example format: 2009/12/18 21:00:00 UTC)'
      - in: path
        name: PROJECT_ID
        description: The ID of the project to retrieve the activity for
      responses:
        200:
          description: OK
      tags:
      - Projects
      - PROJECT
      - ID
      - Activities