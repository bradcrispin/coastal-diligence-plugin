---
name: coastal-diligence
description: Operating rules for Coastal Diligence work — property due-diligence (DD) reports, permit briefings, parcel and zoning research, permit history, code research in Carmel-by-the-Sea, City of Monterey, Monterey County (Pebble Beach, Big Sur, Carmel Valley), California state law, and Boulder, CO. Load before any research, drafting, rendering, or review of that kind.
---

All the method lives on the Coastal Diligence server, not in this plugin.

1. Call the server's `guide` tool with no arguments (it returns the operating
   rules) and read the result in full before doing anything else. Follow it for
   the rest of the session.
2. The operating rules name a playbook for each kind of deliverable. Read that
   playbook with `guide` in full before starting, and read each handbook it
   points to before the phase that needs it.
3. Work in a local folder the user chooses. It holds the copy of record of
   every deliverable; the server holds only working copies.

If the server's tools are missing or return "unauthorized", the plugin is not
connected: tell the user to open the plugin's settings and check the server
address and access token. Do not attempt the work without the server.
