# SBG-EllipseD-UAV-Logs
This project contains UAV flight data collected to support and validate the proposed pseudo-satellite ephemeris design algorithm for UAV navigation.
# UAV-PNS-Navigation2025-Data

This dataset contains flight data collected from a UAV platform equipped with an SBG Ellipse-D RTK/INS system. The data supports the validation of a pseudo-satellite ephemeris generation algorithm for UAV navigation.

## Data Format

Each row in the dataset represents a time-synchronized measurement at a given epoch. The columns are described as follows:

| Column | Name         | Unit             | Description                                      |
|--------|--------------|------------------|--------------------------------------------------|
| 1      | Timestamp    | Seconds          | Unix epoch time                                 |
| 2      | Easting      | Meters           | UTM Easting coordinate (likely Zone 50N)        |
| 3      | Northing     | Meters           | UTM Northing coordinate                         |
| 4      | Roll         | Degrees          | Euler angle - rotation around X axis            |
| 5      | Pitch        | Degrees          | Euler angle - rotation around Y axis            |
| 6      | Yaw          | Degrees          | Euler angle - rotation around Z axis            |
| 7      | Yaw Rate     | Radians/second   | Angular velocity around Z axis (Yaw rate)       |
| 8      | Year         | -                | GNSS date - year                                |
| 9      | Month        | -                | GNSS date - month                               |
| 10     | Day          | -                | GNSS date - day                                 |
| 11     | Hour         | -                | GNSS time - hour (UTC)                          |
| 12     | Minute       | -                | GNSS time - minute (UTC)                        |
| 13     | Second       | -                | GNSS time - second (UTC)                        |
| 14     | Millisecond  | ms               | Sub-second timestamp component                  |
| 15     | Latitude     | Degrees          | WGS84 geographic latitude                       |
| 16     | Longitude    | Degrees          | WGS84 geographic longitude                      |
| 17     | Altitude     | Meters           | Altitude above mean sea level                   |

This dataset is shared as part of the peer review process to support reproducibility of results presented in a submitted manuscript.  
Please do not cite this dataset until the paper is formally accepted and published.
