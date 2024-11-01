---
title: Log To Console Provider
layout: home
parent: Email Providers
nav_order: 200
---

The Log To Console email provider is included in the project to make it easier to develop and test the solution. Instead of attempting to send emails, they are simply logged to the console for review.

## Configuration

To use the Log To Console provider you will need to [configure `appsettings.json`](../application-configuration) or your deployment host with:

- `EmailProvider` set to `LogToConsole`.