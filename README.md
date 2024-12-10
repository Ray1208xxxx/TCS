# TCS (Performance) IT Infrastructure Benchmarking Project
## Fall 2024 Capstone
## Carnegie Mellon University - Heinz College

### Team: Mbalenhle Holt, Pengrui Zeng, Pranav Naik, Abhineet Chaudhary & Chitra Raghavendrarao Krishnarao

---

# **Benchmarking Framework**

## **Overview**
The Benchmarking Framework is a comprehensive tool designed to evaluate and optimize key organizational areas, including **process efficiency**, **security**, **workforce productivity**, and **cost efficiency**. By leveraging industry data and advanced analytics, this framework provides actionable insights to drive performance improvements and align with best practices.

---

## **Key Features**
- **Process Benchmarking**:  
  - Evaluate operational workflows and identify areas for improvement in cycle times, resource allocation, and throughput.
  - Focuses on data and asset management processes to improve operational efficiency, cost-effectiveness, and security.
  - Includes streamlining workflows and reducing redundancy to identify opportunities for cost optimization.

- **Security Benchmarking**:  
  - Assess security posture using metrics such as incident response times, vulnerability detection, and regulatory compliance.
  - Assesses the effectiveness of security measures, policies, and practices.
  - Aims to measure resilience against cybersecurity threats while ensuring compliance with industry standards.

- **Workforce Productivity**:  
  - Analyze team performance with metrics like task completion rates, efficiency, and resource utilization.
  - Focuses on leveraging tools like AI to enhance workforce productivity for IT infrastructure.
  - Links improved workforce efficiency to reduced operational costs and higher return on investment (ROI).

- **Cost Efficiency**:  
  - Compare spending patterns against industry standards to optimize the total cost of ownership (TCO) and resource utilization.
  - Measures cost optimization through metrics like the Cost Efficiency Index (CEI) to quantify financial ROI.
  - Analyzes reductions in operational costs, workforce expenditure, and data processing expenses.

---

## **Data Visualizations**  
The accompanying `.ipynb` notebooks include some of the following visualizations, offering insights into each key focus area:  

1. **Annual Growth Rate in Storage Spending**  
   - **Description**: A line chart illustrating the annual percentage changes in storage spending. It highlights patterns of volatility, notable trends, and anomalies in spending over time.  
   - **Purpose**: To identify periods of excessive or insufficient investment, allowing for an evaluation of spending consistency and strategic adjustments.  

2. **Moving Average Forecast for Storage Spending**  
   - **Description**: A comprehensive visualization combining historical storage spending data (blue line), a calculated moving average (orange dashed line), and a future spending forecast (green dashed line).  
   - **Purpose**: To smooth short-term fluctuations, uncover long-term trends, and provide projections to guide budget planning and resource allocation.  

3. **Box Plot of Cost Distribution Across Categories**  
   - **Description**: A box plot showing the distribution of costs associated with categories such as **maintenance**, **storage**, **backup**, and **operational costs**.  
   - **Purpose**: To identify cost variability, medians, and outliers, helping organizations target areas for cost optimization and resource allocation.  

4. **Scatter Plot: Asset Utilization vs. Total Cost**  
   - **Description**: A scatter plot mapping **asset utilization rates** against total costs, with data points color-coded by **downtime rates (%)** and sized by **energy consumption (kWh)**.  
   - **Purpose**: To identify cost-impact trends and prioritize assets requiring efficiency improvements or resource adjustments.  

5. **Line Plot: Downtime Rate and Idle Time Trends**  
   - **Description**: A dual-line graph comparing the **downtime rate (%)** (red line) and **idle time (hours)** (blue dashed line) over time.  
   - **Purpose**: To track correlations between downtime and idle periods, helping identify operational inefficiencies and the impact of maintenance schedules or policy changes.  

6. **KDE Plot: Downtime Hours vs. Server Utilization**  
   - **Description**: A kernel density estimation (KDE) plot visualizing the relationship between **downtime hours** and **server utilization**, highlighting patterns and correlations.  
   - **Purpose**: To pinpoint inefficiencies, with peaks indicating common values that need attention for optimization.  

7. **Line Plot: Total Cost per Utilization Over Time**  
   - **Description**: A line plot showing the trend of **total cost per utilization** over time, calculated as total cost divided by asset utilization.  
   - **Purpose**: To evaluate cost efficiency relative to asset utilization, with downward trends suggesting improvements and upward trends indicating potential inefficiencies.  

These visualizations collectively provide actionable insights into cost management, operational efficiency, resource utilization, and strategic investment decisions.  

---

## **Prerequisites**
- **Python**: Version 3.8 or later.
- **Libraries**: Ensure the following libraries are installed:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `sklearn`
  - `seaborn`
  - `statsmodels`

- **Data**: Collect and organize relevant historical and industry benchmark data for input.

---

## **Installation**
1. Clone this repository:
   ```bash
   git clone https://github.com/your-organization/benchmarking-framework.git
   ```

2. Navigate to the project directory:
   ```bash
   cd benchmarking-framework
   ```

3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## **Usage**

### **1. Data Input**  
   - Place your historical data and industry benchmark data within each `.ipynb` notebook. Supported formats include `.csv` and `.xlsx`.  
   - Replace the preloaded synthetic data with **historical data** for more accurate and context-specific analysis.  
   - Ensure data is categorized under **Process**, **Security**, **Productivity**, and **Cost Efficiency**.  

### **2. Running the Framework**  
   Execute the main script:  
   ```bash  
   python main.py  
   ```  
   Follow the prompts to select focus areas and desired metrics for benchmarking.  

### **3. Output**  
   - **Visualization**: Graphical insights into performance gaps and trends, now reflecting real-world data after replacing synthetic placeholders.  
   - **Reports**: Generate detailed benchmarking reports in the `output/` directory, tailored to your historical data for actionable recommendations.  

---

## **Next Steps**
1. **Utilization of Industry Data**: Continuously update the framework with the latest benchmarks and trends for more accurate comparisons.
2. **Refinement**: Improve metrics and algorithms for better results across all focus areas.
3. **Training the Model**: Incorporate real-world feedback to train and fine-tune the framework's prediction and analysis capabilities.
4. **Testing & Deployment**: Conduct iterative tests and deploy the framework incrementally within the organization or for clients.

---

A special thank you to TCS and CMU Heinz for the support of our final deliverable.
