# Distribution Network Optimization Project
This project implements a multi-stage distribution network optimization model involving factories, warehouses, and customers. It aims to determine the most cost-effective distribution paths while satisfying customer demand and operational constraints.

📦 #Project Structure

📁 data/

├── costs_fa.xlsx      # Transportation costs from factories to warehouses

├── costs_ac.xlsx      # Transportation costs from warehouses to customers

├── demand.xlsx        # Customer-specific product demand

├── products.xlsx      # Product details and identifiers

├── return.xlsx        # Return cost or data (if applicable)

📓 Distribution_Optimization.ipynb  # Main modeling and analysis notebook

🧠 Problem Description

The network comprises:

Factories that manufacture multiple products

Warehouses that serve as intermediate distribution points

Customers with specific product demand profiles

The objective is to minimize total distribution cost, including:

Cost from factories to warehouses

Cost from warehouses to customers

Return costs (if any)

⚙️ Model Features
Input from Excel data files

Demand handled per customer and product

Cost matrices for both stages of transport

Return cost considerations

Output: optimized flow quantities and total cost

▶️ How to Run
Clone the repository:

git clone https://github.com/OzlemGulsumKilickaya/distribution-network-optimization.git
cd distribution-network-optimization
Ensure the following Python packages are installed:

pip install pandas openpyxl
Open and run the Jupyter notebook:
jupyter notebook Distribution_Optimization.ipynb
📊 Sample Outputs
Total minimized cost

Distribution flow matrices

Demand satisfaction summary

📄 Documentation
Additional documents:

Modelo3 - ingles.docx: Model description (in English)

Modelo3 - data.docx: Dataset structure explanation

infeasible_model.lp: LP model representation for debugging
