# Location, Geofencing & Activity Recognition Lab

Educational reimplementation using Google Play services Location APIs.

- Reads the last known location.
- Creates/removes a 150 m geofence around that point.
- Receives ENTER/EXIT transitions through a `BroadcastReceiver`.
- Starts/stops Activity Recognition updates and reports the most probable activity.
- Requests foreground location and activity-recognition runtime permissions. On modern Android, reliable background geofence delivery additionally depends on the user's background-location setting and system power policy.

A Play-services-enabled physical device or emulator is required for the full demo.
