## OpenStreeMap- Geo2Tz - TimeZoneDB

The webpage is an openstreemap integration which returns the latitude,longitude of the marked place. This is given as an input to the Geo2Tz API request which returns the timezone. This timezone is given to the timezonedb API which returns the local time of that place.

Geo2Tz (https://github.com/noandrea/geo2tz) is locally hosted. The IP address is returned by the function getGeo2TzHostIP() defined inside the env.js. Also the API key for the TimezoneDB is returned by the function getTimezoneDBAPIKey() defined inside the same file.

