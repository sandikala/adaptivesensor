# adaptivesensor
The study proposes a novel Integrated Adaptive Sensor Selection and Hybrid Privacy-Preserving (HE-SMPC) architecture designed for the Unified and Sustainable Sensing as a Service (USSenaaS) framework in smart city environments.
## Repository Contents

The repository includes the following files:

1. **`air_data (1).csv`**
   - **Description:** The empirical sample trace dataset harvested from mobile sensing nodes attached to the Bandung CitySense platform. It contains PM2.5 concentration levels ($\mu g/m^3$) and battery voltage readings.
   - **Usage:** Serves as the raw input data for both simulation notebooks.

2. **`Optimized Sensor Selection.ipynb`**
   - **Description:** This notebook analytically models the temporal-adaptive sensor selection mechanism. 
   - **Outputs:** - Calculates the data volume transmission reduction (achieving 70.4% reduction).
     - Generates the comparative processing & transmission latency graph.
     - Renders the data utility/signal reconstruction graph demonstrating the preservation of environmental trends despite aggressive data filtering.

3. **`Hybrid Privacy-Preserving.ipynb`**
   - **Description:** This notebook simulates the mathematical computation latency and cryptographic overhead of the proposed framework.
   - **Outputs:**
     - Evaluates the total processing time across varying simulated packet sizes (100 to 5000 packets).
     - Generates the logarithmic computation overhead comparison graph between Plaintext (Baseline), Standard Homomorphic Encryption (HE), and the Proposed Hybrid HE-SMPC mechanism.

## Experimental Requirements

The trace-driven simulations were executed in a cloud-based computational environment (Google Colaboratory). To run the code locally or on the cloud, the following software specifications are required:

* **Programming Language:** Python 3.10+
* **Required Libraries:** - `pandas` (Data manipulation)
  - `numpy` (Numerical operations)
  - `matplotlib` (Data visualization)
  - `seaborn` (Enhanced plot styling)

## How to Run the Simulations

1. Clone this repository or download the ZIP file.
2. Upload the `air_data (1).csv` dataset to your working directory or directly into your Google Colab session.
3. Open either of the `.ipynb` files using Jupyter Notebook, JupyterLab, or Google Colaboratory.
4. Execute the cells sequentially (`Run All`).
5. The output graphs will be automatically generated and saved as high-resolution Vector files (`.svg` and `.pdf`) in the same directory.

## Citation

If you use this code or dataset in your research, please cite our paper later.

