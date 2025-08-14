# Task 7: Monitor System Resources Using Netdata

Install and run Netdata via Docker, monitor system and application performance metrics, and capture screenshots of the dashboard, including at least one triggered alert.

## Tools Used

- **Netdata** (real-time monitoring tool)
- **Docker** (containerized environment)
- **stress** (to simulate system load and trigger alerts)

## Steps 

### 1. Installed and Ran Netdata using Docker

```bash
docker run -d --name=netdata -p 19999:19999 netdata/netdata
