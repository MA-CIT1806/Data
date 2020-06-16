# Data
Data sets for the experiments conducted in this thesis.

Each root folder corresponds to an anomaly class. Within such a folder, the recordings, i.e. multivariate time series data, of anomaly injections into certain service components can be found, categorized by service component.

Since the number of observed metrics is the same for all targeted service components, each recording has the same number of rows but a differing column count. The data is stored as csv-files.

#### Anomalies:
- bandwidth
- download
- mem_leak
- packet_duplication
- packet_loss
- stress_cpu
- stress_hdd
- stress_mem

#### Service Components:
- astaire
- backend (i.e. video-server)
- bono
- chronos
- homer
- homestead
- load-balancer
- sprout
- cassandra

The cassandra service component is the only one not target to bandwidth, packet_duplication and packet_loss anomaly injections.
