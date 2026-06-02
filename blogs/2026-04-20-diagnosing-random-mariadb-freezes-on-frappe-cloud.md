---
title: Diagnosing Random MariaDB Freezes on Frappe Cloud
url: https://frappe.io/blog/frappe-cloud/diagnosing-random-mariadb-freezes-on-frappe-cloud
date: '2026-04-20'
author: ''
feed_url: https://frappe.io/rss.xml
---
We kept seeing random database freezes on Frappe Cloud and couldn’t trace them due to missing metrics. This post shows how a hidden I/O-heavy query caused it and how we fixed it.
