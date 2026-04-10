# SDN Mininet Project 
# SDN Mininet Project

## 📌 Overview
This project demonstrates bandwidth analysis using different network topologies in Mininet.

## 🧰 Tools Used
- Mininet
- iperf
- Ubuntu

## 🌐 Topologies Tested
- Single Topology
- Linear Topology
- Tree Topology

## 📊 Results

| Topology | Source | Destination | Throughput (Gbps) |
|----------|--------|------------|------------------|
| Linear   | h3     | h1         | 18.3             |
| Linear   | h3     | h2         | 19.9             |
| Linear   | h1     | h2         | 18.9             |
| Single   | h3     | h1         | 21.2             |
| Single   | h3     | h2         | 20.6             |
| Single   | h1     | h2         | 18.4             |
| Tree     | h4     | h1         | 18.1             |
| Tree     | h2     | h1         | 21.8             |
| Tree     | h2     | h4         | 17.7             |
| Tree     | h1     | h4         | 10.3             |

## 📸 Screenshots
Screenshots are available in the `screenshots` folder.

## 📄 Conclusion
Different network topologies affect bandwidth performance. Simpler topologies provide higher throughput compared to complex ones.
