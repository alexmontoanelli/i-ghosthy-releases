# IGhosthy releases

Public installer releases for the **IGhosthy** SimHub plugin (the source repo is private).

IGhosthy records your iRacing laps and overlays a cloud "ghost" of a chosen lap so you
can compare throttle, brake, speed and line in real time.

## Install

Grab the assets from the [**latest release**](../../releases/latest):

### 1. Plugin

1. Download **`IGhosthy-Setup.exe`**.
2. Run it. The installer auto-detects your SimHub folder and drops the plugin in
   (close SimHub first if it's open).
3. Start SimHub → open the **IGhosthy** plugin page → **Sign in with Google**.

### 2. Dashboard (optional)

The companion SimHub dashboard shows the live-vs-ghost speed delta and throttle trace.

1. Download **`iGhosthy.simhubdash`** (or click **Download dashboard** on the plugin's
   Overlay tab, which opens this releases page).
2. In SimHub: **Dashboards → Import** → pick the `iGhosthy.simhubdash` file.
3. Add the dashboard to a screen / device. It only animates once a ghost is loaded and
   you're on track.

## Updates

The plugin checks this repo for new releases on startup and offers an in-app update,
so you normally only install the `.exe` manually once.
