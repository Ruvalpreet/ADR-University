# 6. Push Notification

Date: 2024-02-20

## Status

Accepted

## Context

The app should be able to inform users about the new announcements, assignment deadlines, and other relevant updates, the app should integrate with a push notification service. Therefore the app should be a push notifications service.

## Decision

We will be using the OneSignal service to allow pushing notifications on both iOS and Android devices.

## Consequences

1.  It supports cross-platform iOS and Android apps.
2.  It is easy to integrate into our app.
3.  Required minimal code changes in our app to implement it.
4.  It has a very high throughput, capable of handling many notifications.
5.  Built-in automation system, that allows to send notification based on the user's preferences.
