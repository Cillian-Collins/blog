---
layout: post
title: Exploiting POST-Based CSRF
---

This article will explore the possibilities of exploiting POST-Based CSRF, such as commonly vulnerable endpoints, simple solutions and severity of such findings.

## What Is POST-Based CSRF?

POST-Based CSRF, as opposed to GET-Based CSRF, is a type of CSRF which affects POST requests. These, unlike GET requests, contain a body which means they cannot be exploited simply using an image. Instead, one must create a specially crafted page in order to execute the CSRF. This is where a lot of newer hackers fail, as they are not aware that this is possible, so it's something that's very important to be familiar with!
