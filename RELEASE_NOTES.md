# Frequenz Weather API Release Notes

## Summary

Moves the client to[frequenz-client-weather-python](https://github.com/frequenz-floss/frequenz-client-weather-python).

## Upgrading

The weather client and CLI tool are no longer included in this package. To
continue using them, migrate to frequenz-client-weather-python. Follow
the installation and usage instructions provided in the new repository.

- The parameters for the historical RCP changed from `start_ts` to `creation_start_ts` and from `end_ts` to `creation_end_ts`.

- The historical RPC replaced pagination with streaming.

- Added optional `forecast_horizon_min` and `forecast_horizon_max` parameter
  to `ReceiveHistoricalWeatherForecastRequest` that allows limiting the forecast
  horizon of returned forecasts.

## New Features

## Bug Fixes
