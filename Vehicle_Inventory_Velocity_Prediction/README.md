# Vehicle Inventory Velocity Prediction

## Business Problem
Inventory holding costs and floorplan interest are among the largest financial liabilities for automotive retail networks. While the national average dwell time for inventory can stretch past 70 days, top-performing networks target a turn rate of 28 to 33 days. Unsold vehicles sitting on dealership lots deteriorate profit margins daily. 

## Solution
This project establishes a predictive supply chain and inventory velocity pipeline using a **Random Forest Regressor**. By predicting the exact continuous variable of "Days on Lot" for incoming inventory before vehicles ever physically land at the dealership, inventory managers can gain foresight into logistical bottlenecks. Vehicles flagged as high-risk slow-movers can be proactively rerouted to high-demand regions or matched with targeted marketing incentives on Day 1.

## Key Features
* **Logistics Data Engineering:** Models multi-dimensional market inputs including regional supply indices, manufacturer suggested retail prices (MSRP), trim lines (LE, XLE, TRD Pro), and drivetrain configurations.
* **Continuous Dwell Time Forecasting:** Moves beyond simple binary classification to deliver precise day-count predictions via regression.
* **Proactive Incentive Optimization:** Features an integrated financial model to evaluate the exact cost-benefit threshold of applying proactive consumer incentives to save on asset depreciation.

## Performance & Valuation Metrics
* **Technical Reliability:** Achieved a **Mean Absolute Error (MAE) of +/- 5.1 days** on inventory turn forecasting with an **R-Squared of 0.797**.
* **Risk Mitigation:** Successfully identified 476 high-risk vehicle units predicted to exceed 60 days on the lot.
* **Net Financial Savings:** Implementing a proactive $500 marketing incentive to move these predicted slow-movers 20 days faster offsets floorplan interest by $600 per unit, generating a net savings of **$47,600.00** across the test set.

## Tech Stack
* **Language:** Python
* **Modeling:** Scikit-Learn (Random Forest Regressor)
* **Data Processing:** Pandas, NumPy
* **Visualization:** Seaborn, Matplotlib

## How to Run
1. Install required packages: `pip install scikit-learn pandas numpy matplotlib seaborn joblib`
2. Run the `Inventory_Forecasting.ipynb` notebook.
3. The script will train the model, output performance graphs, and save the serialized production asset as `inventory_velocity_rf_model.pkl`.
