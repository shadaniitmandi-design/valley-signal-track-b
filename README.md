Valley Signal
Track B — Mapping Flood Damage from Space
Valley Signal is a preliminary flood-mapping desk for screening satellite change, mapped assets, and road access. The app pairs Sentinel-1 RTC scenes from a matching orbit, uses Sentinel-2 as an optional corroboration layer, and retrieves a pre-event OpenStreetMap snapshot through ohsome. A fact-bounded situation report is available in English and Nepali.
Source package
The complete Flask application and submission materials are in valley-signal-track-b.zip. Extract the archive and follow track-b-flood-response/README.md to run locally. The root render.yaml extracts the archive during a Render Blueprint deployment.
Method and limits
Flood extents are thresholded radar-change candidates on a 20 m analysis grid, not confirmed flood or damage labels. Asset intersections are exposure estimates. Road connectivity is a graph screen based on mapped OSM roads; all outputs require field verification and are not for operational rescue or evacuation. Read the included report for the full method, evaluation plan, and limits.
Data attribution
Contains modified Copernicus Sentinel data 2026.
Produced using Copernicus WorldDEM-30 © DLR e.V. 2010–2014 and © Airbus Defence and Space GmbH 2014–2018 provided under COPERNICUS by the European Union and ESA; all rights reserved.
© OpenStreetMap contributors.
The EMSR927 reference is for validation only and is not an analysis input.
