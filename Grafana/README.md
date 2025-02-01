# Grafana Dashboard Configuration

This folder contains the Grafana dashboard configuration for monitoring the application's performance metrics.

## Metrics Included

1. **HTTP Request Latency**
   - **Description**: Time taken to process HTTP requests.
   - **Importance**: Indicates the responsiveness of the application.
   - **Source**: Four Golden Signals.

2. **Error Rate**
   - **Description**: Percentage of failed requests.
   - **Importance**: Helps identify issues in the application.
   - **Source**: RED Method.

3. **CPU Utilization**
   - **Description**: Percentage of CPU usage.
   - **Importance**: Indicates resource bottlenecks.
   - **Source**: USE Method.

4. **Memory Utilization**
   - **Description**: Percentage of memory usage.
   - **Importance**: Helps in identifying memory leaks or insufficient memory allocation.
   - **Source**: USE Method.

5. **Database Query Latency**
   - **Description**: Time taken to execute database queries.
   - **Importance**: Indicates database performance issues.
   - **Source**: Derived from test code (LoginServletTests).

6. **Number of Active Sessions**
   - **Description**: Number of active user sessions.
   - **Importance**: Indicates user load on the system.
   - **Source**: Derived from test code (login_user.feature).

7. **Page Load Time**
   - **Description**: Time taken to load web pages.
   - **Importance**: Affects user experience.
   - **Source**: Derived from test code (basic_test.py).

8. **Successful Login Rate**
   - **Description**: Percentage of successful login attempts.
   - **Importance**: Indicates authentication system reliability.
   - **Source**: Derived from test code (login_user.feature).

9. **Failed Login Attempts**
   - **Description**: Number of failed login attempts.
   - **Importance**: Helps in identifying potential security issues.
   - **Source**: Derived from test code (login_user.feature).

10. **Book Lending Success Rate**
    - **Description**: Percentage of successful book lending operations.
    - **Importance**: Indicates the reliability of the library system.
    - **Source**: Derived from test code (basic_test.py).

## How to Use

1. Import the `dashboard.json` file into your Grafana instance.
2. Update the data source placeholders with the actual Prometheus endpoint.
3. Start monitoring the metrics in real-time.