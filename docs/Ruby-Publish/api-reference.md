---
title: api-reference
date: 2026-04-21
tags: [API overview, Theme]
layout: post
---

This API allows users to customize their display theme based on their preference, with options for light, dark, or system mode.

For authentication, a bearer token is required.

The endpoint should follow this format: POST /api/v2/users/preferences

If it was successful the response should provide a "timestamp" and "status", if there is a problem it should provide a return error: "Invalid theme selected."
