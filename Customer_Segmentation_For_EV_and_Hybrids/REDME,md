# Customer Segmentation for Targeted EV & Hybrid Marketing

## Business Problem
As automotive manufacturers accelerate the transition from internal combustion engines (ICE) to Hybrid and Battery Electric Vehicles (BEVs), marketing departments face massive customer acquisition barriers. Mass-blasting generic vehicle upgrade promotions to a massive database yields low conversion rates and increases customer opt-out rates. Precision targeting is required to match the right customer profile to the right powertrain.

## Solution
This project leverages **Unsupervised Machine Learning via K-Means Clustering** to segment an enterprise CRM database of 5,000 active ICE vehicle owners. By mining hidden, multi-dimensional patterns across variables like current vehicle age, annual mileage, local fuel costs, and household income, the algorithm automatically extracts distinct buyer personas. This lets marketing teams run hyper-targeted campaigns for emerging product lines (such as the bZ, bZ Woodlands, C-HR, and Highlander EV) with minimal ad waste.

## Key Features
* **Distance-Safe Data Normalization:** Implements Scikit-Learn's `StandardScaler` to normalize disparate feature metrics (e.g., zeroing out scale variances between $100,000 income and 5-year vehicle ages).
* **Dimensionality Reduction:** Exploys Principal Component Analysis (PCA) to project high-dimensional consumer behavior into a interpretable 2D scatter space.
* **Actionable Corporate Mapping:** Programmatically converts statistical cluster centroids into highly strategic, customized campaign playbooks.

## Discovered Customer Personas
* **Cluster 0: Prime EV Targets.** High-income tech adopters driving newer vehicles. *Corporate Action: Deploy early-reservation reservation campaigns for premium BEV lines (bZ/Highlander EV).*
* **Cluster 1: Prime Hybrid Upgrade Candidates.** Low vehicle efficiency, high annual mileage, facing premium local gas costs. *Corporate Action: Push low-payment hybrid leases (Prius, Camry Hybrid, RAV4 Hybrid).*
* **Cluster 2: Aging Vehicle Loyalists.** Owners of decade-old vehicles showing strong dealership service center loyalty. *Corporate Action: Provide trade-in equity evaluations paired with modern safety upgrade messaging.*
* **Cluster 3: General Audience.** Baseline brand metrics. *Corporate Action: Retain in standard, low-frequency brand-awareness lifecycles.*

## Tech Stack
* **Language:** Python
* **Clustering & Preprocessing:** Scikit-Learn (KMeans, PCA, StandardScaler)
* **Data Wrangling:** Pandas, NumPy
* **Data Storytelling:** Seaborn, Matplotlib

## How to Run
1. Install required packages: `pip install scikit-learn pandas numpy matplotlib seaborn`
2. Run the `Powertrain_Segmentation.ipynb` notebook.
3. The script will process the CRM data, train the unsupervised algorithm, display the cluster maps, and output the strategic customer list.
