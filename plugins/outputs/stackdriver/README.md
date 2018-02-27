# Stackdriver Output Plugin

This plugin writes to the [Google Cloud Stackdriver API](https://cloud.google.com/monitoring/api/v3/)
and requires [authentication](https://cloud.google.com/docs/authentication/getting-started) with Google Cloud using either a service account or user credentials.

Metrics are grouped by the `namespace` variable and metric key - eg: `custom.googleapis.com/telegraf/system/load5`