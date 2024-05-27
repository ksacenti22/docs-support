---
summary: This article explains the cause, impact, and recommended action for an unimplemented error that occurs while connecting to the destination server.
tags:
guid: 1b01900c-30d3-49fc-a562-3c6a51982738
locale: en-us
app_type: traditional web apps, mobile apps, reactive web apps
figma: 
platform-version: o11
---

# OS-DP-STREAM-00012

## Error message

`There was an 'unimplemented' response from your destination server.`

## Cause

The error occurs when testing the connection after [Configuring the log streaming service in LifeTime](https://www.outsystems.com/tk/redirect?g=172ac547-add4-4cc5-9adf-d72fbe379d35) or when checking Log Streaming health and the destination server has responded with gRPC 12 (Unimplemented) error.

## Impact

Unable to establish a connection with the destination server. Therefore, logs aren't streamed to the destination.

## Recommended action

In LifeTime Log Streaming, review the destination server configuration. Check if the APM tool works correctly and re-establish the connection. If the problem persists, contact OutSystems Support.