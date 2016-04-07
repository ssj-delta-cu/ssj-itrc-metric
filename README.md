# ssj-itrc-metric
ITRC semi-automated METRIC based ET calculation

Lead: CalPoly, Dan Howes)

Modifies METRIC by using a semi-automated internal calibration and
replacing the alfafa reference ET with grass reference ET.

## [Results](./results)

This method will provide estimates of ET, G, and H based on Landsat
data, at approximately 28 day increments.  Monthly results will be
created byapplying ETo data for the interperiods.


Data | Date | Daily | Monthly
---  | --- | --- | ---
ET   | [l] | [d] | [m]
H    | [l] | [d] | [m]
G    | [l] | [d] | [m]
Ts   | [l] | [d] | [m]

The following table describes some of the required data from the other sources.

Data | Date | Daily | Monthly
--------- | --- | --- | ---
ETo       | [W] | [W] | [W]
Z         | [O] | [O] | [O]
LandCover | [N] | [N] | [N]



[O]: https://github.com/ssj-delta-cu/ssj-overview
[W]: https://github.com/ssj-delta-cu/ssj-weather/cimis
[N]: https://github.com/ssj-delta-cu/ssj-nasa-landcover
[l]: ./results/dates
[d]: ./results/daily
[m]: ./results/monthly