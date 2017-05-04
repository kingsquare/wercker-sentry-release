sentry-release
==============

Send your release to Sentry.io


Example
--------

Add SENTRY_AUTH and SENTRY_ORG as deploy target or application environment variable.

```
    - rafaelverger/sentry-release:
        auth_token: $SENTRY_AUTH
        organization: $SENTRY_ORG
        version: **OPTIONAL** // default: '$WERCKER_GIT_COMMIT'
```
