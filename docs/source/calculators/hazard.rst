##################
Hazard Calculators
##################

*******
General
*******
.. automodule:: oqengine.calculators.hazard.general

*************************
Classical PSHA Calculator
*************************
.. automodule:: oqengine.calculators.hazard.classical.__init__

Classical PSHA Core
===================
.. automodule:: oqengine.calculators.hazard.classical.core

Classical PSHA Post-Processing
==============================
.. automodule:: oqengine.calculators.hazard.classical.post_processing
.. autofunction:: oqengine.calculators.hazard.classical.post_processing.hazard_curves_to_hazard_map_task
.. autofunction:: oqengine.calculators.hazard.classical.post_processing.do_post_process

***************************
Event-Based PSHA Calculator
***************************
.. automodule:: oqengine.calculators.hazard.event_based.__init__

Event-Based Core
================
.. automodule:: oqengine.calculators.hazard.event_based.core_next

Event-Based Post-Proccessing
============================
.. automodule:: oqengine.calculators.hazard.event_based.post_processing

*******************
Scenario Calculator
*******************

The Scenario Siesmic Hazard Analysis (SSHA) approach allows calculation of
ground motion ﬁelds from a single earthquake rupture scenario taking
into account ground-motion aleatory variability.

*************************
Disaggregation Calculator
*************************

The Disaggregation approach allows calculating relative contribution to a seismic hazard level.
Contributions are defined in terms of latitude, longitude, magnitude, distance,
epsilon, and tectonic region type.

Sources:

* | Disaggregation of Seismic Hazard
  | by Paolo Bazzurro and C. Allin Cornell
  | Bulletin of the Seismological Society of America, 89, 2, pp. 501-520, April 1999
