# data

Place data file(s) in this folder. Add the dimensions (rows and columns).

Then, include codebooks (variables, and their descriptions) for your data file(s)
using the following format.

## name of data file

- `BEGIN_YEARMONTH`: Year and month when the event began (YYYYMM).
- `BEGIN_DAY`: Calendar day when the event began.
- `BEGIN_TIME`: Local starting time of the event (HHMM).
- `END_YEARMONTH`: Year and month when the event ended (YYYYMM).
- `END_DAY`: Calendar day when the event ended.
- `END_TIME`: Local ending time of the event (HHMM).
- `EPISODE_ID`: Unique identifier assigned by NWS to denote a storm episode.
- `EVENT_ID`: Identifier for each individual event within an episode.
- `STATE`: Name of the U.S. state where the event occurred.
- `YEAR`: Four-digit year of the event.
- `MONTH_NAME`: Name of the month when the event occurred.
- `EVENT_TYPE`: Type of event (e.g., Tornado, Flood, Hail).
- `WFO`: Weather Forecast Office responsible for the event record.
- `BEGIN_DATE_TIME`: Combined date and time stamp for event start.
- `CZ_TIMEZONE`: Time zone code of the event’s county/zone.
- `END_DATE_TIME`: Combined date and time stamp for event end.
- `INJURIES_DIRECT`: Number of people directly injured.
- `INJURIES_INDIRECT`: Number of people indirectly injured.
- `DEATHS_DIRECT`: Number of people directly killed.
- `DEATHS_INDIRECT`: Number of people indirectly killed.
- `DAMAGE_PROPERTY`: Estimated property damage (e.g., in USD).
- `DAMAGE_CROPS`: Estimated crop damage (e.g., in USD).
- `SOURCE`: Reporting source (e.g., Law Enforcement, Broadcast Media).
- `MAGNITUDE`: Intensity or magnitude value for the event (if applicable).
- `MAGNITUDE_TYPE`: Units or scale for the magnitude measurement.
- `FLOOD_CAUSE`: Primary cause of flooding events (if applicable).
- `CATEGORY`: Categorical level of the event type (if provided).
- `BEGIN_LAT`: Starting latitude coordinate of the event.
- `BEGIN_LON`: Starting longitude coordinate of the event.
- `END_LAT`: Ending latitude coordinate of the event.
- `END_LON`: Ending longitude coordinate of the event.
