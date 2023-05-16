# Splunk

#### Using service logs stored in Splunk and display details and aggregated data

### Pictures

#### publish_overview.png
Gives the count overtime of messages published to clients
- Template variables are used to filter by message types and select interval
- Graphs give publish amount overtime and how long it takes to do so 

#### publish_detail.png
Give a more detailed view of message type being published. Helps see if any latency issues in a particular step during publishing
- Graphs that give amount of messages published by type
- Following graphs give the time spent on each step to publish messages

#### publish_history.png
Gives logs for specified message id of when message is sent to service and then when it was published out
- Tables will give logs and general details of the message being published
- Tables on the right will populate if any errors occurred