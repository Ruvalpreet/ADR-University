# 2. React native UI

Date: 2024-02-20

## Status

Accepted

## Context

The stakeholders required an app that supports both iOS and Android platforms therefore, we need to decide on a framework that allows for efficient development and maintenance across multiple platforms. The app should support offline mode to enable users to access certain features and data even when offline. the app should have offline capabilities and data synchronization mechanisms.

## Decision

The react native UI will be used to build a UI for cross-platform, that will render the UI using the actual native views. Moreover, react native supports offline capabilities and manages offline data synchronization.

## Consequences

1.  The react native compiles the code into native components, that will render the UI as a native.
2.  React native allows efficient development and maintenance across multiple platforms.
3.  The user would be able to access some of the client-side features without internet connections.
4.  React uses redux for managing offline data synchronization.
