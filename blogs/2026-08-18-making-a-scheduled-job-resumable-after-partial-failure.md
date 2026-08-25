---
title: "Making a scheduled job resumable after partial failure"
url: "https://codehooks.io/blog/resumable-cron-jobs"
date: "2026-08-18"
author: "jones@codehooks.io (Jones)"
feed_url: "https://codehooks.io/blog/rss.xml"
---
A nightly job that dies at 80% should not start again from zero. How to make scheduled work resumable with a cursor, per-record idempotency, and a queue, and when to reach for the Workflow API instead.
