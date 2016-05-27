# Strava Scripts

These are a collection of scripts I've written to ease manipulating and querying Strava data.

Scripts:

- `dup_and_delete -a <activity_id> -d <distance> [-v]` - Used to duplicate an activity, replacing just the distance with that specified in the `<distance>` argument, and then removing the original activity.  This is useful for situations where the activity you have has wrong GPS or distance data, which Strava currently (May '16) doesn't allow you to change.  This has the caveat that you lose _all_ of the GPS data.
