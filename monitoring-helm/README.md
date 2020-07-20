# Install umbrella chart
1. `kubectl create namespace telemetry`
2. `helm -n telemetry install telemetry .`
3. `sudo kubefwd svc -n telemetry`