# Bard College Operational Status

Out-of-band status dashboard for Bard College Information Technology and Physical Plant infrastructure, hosted at **[bard-ops.github.io](https://bard-ops.github.io)**[cite: 4].

## Overview

This site provides real-time operational visibility into core campus systems, active service disruptions, scheduled maintenance windows, and historical incident records[cite: 4]. It is hosted independently of on-campus infrastructure so status updates remain accessible even during localized network or power outages.

### Monitored Categories

* **Information Technology:** Systems, Network, Security, Applications, Other
* **Physical Plant:** Power, Water, Weather, Other

## Architecture

* **Self-Contained Frontend (`index.html`):** Zero external CSS, font, or JavaScript CDN dependencies—everything required to render the dashboard lives in a single static HTML file[cite: 4].
* **Static Data Feed (`data.json`):** Updated automatically via an automated sync pipeline whenever incidents or maintenance notices are published, updated, or resolved[cite: 4].