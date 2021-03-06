Release Notes
=============

This is the list of changes to Hydrostats between each release. For full details, see the commit logs at
https://github.com/BYU-Hydroinformatics/Hydrostats.

Version 0.78
^^^^^^^^^^^^
- Added the ability to use different thresholds for the ensemble forecast for the observed and ensemble forecast data in
  the hydrostats.ens_metrics.auroc() and hydrostats.ens_metrics.ens_brier() methods.
- Changes to documentation to reflect the addition of the .name and .abbr properties to metrics from the HydroErr
  package.

Version 0.77
^^^^^^^^^^^^
- Added a new rolling average feature to the hydrostats.data.daily_average(). Set rolling=True as a parameter to use the
  defaults, or specify arguments from the pandas.DataFrame.rolling() method for a custom rolling average.
- Minor changes and more coverage.

Version 0.76
^^^^^^^^^^^^
- Moved the documentation to new location at https://hydrostats.readthedocs.io/

Version 0.75
^^^^^^^^^^^^
- Minor bug fixes and changes

Version 0.74
^^^^^^^^^^^^

- Added support for parsing julian dates with the new hydrostats.data.julian_to_gregorian() function
- Added support for parsing files with julian dates in the hydrostats.data.merge_data() function.
- Added example code in the github repository, in the "Examples" directory.
