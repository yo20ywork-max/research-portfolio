# Privacy Display — Android Privacy Overlay

[Public source](https://github.com/yo20ywork-max/privacy-display) · [Build and test evidence](https://github.com/yo20ywork-max/privacy-display/blob/main/VALIDATION.md)

## Problem and approach

This native Android application explores how users can reduce the visibility of selected on-screen content through software overlays, notification handling, and local image obfuscation.

## Implementation scope

The initial prototype implements permission flows, per-app selection, a foreground overlay service, a notification listener, local preferences, and a Quick Settings tile. The later iteration adds patterned overlays, image import/processing/export, and a Google Play Billing integration.

Both source directories are preserved in one repository to show the progression of the same application. The main implementation uses Java, Android services, AndroidX image support, Gradle, and Play Billing.

## Evidence and limits

The source, build configuration, English READMEs, and validation record are public. Original store images are promotional mockups, not measured privacy outcomes. The directory name PrivacyDisplayStoreReady describes release preparation; it does not prove store approval.

Software visual obfuscation cannot establish a hardware viewing-angle restriction. Coverage of system UI, behavior under device background limits, billing transactions, and actual privacy effectiveness require separate tests.

## Publication boundary

The public snapshot excludes the original upload signing key, populated signing properties, machine-specific configuration, and generated builds. Release drafts use placeholder contact details where needed. Third-party framework and library attribution remains applicable.
