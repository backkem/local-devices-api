# Local Devices API explainer

This is the repository for Local Devices API. You're welcome to
[contribute](CONTRIBUTING.md)!

## Authors:

- [backkem](https://github.com/backkem)

## Participate

- [Issue tracker](https://github.com/backkem/local-devices-api/issues)
- [Discussion forum](https://discourse.wicg.io/t/idea-local-devices-api-lan-services/5056)

## Table of Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Introduction

The Local Devices Protocol connects browsers to devices on the Local Area Network. Typically, these are devices such as NAS servers, Internet-connected TVs and IoT devices such as IP cameras, doorbells or thermostats.
This entire specification assumes operation in an air-gapped Local Area Network. There can be no reliance on cloud or other remote servers for core functionality. The browser and devices should communicate directly and only make use of readily available network protocols.
