---
schema: default
title: Lufthansa Flights from FRA to TXL
organization: Lufthansa Datasets
notes: 'Provides number of flights per day from Frankfurt to Berlin Tegel. Response format: A json file consisting of multiple list items with following columns: ["time", "Total number of planned flights", "No. of cancelled flights", "route"]. You can access all values by applying response["results"][0]["series"][0]["values"]'
resources:
  - name: 'https://ipuzs6skt6.execute-api.eu-central-1.amazonaws.com/query/lufthansa_flights'
    url: 'https://ipuzs6skt6.execute-api.eu-central-1.amazonaws.com/query/lufthansa_flights'
    format: json
license: -/-
category:
  - Transportation
maintainer: Florian
maintainer_email: floriancph@siesiehtalles.de
---
