# argo-influx-prediction-Workflow

This argo workflow loads data from influxdb, makes timeseries predictions and loads the predictions back into influx

## prerequisites

- install argo into kubernetes cluster
- configure environment variables for the [darts-timeseries-forecaster](https://github.com/peterpeerdeman/darts-timeseries-forecaster) step

## commands

argo submit timeseries-prediction-parking.yaml -n argo
argo watch timeseries-prediction-parking-pgdnj -n argo

