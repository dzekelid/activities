---
swagger: "2.0"
x-collection-name: Akamai
x-complete: 1
info:
  title: Akamai API
  description: the-akamai-api-for-managing-your-akamai-service
  version: 1.0.0
host: developer.akamai.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /etp-report/v1/configs/{configId}/dns-activities/time-series:
    get:
      summary: Report DNS Activity Time Series
      description: Report DNS Activity Time Series
      operationId: etpreportv1configsconfigiddnsactivitiestimeseriesstarttimesecendtimesecdimensionfilters
      x-api-path-slug: etpreportv1configsconfigiddnsactivitiestimeseries-get
      parameters:
      - in: query
        name: configId
        description: ETP Configuration identifier assigned to the customer
        type: string
      - in: query
        name: dimension
        description: Flag to group the data
        type: string
      - in: query
        name: endTimeSec
        description: Timestamp for the end of the data window, in UTC seconds format
        type: string
      - in: query
        name: filters
        description: filter parameters to filter the data
        type: string
      - in: query
        name: startTimeSec
        description: Timestamp for the start of the data window, in UTC seconds format
        type: string
      responses:
        200:
          description: OK
      tags:
      - Etp
      - Report
      - Configurationss
      - Configurations
      - DNS
      - Activities
      - Time
      - Series
      - Starttimesec
      - endtimesec
      - dimension
      - filters
  /etp-report/v1/configs/{configId}/dns-activities/aggregate:
    get:
      summary: Report DNS Activities Totals
      description: Report DNS Activities Totals
      operationId: etpreportv1configsconfigiddnsactivitiesaggregatestarttimesecendtimesecdimensionfilters
      x-api-path-slug: etpreportv1configsconfigiddnsactivitiesaggregate-get
      parameters:
      - in: query
        name: configId
        description: ETP Configuration identifier assigned to the customer
        type: string
      - in: query
        name: dimension
        description: Flag to group the data
        type: string
      - in: query
        name: endTimeSec
        description: Timestamp for the end of the data window, in UTC seconds format
        type: string
      - in: query
        name: filters
        description: filter parameters to filter the data
        type: string
      - in: query
        name: startTimeSec
        description: Timestamp for the start of the data window, in UTC seconds format
        type: string
      responses:
        200:
          description: OK
      tags:
      - Etp
      - Report
      - Configurationss
      - Configurations
      - DNS
      - Activities
      - Aggregation
      - Starttimesec
      - endtimesec
      - dimension
      - filters
      - Aggregation
---