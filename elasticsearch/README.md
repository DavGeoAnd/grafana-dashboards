# Elasticsearch

#### Using service audits from Elasticsearch to display detailed and overall request details

### Pictures

#### service_audit.png
Give requests amount over time grouped by domain (categories) and object types (subcategories)
- Template variables are used to filter by common fields
- Panels are used to make comparisons by common fields (successful vs error requests, source database, etc.)

#### service_audit_1.png
Mixture of panels that compare request counts for apps and give individual unsuccessful requests
- Using pie charts to compare request counts per app and how many messages the requested
- Tables that give the amount of requests by users and users that come from decommissioned teams
- Table that gives list of unsuccessful requests with details on the request

#### user_audit.png
Similar to service audit but filters it down to user
- Give user details at the top related to team associated and ips the requests are coming from
- Comparison for types of requests being made by user