# 🌐 Cloud Web-Traffic-Classification

## 📝 Description
This project focuses on analyzing and classifying web traffic patterns using machine learning techniques to detect potential security threats and anomalies in cloud infrastructure. The project utilizes AWS CloudWatch data to identify suspicious web traffic patterns and potential security breaches.

## 🚀 Features
- Web traffic analysis using AWS CloudWatch data
- Anomaly detection using Isolation Forest algorithm
- Traffic pattern classification
- Security threat detection
- Data visualization and analysis

## 🛠️ Technologies Used
- Python 3
- Pandas for data manipulation
- Scikit-learn for machine learning
- Matplotlib for visualization
- AWS CloudWatch data integration

## 📊 Dataset
The project uses the `CloudWatch_Traffic_Web_Attack.csv` dataset which contains:
- Network traffic metrics (bytes_in, bytes_out)
- Timestamp information
- Source and destination IP addresses
- Protocol information
- Response codes
- Port information
- Security rule names and observations

## 🔧 Installation
1. Clone the repository:
```bash
git clone https://github.com/yourusername/Cloud-Web-Traffic-Classification.git
```

2. Install required packages:
```bash
pip install pandas numpy scikit-learn matplotlib
```

## 📖 Usage
1. Place your CloudWatch traffic data in CSV format
2. Run the Jupyter notebook `CloudWatch_Traffic_Web_Attack-Classification.ipynb`
3. Follow the analysis steps in the notebook

## 🔍 Analysis Process
1. Data loading and preprocessing
2. Feature engineering
3. Anomaly detection using Isolation Forest
4. Traffic pattern classification
5. Results visualization and interpretation

## 📈 Results
The project provides:
- Classification of web traffic patterns
- Detection of suspicious activities
- Visualization of traffic patterns
- Performance metrics of the classification model

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Authors
- Your Name - Initial work

## 🙏 Acknowledgments
- AWS CloudWatch for providing the data
- Scikit-learn community for the machine learning algorithms
- Contributors and maintainers of the libraries used

---
⭐️ If you find this project helpful, please consider giving it a star! 