# MSc_Thesis-Delta-Lake-Apache-Iceberg-and-Apache-Hudi

This repository contains the final thesis for the MSc degree in Data Science and Machine Learning at the National Technical University of Athens (NTUA).

## 🎯 Purpose of the Study

This study aims to **analyze and experimentally evaluate** the performance of three popular Log-Structured Table (LST) data storage systems — **Delta Lake**, **Apache Iceberg**, and **Apache Hudi** — under a variety of workload scenarios.

### 🔑 Key Objectives

- Study the design and architecture of each system.  
- Conduct experimental performance evaluations using realistic workload scenarios.  
- Identify the key differences, strengths, and limitations of each system across different use cases.
  

## 📘 Abstract

As the need for efficient data storage and processing continues to grow, new technologies
have emerged to address the limitations of traditional data warehouses by introducing more
effective storage models and advanced data management capabilities. This thesis focuses on the
analysis and comparative evaluation of three modern data storage systems, Delta Lake, Apache
Iceberg, and Apache Hudi, which aim to combine the performance advantages of columnar
storage with features for data updates and version tracking. These systems are designed to
overcome the drawbacks of both traditional data warehouses and columnar storage formats.
The study begins with a theoretical overview of the architecture and main characteristics of
each system. This is followed by a performance evaluation using the LST-Bench tool, with a
series of workloads that simulate real-world usage scenarios. The experiments were executed
in a distributed environment where Apache Spark was used for data processing and Apache
Hadoop for data storage. The results offer useful insights into the performance, strengths, and
limitations of each solution, showing under which conditions each performs best. Overall, this
thesis provides practical guidance for choosing the most suitable system depending on specific
needs and workload patterns.
