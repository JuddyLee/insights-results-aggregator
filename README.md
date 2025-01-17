# Insights Results Aggregator

[![GoDoc](https://godoc.org/github.com/RedHatInsights/insights-results-aggregator?status.svg)](https://godoc.org/github.com/RedHatInsights/insights-results-aggregator)
[![GitHub Pages](https://img.shields.io/badge/%20-GitHub%20Pages-informational)](https://redhatinsights.github.io/insights-results-aggregator/)
[![Go Report Card](https://goreportcard.com/badge/github.com/RedHatInsights/insights-results-aggregator)](https://goreportcard.com/report/github.com/RedHatInsights/insights-results-aggregator)
[![Build Status](https://ci.ext.devshift.net/buildStatus/icon?job=RedHatInsights-insights-results-aggregator-gh-build-master)](https://ci.ext.devshift.net/job/RedHatInsights-insights-results-aggregator-gh-build-master/)
[![Build Status](https://travis-ci.org/RedHatInsights/insights-results-aggregator.svg?branch=master)](https://travis-ci.org/RedHatInsights/insights-results-aggregator)
[![codecov](https://codecov.io/gh/RedHatInsights/insights-results-aggregator/branch/master/graph/badge.svg)](https://codecov.io/gh/RedHatInsights/insights-results-aggregator)
![GitHub go.mod Go version](https://img.shields.io/github/go-mod/go-version/RedHatInsights/insights-results-aggregator)
[![License](https://img.shields.io/badge/license-Apache-blue)](https://github.com/RedHatInsights/insights-results-aggregator/blob/master/LICENSE)

Aggregator service for insights results

<!-- vim-markdown-toc GFM -->

* [Description](#description)
* [Documentation](#documentation)
* [Package manifest](#package-manifest)

<!-- vim-markdown-toc -->

## Description

Insights Results Aggregator is a service that provides Insight OCP data
(officially called *recommendations*) that are being consumed by OpenShift
Cluster Manager (OCM), Advanced Cluster Manager (ACM), and OCP WebConsole via
Insights Operator. That data contain information about clusters status
(especially health, security, performance, etc.) and recommendations based on
results generated by Insights rules engine. Insights OCP data are consumed from
selected broker, stored in a storage (that basically works as a cache) and
exposed via REST API endpoints.

## Documentation

Documentation is hosted on Github Pages <https://redhatinsights.github.io/insights-results-aggregator/>.
Sources are located in [docs](https://github.com/RedHatInsights/insights-results-aggregator/tree/master/docs).

## Package manifest

Package manifest is available at [docs/manifest.txt](docs/manifest.txt).
