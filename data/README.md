# data

Place data file(s) in this folder. Add the dimensions (rows and columns).

Then, include codebooks (variables, and their descriptions) for your data file(s)
using the following format.

## name of data file

- `late_date_modified`: The last date of modification by NWS
- `last_date_certified`: The last date of certification by NWS
- `episode_id`: ID assigned by NWS to denote the storm episode
- `event_id`: ID assigned by NWS to note a single, small part that goes into a specific storm episode
- `state`: The state name where the event occurred
- `state_fips`: A unique number (State Federal Information Processing Standard) is assigned to the county by the National Institute for Standards and Technology (NIST)
- `year`: Four digit year for the event in this record
- `month_name`: Name of the month for the event in this record
- `event_type`: The type of weather event 
- `cz_type `: Indicates whether the event happened in a (C) county/parish, (Z) zone or (M) marine
- `cz_fips`: The county FIPS number
- `cz_name`: County/Parish, Zone or Marine Name

