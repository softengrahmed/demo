# Monitoring Artifacts

## List of Performance Metrics

1. **Response Time**: Measures the time taken to respond to a request.
2. **Throughput**: Measures the number of requests processed in a given time period.
3. **Error Rate**: Measures the percentage of failed requests.
4. **CPU Utilization**: Measures the percentage of CPU used.
5. **Memory Utilization**: Measures the percentage of memory used.
6. **Disk I/O**: Measures the read/write operations on the disk.
7. **Network I/O**: Measures the data sent and received over the network.
8. **Database Query Performance**: Measures the time taken to execute database queries.
9. **Cache Hit/Miss Ratio**: Measures the effectiveness of caching.
10. **Garbage Collection Time**: Measures the time spent in garbage collection.

## Explanation of Metrics

1. **Response Time**:
   - **Measures**: Time taken to respond to a request.
   - **Importance**: Indicates the performance and user experience of the application.
   - **Usage**: Monitor to ensure that response times are within acceptable limits.
   - **Source**: Industry best practices (Four Golden Signals).

2. **Throughput**:
   - **Measures**: Number of requests processed in a given time period.
   - **Importance**: Indicates the capacity and scalability of the application.
   - **Usage**: Monitor to understand the load and performance under different conditions.
   - **Source**: Industry best practices (Four Golden Signals).

3. **Error Rate**:
   - **Measures**: Percentage of failed requests.
   - **Importance**: Indicates the reliability and stability of the application.
   - **Usage**: Monitor to detect and address issues causing failures.
   - **Source**: Industry best practices (Four Golden Signals, RED Method).

4. **CPU Utilization**:
   - **Measures**: Percentage of CPU used.
   - **Importance**: Indicates the processing capacity and potential bottlenecks.
   - **Usage**: Monitor to ensure efficient use of CPU resources and detect performance issues.
   - **Source**: Industry best practices (USE Method).

5. **Memory Utilization**:
   - **Measures**: Percentage of memory used.
   - **Importance**: Indicates the memory usage and potential memory leaks.
   - **Usage**: Monitor to ensure efficient use of memory resources and detect memory-related issues.
   - **Source**: Industry best practices (USE Method).

6. **Disk I/O**:
   - **Measures**: Read/write operations on the disk.
   - **Importance**: Indicates the performance of disk operations and potential bottlenecks.
   - **Usage**: Monitor to ensure efficient disk operations and detect performance issues.
   - **Source**: Industry best practices (USE Method).

7. **Network I/O**:
   - **Measures**: Data sent and received over the network.
   - **Importance**: Indicates the network performance and potential bottlenecks.
   - **Usage**: Monitor to ensure efficient network operations and detect performance issues.
   - **Source**: Industry best practices (USE Method).

8. **Database Query Performance**:
   - **Measures**: Time taken to execute database queries.
   - **Importance**: Indicates the performance of database operations and potential bottlenecks.
   - **Usage**: Monitor to ensure efficient database operations and detect performance issues.
   - **Source**: Industry best practices.

9. **Cache Hit/Miss Ratio**:
   - **Measures**: Effectiveness of caching.
   - **Importance**: Indicates the performance of caching mechanisms and potential improvements.
   - **Usage**: Monitor to ensure efficient caching and optimize performance.
   - **Source**: Industry best practices.

10. **Garbage Collection Time**:
    - **Measures**: Time spent in garbage collection.
    - **Importance**: Indicates the performance of memory management and potential bottlenecks.
    - **Usage**: Monitor to ensure efficient memory management and detect performance issues.
    - **Source**: Industry best practices.

## Sources

1. [Google Web Vitals](https://web.dev/vitals/)
2. [The Four Golden Signals](https://landing.google.com/sre/sre-book/chapters/monitoring-distributed-systems/)
3. [The RED Method](https://www.weave.works/blog/the-red-method-key-metrics-for-microservices-architecture