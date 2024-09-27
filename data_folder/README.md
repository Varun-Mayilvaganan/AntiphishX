### Dataset Acquisition

For this project, we sourced our datasets from reputable open-source platforms to ensure a diverse and effective training environment for our machine learning models.

1. **Phishing URLs**: We gathered phishing URLs from **PhishTank**, an excellent open-source service that curates a continuously updated collection of phishing URLs. This resource provides data in various formats, such as CSV and JSON, and refreshes its content every hour. You can download the data directly from their [developer site](https://www.phishtank.com/developer_info.php). From this extensive dataset, we extracted **5,000 random phishing URLs** to train our models effectively.

2. **Legitimate URLs**: The legitimate URLs were sourced from the **University of New Brunswick**, which offers a comprehensive open dataset containing benign, spam, phishing, malware, and defacement URLs. For our purposes, we specifically selected the benign URL subset. Again, we took **5,000 random legitimate URLs** from this dataset to ensure our model learns from a balanced perspective. This dataset can be accessed at [UNB URL Dataset](https://www.unb.ca/cic/datasets/url-2016.html).

Both datasets have been uploaded to the **data_folder** folder of this repository for your convenience.
