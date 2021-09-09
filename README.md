# PPE-Use-Models


These models calculate daily PPE use for the designated healthcare facility given three types of inputs (described below). All excel files are example inputs with data from Massachusetts gathered during and after COVID-19.

Inputs:

stored_values: These values are initialized during the first data import and are updated during each day in the for loop. This includes COVID patients in inpatient, PUI in inpatient, etc.

static_values: These values are kept constant during the entire model and are not updated. This includes staff ratios, PPE reuse policy length, daily patient contacts, etc.

daily_inputs: These inputs include epidemiological information for each day of the model run. This includes case count, hospitalizations, etc.
