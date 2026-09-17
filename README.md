# 116 Garage

A mobile-first garage companion for the 1973 Mercedes-Benz 450SE (W116 / M117 4.5), focused on practical restoration and troubleshooting.

## Features

- Interactive distributor-cap firing-order reference
- Clean ignition-wire routing instructions by cylinder bank
- Guided diagnostic flows for low idle, shift stalling, no-start, and misfire
- Persistent service checklist
- Local repair notes
- Light/dark UI
- Installable web-app manifest

## Run

No build step or dependencies are required. Serve the repository with any static HTTP server, for example:

```bash
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## Important

The app intentionally avoids presenting unverified timing/dwell/fuel-pressure numbers as authoritative specifications. Confirm measurements and adjustment values against the correct Mercedes-Benz workshop documentation for the exact engine/distributor configuration before making adjustments.
