---
swagger: "2.0"
x-collection-name: IBM Watson
x-complete: 0
info:
  title: IBM Watson Machine Learning Get Wml Instances Instance Published Models
  description: Get wml instances instance published models.
  version: 1.0.0
basePath: v3/
schemes:
- http
produces:
- application/json
consumes:
- application/json
host: ibm-watson-ml.mybluemix.net
paths:
  /wml_instances/{instance_id}/published_models:
    get:
      summary: Get Wml Instances Instance Published Models
      description: Get wml instances instance published models.
      operationId: listModelDeployments
      x-api-path-slug: wml-instancesinstance-idpublished-models-get
      parameters:
      - in: query
        name: limit
        description: Maximum number of resources to retrive (defaults to 1000)
      - in: query
        name: start
        description: Token required for token-based pagination
      responses:
        200:
          description: OK
      tags:
      - Machine Learning
      - Wml
      - Instances
      - Instance
      - Id
      - Published
      - Models
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