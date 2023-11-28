# Supervised Anomaly Detection Accelerator
---

## Overview

The supervised anomaly model is designed to handle multivariate data as input and predicts both a lower and upper value that encompasses the target variable/signal under normal conditions, based on a user-specified probability or confidence level. The higher the chosen probability, the less likely it is to observe the monitored signal outside of the predicted interval under in-distribution conditions. Consequently, any measured target variable falling outside the predicted interval can be considered an anomaly, with the probability of false alarm equal to the probability specified for the prediction interval.

Two typical examples:
- Predicting Anomalies/Alarms in Wind Turbine Gearboxes using Operational, Maintenance, Sensor Warning, and Weather Data
- Predicting Anomalies/Alarms in Electrical Transformers by analyzing Power Quality, Sensor, Sensor Warning, and Work Order data

## Onboarding Guide
This repository includes a comprehensive guide for building and deploying a conformal prediction based model using AI Model Factory's - Supervised Anomaly Recipe (available as API endpoint) for Maximo Monitor Application. It provides all the necessary resources, including 
1. Sample data for `Wind Turbine` Asset
2. AI Cookbook to facilitate model training using `AI Model Factory` Service, 
3. Creating an IoT device on `Monitor`, 
4. Deploying and configuring the `KPI` endpoints to the created device, 
5. Conducting inference with real-time data streaming into `Monitor`,  
6. `Visualizing` the results through an intuitive dashboard

Navigate to the **[onboarding](onboarding)** folder, where you'll discover all the resources essential for utilizing our supervised anomaly detection accelerator. To streamline and automate the entire procedure, we have provided a detailed outline of the required steps. 

Completing the walkthrough should take around 15 minutes, taking into account the time needed for training, deployment, and inference on a dataset of size 10,000 during the demonstration.

## Security
See [**CONTRIBUTING**](./CONTRIBUTING.md) for more information.

## License
This collection of AI cookbooks is licensed under ???. See the [**LICENSE**](LICENSE) file.

## Questions
Please contact [**Dhaval Patel**](mailto:pateldha@us.ibm.com) or raise an issue on this repository.
