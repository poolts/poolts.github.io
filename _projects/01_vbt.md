---
layout: single
title: "Virtual Bird Table"
permalink: /projects/vbt/
header:
  teaser: /assets/images/projects/vbt.png
excerpt: "A real-time virtual bird table used for intelligence briefing and planning."
order: 1
---

<iframe src="https://player.vimeo.com/video/1078775185?h=478151ecdc&title=0&byline=0&portrait=0&badge=0&autoplay=1&muted=1&controls=0&loop=1"  
        width="640"  
        height="360"  
        frameborder="0"  
        allow="autoplay; fullscreen; picture-in-picture"  
        allowfullscreen>
</iframe>

## Project Overview
The **Virtual Bird Table** is a military briefing and planning tool that lets distributed teams visualise and manipulate units on a shared map in real time. Built for austere networks, it replaces manual, printed tables with a collaborative XR/VR experience, so commanders and staff can plan from anywhere in the world without the need to be co-located.

## Tech Stack
- **Clients:** Unity (XR, VR, Windows Standalone) 
- **Server:** .NET, Docker
- **SDKs & Integrations:** [ArcGIS Maps SDK for Unity](https://developers.arcgis.com/unity/), [MilSymbol Server](https://github.com/spatialillusions/milsymbol-server)

## Key Features
- **Distributed Command**  
  Real-time, multi-user briefing & planning from anywhere in the world. Eliminates the need to co-locate.
- **Real-time Accurate Avatars**  
  See teammates’ head abd hand movements in real-time high fidelity.
- **Interactive Map**  
  Pan, zoom, and scale a shared map with 2D or 3D terrain and buildings.  
- **Unit Symbology & Manipulation**  
  Drag-and-drop NATO-standard units to simulate complex miltary scenarios.
- **Live Annotations & Layers**  
  Annotate the map using free-hand drawing and resizable shapes. Toggle grouped elements on the map (e.g. units, drawings, shapes) to avoid visual clutter.  
- **State Persistence**  
  Save/load map states (position, scale, units) to switch between scenarios instantly.  
- **Austere-Network Optimization**  
  Custom serialisation and compression to minimize bandwidth usage over low-rate links.

<!---
## Technical Deep Dive
> _TBC—please add any architecture diagrams, key algorithms (e.g. map tiling, state sync), data formats, or performance-tuning tricks you’d like highlighted._

## Lessons Learned & Next Steps
- **Challenges Overcome:** _TBC (e.g. balancing network load vs. update fidelity; XR UX hurdles; map rendering pipelines)_  
- **Future Enhancements:** _TBC (e.g. AI-assisted planning, offline mode, mobile support)_
--->

## Connect
- 🌐 [HawkWRX Website](https://www.hawkwrx.com/)  
- 🔗 [HawkWRX on LinkedIn](https://www.linkedin.com/company/hawkwrx/)