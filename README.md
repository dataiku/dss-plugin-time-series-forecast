# Time Series Forecast Plugin (Legacy)

![GitHub release (latest by date)](https://img.shields.io/github/v/release/dataiku/dss-plugin-time-series-forecast) ![Build status](https://img.shields.io/badge/build-passing-brightgreen) ![Support level](https://img.shields.io/badge/support-Unsupported-orange)

This Dataiku DSS plugin provides recipes to work on yearly to hourly time series data to solve forecasting problems using R models.

⚠️ Starting with version 0.5, this plugin will be considered as "legacy". We will maintain it only to fix bugs. For the latest features and models, we recommend using the [new Forecast plugin](https://www.dataiku.com/product/plugins/timeseries-forecast/).**

Documentation: https://www.dataiku.com/product/plugins/time-series-forecast-legacy/

## Changelog

**Version 0.5.0 (2021-01)**

- Improve error messages
- Harmonize UX with the new Forecast plugin
- Mark as Legacy

**Version 0.4.1 (2020-02)**

- Small bug fixes for edge cases

**Version 0.4.0 (2019-12)**

- **Kubernetes** and external filesystem support for model storage
- Keep external regressors in the output dataset of the "Forecast" recipe
- Add option for filling with previous value in the "Clean" recipe
- Minor bug fixes and UX enhancements

**Version 0.3.1 (2019-10)**

- Various bug fixes, in particular for Expert mode

**Version 0.3.0 (2019-05)**

- Remove dependency on rstan and prophet packages (thus removing Prophet model support)

**Version 0.2.0 (2019-03)**

- Added support of external features/regressors for Neural Network, Prophet and ARIMA models (requires availability of future values of regressors when forecasting).

**Version 0.1.0 (2019-01)**

- Initial release
- First pipeline for univariate forecasting of hourly to yearly time series


## License

The Forecast plugin is:

Copyright (c) 2021 Dataiku SAS
Licensed under the [MIT License](LICENSE.md).
