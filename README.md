# ASU_ONR - Network Threat Detection Using Machine Learning

Welcome to the **ASU_ONR** project! This repository contains work from a cybersecurity research initiative at **Alabama State University**, funded by the Office of Naval Research (ONR). The goal is to detect suspicious network behavior using machine learning and deep learning models.

---

##  Project Structure

| File | Description |
|------|-------------|
| `CleaningAndPreprocesssing.ipynb` | Loads and preprocesses network traffic data efficiently, optimizing for memory usage. |
| `NetworkThreatDetection.ipynb` | Implements unsupervised and supervised learning techniques to detect anomalies and threats. |

---

##  Project Goals

-  Clean and preprocess high-dimensional network flow datasets.
-  Detect outliers and attacks using **DBSCAN** clustering.
-  Train RNN Model to detect malicous activities.
-  Visualize network activity trends for insights.

---

##  Dataset Overview

- Raw network flow captured with over **80 features** including:
  - IPs, ports, protocol
  - Packet lengths, flow duration, inter-arrival times
  - TCP flag counts

---

##  Tools & Libraries

- **Python 3**
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn` (DBSCAN)
- `tensorflow` / `keras` (RNN model)
- `tqdm`, `gc` for performance

---

##  How to Run

```bash
# Clone the repo
git clone https://github.com/your-username/ASU_ONR.git
cd ASU_ONR

# (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install required packages
pip install -r requirements.txt

# Launch the notebooks
jupyter notebook
