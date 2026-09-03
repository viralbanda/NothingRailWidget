# Nothing Rail
Nothing OS-inspired train-status home-screen widget.

Build without a PC: upload this folder to GitHub, open Actions, choose Build APK, Run workflow, then download the NothingRail-debug artifact.

The supplied AniCrad API currently exposes train info/route and station-live endpoints; its current route source does not expose train-running status. The app keeps the API base configurable so a live-status provider can be plugged in.
