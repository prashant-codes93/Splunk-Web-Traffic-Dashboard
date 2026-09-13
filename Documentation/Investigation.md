# Web Traffic Investigation

## Investigation Flow

1. Web access logs are generated.
2. Logs are ingested into Splunk.
3. Data is stored in the web_traffic index.
4. Important fields are extracted:
   - src_ip
   - method
   - uri
   - http_version
   - status
   - bytes
5. SPL queries are used to analyze traffic.
6. Security detections identify suspicious activity.
7. Results are displayed in the Web Traffic Security Dashboard.

## Security Investigations

The project investigates:

- High-volume source IPs
- Excessive 404 requests
- Excessive 403 requests
- Suspicious URL access
- Unusual HTTP methods
- Possible scanning activity
- Server errors
- Suspicious source IP risk

## Important Note

The detection thresholds and risk score used in this project are designed for a controlled lab environment and demonstrate SOC investigation techniques. They should not be treated as production detection rules without tuning.
