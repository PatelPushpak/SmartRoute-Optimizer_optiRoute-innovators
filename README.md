# SmartRoute-Optimizer_optiRoute-innovators
##  Project Overview
**Smart Route Optimizer** is an AI/ML-powered delivery planning solution designed to optimize grocery and essential item deliveries. The solution automates trip creation, shipment sequencing, and vehicle assignment while minimizing travel distance, delivery time, and operational costs.

##  Problem Statement
- Manual trip planning leads to inefficient delivery routes and schedules.
- Underutilized resources result in poor vehicle capacity management and higher operational costs.
- High delivery times occur due to inefficient route sequencing.
- Higher fuel costs arise from non-optimized delivery routes.
- Inflexible scheduling makes it difficult to accommodate special time slot preferences.

##  Features
- **AI-based Route Optimization:** Intelligent algorithms determine the most effective delivery routes.
- **Automated Vehicle Assignment:** Selects the best-suited vehicle based on volume and priority.
- **Time-slot Awareness:** Ensures deliveries are completed within specified time slots.
- **Capacity Utilization:** Maximizes vehicle load to reduce trips and fuel costs.
- **Real-time Traffic Awareness:** Uses live traffic data to enhance route planning.

## Proposed Approach
### Data Cleaning & Preprocessing
- Remove duplicate entries to avoid redundancy.
- Save cleaned dataset as `Cleaned_SmartRoute_Optimizer.csv`.

### Data Splitting for Training & Testing
- Split dataset into 80:20 ratio using `train_test_split()`.
- Save split datasets as `Train_80.csv` and `Test_20.csv`.

###  Data Analysis & Insights
- Check for missing values.
- Generate summary statistics of numerical features.

## Optimization Techniques
- **K-Means Clustering:** Groups nearby deliveries to reduce travel distance and improve efficiency.
- **Minimum Spanning Tree (MST):** Optimizes delivery routes by minimizing total travel distance.
- **Vehicle Selection:** Assigns the best-suited vehicle based on weight, capacity, and distance constraints.
- **Time & Capacity Optimization:** Balances trip duration and load capacity to maximize resource utilization.


##  References
- [A comprehensive study on optimizing Delivery Routes through Generative AI](https://www.researchgate.net/publication/384467526_A_comprehensive_study_on_optimizing_Delivery_Routes_through_Generative_AI_using_Real-Time_Traffic_and_Environmental_Data)
- [Google Maps API](https://developers.google.com/maps)
- [OpenStreetMap Routing API](https://www.openstreetmap.org)
- Python Libraries: `NetworkX`, `Folium`, `Scikit-learn`, `Pandas`

## Team
**OptiRoute Innovators**
- Patel Prachi Paragkumar
- Bhalodiya Devanshi Kishorkumar
- Radadiya Hetvi Hasmukhbhai
- Patel Pushpak Pareshbhai
- Mungra Heet Vimalbhai

