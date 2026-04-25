# TUX — Touch User Extensions for Sencha Touch 2

TUX is a bundle of professional **Touch User Extensions** built for **Sencha Touch 2.x** (circa 2012–2013).  
It collects a set of reusable UI components, layouts, and plugins that were designed to ship in real-world mobile HTML5 applications, with a focus on polish, performance, and “product-grade” interaction details.

This repository is the original workspace-style distribution, including **source**, **themes**, **generated docs**, and a set of **example apps** showcasing the components in action.

## What’s inside

TUX includes (among others):

- **Progress components**
  - Linear progress bar component and form field
  - Radial (“donut”) progress bar with customization/masking
  - Progress-enabled `MessageBox`
- **DataView components**
  - Editable lists (single and multi edit modes)
  - Photo gallery view
  - Audio track / playlist UI
- **Layouts & animations**
  - Orb layout (arrange items around a circle)
  - “Time Machine” style card transition effects
- **Plugins**
  - Touch timeout / taphold feedback plugin
  - Speech-to-text plugin (intended for native/Cordova environments)

## A bit of history (behind the scenes)

TUX was authored and maintained between 2012 and 2013 as a reusable component bundle for Sencha Touch 2, with the goal of packaging interaction-heavy UI building blocks (components, layouts, effects) together with documentation and runnable examples.

## Examples and documentation

- **Examples hub**: the `examples/` folder contains multiple small apps (progress bars, radial progress, gallery, editable list, gestures, layouts, time-machine, etc.).
- **API documentation**: pre-generated docs live in `docs/` (generated with JSDuck).

## Getting it running (high level)

This is a legacy Sencha Touch 2 workspace. To run the examples you typically need:

- **Sencha Touch 2.x** (download separately)
- **Sencha Cmd** (see `versions.md` for the versions used at the time)

The release notes mention that the framework folder was intentionally removed from the repo, so you’ll need to place Sencha Touch locally and generate/serve an app within the workspace to run examples.

## License

Dual-licensed:

- **GPL v3** (open source)
- **Commercial license** available for proprietary applications

See `license.txt` for details.

## Credits

Copyright (c) 2012–2013, **SIMACS di Andrea Cammarata**  
Authored by **Andrea Cammarata** (see `license.txt`).

