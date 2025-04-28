# Frequenz Weather API Release Notes

## Summary

Moves the client to[frequenz-client-weather-python](https://github.com/frequenz-floss/frequenz-client-weather-python).

## Upgrading

The weather client and CLI tool are no longer included in this package. To
continue using them, migrate to frequenz-client-weather-python. Follow
the installation and usage instructions provided in the new repository.

- The parameters for the historical RPC changed from `creation_start_ts` to `start_create_time`
  and from `creation_end_ts` to `end_create_time`.

- Renamed `valid_at_ts` field to `valid_time`.

- Renamed `creation_ts` field to `create_time`.

- The historical RPC replaced pagination with streaming.

- Added optional `ForecastHorizon`parameter to `StreamHistoricalWeatherForecastRequest`
  that allows limiting the forecast horizon of returned forecasts.

- Instead of `forecast_horizon_min` and `forecast_horizon_max` parameter in
  `StreamLiveWeatherForecastRequest` a new message `ForecastHorizon` is introduced.

- The package name changed from `frequenz.api.weatherforecast.v1` to
  `frequenz.api.weather.v1`.

## New Features

## Bug Fixes
