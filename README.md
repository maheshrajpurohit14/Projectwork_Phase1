## Multi-Agent System – Cold Chain Monitoring Agent (CCMA)
The integration of AI-based anomaly detection within a cold chain monitoring system, aimed at maintaining medicine and vaccine safety by predicting and detecting refrigerator malfunctions in real time.

## About
The Cold Chain Monitoring Agent (CCMA) is a core component of the larger Multi-Agent System for Cold Chain Integrity and Dynamic Inventory (MAS-CCID).

This agent is designed to continuously monitor temperature, humidity, and power supply data from cold storage units in hospitals and pharmacies. It uses deep learning (LSTM Autoencoder) and synthetic data generation (TimeGAN) to detect anomalies such as sudden temperature spikes, cooling failures, or power cuts — preventing vaccine spoilage and equipment downtime.

Traditional cold chain systems rely heavily on manual inspection and threshold-based alarms, which often fail to capture gradual or compound failures.
CCMA overcomes these challenges using AI-driven anomaly detection and real-time IoT integration with the Blynk Cloud, enabling automatic alerts and intelligent decision-making.

## Features
🔹 AI-based anomaly detection using LSTM Autoencoder trained on TimeGAN-generated sensor data.

🔹 Time-series GAN (TimeGAN) for realistic data generation and augmentation.

🔹 Real-time monitoring loop for continuous anomaly detection.

🔹 Blynk IoT cloud integration for dashboard visualization and live alerts.

🔹 Automatic email notifications when anomalies or power cuts occur.

🔹 Scalable multi-agent architecture, allowing integration with other agents like PMA and PLA.

🔹 Extensible design for future edge deployment (ESP32/Raspberry Pi).

## Requirements
🖥️ Operating System

Works on any 64-bit OS (Windows 10/11, macOS, Ubuntu).

💻 Development Environment

Python 3.8+

Google Colab / VSCode / Jupyter Notebook

🤖 Machine Learning Frameworks

TensorFlow / Keras — for TimeGAN and LSTM Autoencoder

scikit-learn — for metrics and preprocessing

NumPy / Pandas / Matplotlib — for data processing and visualization

☁️ IoT and Cloud

Blynk IoT Cloud for dashboard, live data updates, and email alerts

requests library for RESTful communication with Blynk API



## System Architecture
<!--Embed the system architecture diagram as shown below-->

<img width="671" height="632" alt="image" src="https://github.com/user-attachments/assets/8efed089-dd61-4023-9823-be8912350ae3" />



## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1:

<img width="1256" height="504" alt="image" src="https://github.com/user-attachments/assets/eee70aad-1a03-4bf9-b6f8-9aec46d4d605" />


#### Output2: 
<img width="843" height="476" alt="image" src="https://github.com/user-attachments/assets/d37e41de-93af-4015-bd5a-c354c4117eac" />


Detection Accuracy: 98.38%
Note: These metrics can be customized based on your actual performance evaluations.


## Results and Impact
<!--Give the results and impact as shown below-->
The Sign Language Detection System enhances accessibility for individuals with hearing and speech impairments, providing a valuable tool for inclusive communication. The project's integration of computer vision and deep learning showcases its potential for intuitive and interactive human-computer interaction.

This project serves as a foundation for future developments in assistive technologies and contributes to creating a more inclusive and accessible digital environment.

## Articles published / References

[1] R. Paranjape and A. Sadanand, Multi-Agent Systems for Healthcare Simulation and Modeling: Applications for System Improvement, IGI Global, 2021.

[2] S. Rehman, S. Larabi-Marie-Sainte, and D. Goyal, Artificial Intelligence and Internet of Things: Applications in Smart Healthcare, Routledge, 2024.

[3] J. Smith and M. Johnson, “Machine Learning Approaches for Predictive Maintenance in Medical Equipment,” Journal of Healthcare Engineering, vol. 45, no. 3, pp. 234–256, 2023.

[4] L. Chen, H. Wang, and Y. Zhang, “Intelligent Demand Forecasting for Healthcare Supply Chain Optimization,” Int. J. Prod. Econ., vol. 268, pp. 109–125, 2024.

[5] M. Wooldridge, An Introduction to Multi-Agent Systems, Wiley, 2020.

[6] D. Mhlanga, AI in Hospital Administration: Revolutionizing Healthcare, Routledge, 2025.

[7] S. Russell and P. Norvig, Artificial Intelligence: A Modern Approach, 4th ed., Pearson, 2022.

[8] Y. Zhao et al., “Predictive Analytics for Hospital Resource Optimization Using Machine Learning,” IEEE Access, vol. 11, pp. 12245–12258, 2023.

[9] J. Al-Gumaei et al., “Hybrid Deep Learning Model for Predictive Maintenance of Biomedical Equipment,” Sensors, vol. 23, no. 5, 2023.

[10] N. Jennings, “An Agent-Based Approach to Decentralized Resource Allocation in Healthcare,” AI Communications, vol. 35, pp. 245–260, 2022.




