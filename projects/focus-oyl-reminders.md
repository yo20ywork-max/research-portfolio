# Focus Oyl — Local Reminders & Care Companion

[Public source](https://github.com/yo20ywork-max/focus-oyl-reminders) · [Build and test evidence](https://github.com/yo20ywork-max/focus-oyl-reminders/blob/main/VALIDATION.md)

## Problem and approach

Important actions and deadlines can be scattered across text, screenshots, and device notifications. This application explores a local reminder workflow that extracts candidate actions, asks for review where confidence is low, and schedules reminders around deadlines and quiet hours.

## Implementation scope

The source combines a JavaScript interface, a rule-based extraction engine, a timing engine, local English and Traditional Chinese OCR through Tesseract.js, and Capacitor Android/iOS projects. Native source includes notification handling and optional care-related integrations. Earlier native reference files are kept distinct from the integrated platform projects.

The project demonstrates application integration, local data handling, platform permissions, mobile packaging, and regression checks. It does not claim original model training or evaluated emergency-response reliability.

## Evidence and limits

The public repository contains actual application code, native implementations, and the existing regression runner. Its validation record separates automated scheduling checks and build checks from physical-device behavior. Native background execution, OCR accuracy, SMS/location behavior, and store acceptance need their own evidence.

## Relationship and publication

This is the project formerly stored in the ultramax folder. It is separate from [FocusOYL — Local AI Translator & Agent](focusoyl.md). Its new public history starts with a reviewed source snapshot; private signing material, local configuration, and generated outputs are excluded. See the repository's publication notes for import changes.
