# Shanghai planner

**Open it: https://gewoonkees132.github.io/Shanghai-planner/**

The typing planner for Shanghai, 5–8 Nov 2026, as one page: the plan, places, the shops map with your GPS position (Places → Shops → the location button), phrases and info. Everything is in `index.html`; nothing else loads.

It is served over https so that Chrome on Android can give the map your location. The copy sent over WhatsApp opens as a local file, which Chrome never gives the location. What you type is kept in the browser, per copy: move it with Info → Notes.

Built from a private repository (`tools/build_planner.py`); this repository only holds the published page.
