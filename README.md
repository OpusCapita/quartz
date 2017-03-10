
It is OpusCapita fork of  https://github.com/quartz-scheduler/quartz
to fix https://github.com/quartz-scheduler/quartz/issues/93 in quartz-2.2.1

## Changes

- changed version to not conflict with official quartz
- changed build config to make maven install/deploy possible in OpusCapita env
- disabled `Update Check` (made `org.terracotta.quartz.skipUpdateCheck=true` by default)
- cherry pick fix for https://github.com/quartz-scheduler/quartz/issues/93