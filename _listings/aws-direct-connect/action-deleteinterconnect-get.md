---
swagger: "2.0"
info:
  title: AWS Direct Connect API
  version: 1.0.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=DeleteInterconnect&k=1:
    get:
      summary: ' Delete Interconnect '
      description: Deletes the specified interconnect
      operationId: deleteInterconnect
      parameters:
      - in: query
        name: interconnectId
        description: The ID of the interconnect
        type: string
      responses:
        200:
          description: OK
      tags:
      - interconnects
definitions: []
x-collection-name: AWS Direct Connect
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