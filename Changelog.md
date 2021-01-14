# Changelog

## [Unreleased]
- fix rare crash - sometimes, rarely, there is no focused workspace according to sway (eg. wake from sleep or other such situations) - handle gracefully
- set default opacity to 1.0 which also means persway won't tell sway to make any opacity changes (see: [#5](../../issues/5))
- workspace renaming: reset workspace name to number when all windows are closed (see: [#4](../../issues/4))
- start keeping a Changelog