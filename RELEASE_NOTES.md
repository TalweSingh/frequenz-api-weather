# Frequenz Weather API Release Notes

## Summary

<!-- Here goes a general summary of what this release is about -->

## Upgrading

<!-- Here goes notes on how to upgrade from previous versions, including deprecations and what they should be replaced with -->

## New Features

* Added optional `forecast_horizon_min` and `forecast_horizon_max` parameter
  to `ReceiveLiveWeatherForecastRequest` that allows limiting the forecast
  horizon of returned forecasts. When not specified, forecasts with their
  minimum/maximum available horizon will be returned.

<!-- Here goes the main new features and examples or instructions on how to use them -->

## Bug Fixes

<!-- Here goes notable bug fixes that are worth a special mention or explanation -->
