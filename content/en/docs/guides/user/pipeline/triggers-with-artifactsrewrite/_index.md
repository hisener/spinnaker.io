---
title: "Overview"
linkTitle: "Overview"
weight: 
description: >
  A pipeline trigger defines when to automatically run a pipeline. There are many types of triggers available: Jenkins jobs, webhooks, CRON jobs, even other pipelines. 
---

A pipeline trigger defines when to automatically run a pipeline. There are many
types of triggers available: Jenkins jobs, webhooks, CRON jobs, even other
pipelines. Adding a trigger to your pipeline means that the pipeline runs each
time the triggering event occurs.

Note that whether or not you have set up a pipeline trigger, you can always
[run your pipeline manually](/docs/v1/guides/user/pipeline/managing-pipelines#manually-run-a-pipeline).

For more information about how to configure
specific types of triggers, see the rest of the pipeline triggers
documentation:

<!-- TODO:add other links as they're added. -->
* [Triggering on Jenkins job completion](/docs/v1/guides/user/pipeline/triggers-with-artifactsrewrite/jenkins/)
* [Triggering on Pub/Sub messages](/docs/v1/guides/user/pipeline/triggers-with-artifactsrewrite/pubsub/)
* [Triggering on webhooks](/docs/v1/guides/user/pipeline/triggers-with-artifactsrewrite/webhooks/)
* [Triggering on receiving artifacts from GCS](/docs/v1/guides/user/pipeline/triggers-with-artifactsrewrite/gcs/)
* [Triggering on receiving artifacts from GitHub](/docs/v1/guides/user/pipeline/triggers-with-artifactsrewrite/github/)
* [Triggering on Artifactory artifact publishing](/docs/v1/guides/user/pipeline/triggers-with-artifactsrewrite/artifactory/)