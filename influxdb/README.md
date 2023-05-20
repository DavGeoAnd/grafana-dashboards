# InfluxDB

#### Store service metrics and custom events for performance comparison and detail

### Pictures

#### app_list.png
Gives the count overtime of messages published to clients
- Mix of spring boot app metrics and custom event when service starts
- List of all services for all environments and hosts
- Gives build and java version for comparison
- Gives last start time of service and how long service has been running
- If uptime metric is null, that means service isn't running but still have info of service if was running in the last 30 days
- By selecting the service name, it will give an option go to the overview or the detail dashboard

#### app_overview.png
Gives common metrics for spring boot services and is used for comparison
- Gives a quick overview of services that would be used for alerting
- By clicking on a value in a graph, it will open the detail dashboard for the selected service with matching time range

#### app_detail.png (and all starting with app_detail)
Gives all metrics for spring boot service for a detailed view
- Gives the same metrics from overview dashboard to start
- Breaks down through grafana rows for more detailed metrics