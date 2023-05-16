# AppDynamics

#### Using metrics from AppDynamics of java services and display them in Grafana

### Pictures

#### process_quick_view.png
Availability, cpu, and memory metrics used on home page to give a quick view for java services and servers
- First template variable to switch between environments (test and prod)
- Remaining template variables help user filter which application, tier, and nodes they would like to view
- First row of tables give the service availability, cpu, and memory for java services
- Second row of tables give the server availability, cpu, and memory for servers
- If service/server is down, will give "Not Running" value

#### process_info.png
Java service metrics that give an overall performance view. Metrics used that would be associated to alerts. Uses Grafana rows below to give more detailed metrics.
- Template variables are to choose which nodes they would like to use
- Graphs are to help compare metrics for nodes selected