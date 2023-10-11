# Multivariate Time Series Anomaly Detection Toolkit

This repository contains a toolkit for Multivariate Time Series Anomaly Detection, which includes state-of-the-art methods with a unified and easy-to-use interface.

Multivariate time series (MTS) are a group of inherently correlated time series. For instance, in manufacturing industry and Information Technology (IT) systems, an entity (e.g., a physical machine or software service) is typically equipped with a monitoring mechanism to ensure its security or reliability.

Unlike anomaly detection on single time series, recent studies indicate that the dependency hidden in MTS is crucial for accurate anomaly detection. The anomaly detector should consider the MTS as a whole. To address this, state-of-the-art methods have resorted to deep learning-based methods to capture the dependency for more accurate anomaly detection.

## Models Integrated in This Repo

| Model     | Paper Reference                                                                                                              |
|-----------|------------------------------------------------------------------------------------------------------------------------------|
| MSCRED    | [AAAI'19] A Deep Neural Network for Unsupervised Anomaly Detection and Diagnosis in Multivariate Time Series Data           |
| MTAD-GAT  | [ICDM'2020] Multivariate Time-series Anomaly Detection via Graph Attention Networks                                           |
| GDN       | [AAAI 2021] Graph Neural Network-Based Anomaly Detection in Multivariate Time Series                                           |
| GLUE      | [ICLR'2021] Learning Graph Neural Networks for Multivariate Time Series Anomaly Detection                                     |

## Datasets 

The following datasets have been kindly released by various institutions or schools. Raw datasets can be downloaded or applied for via the link provided behind the dataset names. The processed datasets can be found [here](https://drive.google.com/drive/folders/1NEGyB4y8CvUB8TX2Wh83Eas_QHtufGPR?usp=sharing).

- **Server Machine Dataset (SMD)**: [Download raw datasets](https://github.com/NetManAIOps/OmniAnomaly.git)
  > Collected from a large Internet company, it contains 5-week-long monitoring KPIs of 28 machines. The meanings of each KPI can be found [here](https://github.com/NetManAIOps/OmniAnomaly/issues/22).

- **Soil Moisture Active Passive satellite (SMAP)** and **Mars Science Laboratory rover (MSL)**: [Download raw datasets](link)
  > These datasets, collected from operational spacecraft, contain a set of telemetry anomalies corresponding to actual spacecraft issues involving various subsystems and channel types.

- **Secure Water Treatment (WADI)**: [Apply here](https://itrust.sutd.edu.sg/itrust-labs_datasets/dataset_info/)
  > WADI is collected from a real-world industrial water treatment plant, containing 11-day-long multivariate KPIs. The system is in a normal state for the first seven days and is under attack for the following four days.

- **Water Distribution (SWAT)**: [Apply here](https://itrust.sutd.edu.sg/itrust-labs_datasets/dataset_info/)
  > An extended dataset of SWAT. It includes 14-day-long operational KPIs collected during normal system operation and 2-day-long KPIs obtained during system attack scenarios.

\* WADI and SWAT datasets were released by iTrust and must be applied for individually. You can request the raw datasets and preprocess them with our preprocessing scripts.
