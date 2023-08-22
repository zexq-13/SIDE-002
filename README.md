# SIDE-002

### About

The project aims to create a machine learning model that predicts whether a executable file is harmful to the system. By analyzing various attributes of the file, such as structure, pattern, opcode sequence, the model differentiates between benign and malicious processes. This predictive capability can be integrated into system monitoring tools for early threat detection and protection against harmful processes.

- [ ] Explore the characteristics of executable file and identify the information that can be extracted from them
- [ ] Identify a varied data source that captures typical features exhibited by malicious files
- [ ] Conduct EDA on the dataset and uncover relationships between attributes and the potential maliciousness of a file
- [ ] Develop a machine learning model capable of predicting the harmfulness of a file by utilizing its attributes
- [ ] Incorporate and deploy this model into production for application usage

### Dataset

The dataset used is DikeDataset, It is a labeled dataset of benign and malicious PE and OLE files. It's used to train AI algorithms for predicting malice and malware family membership. The dataset includes numeric malice labels (0 to 1) that can be discretized for standard classification. The goal is to enable AI techniques like machine learning and deep learning to make accurate malice predictions and classify files accordingly.

### Preprocessing 






