### Brier Score Results  

**Scope:**  
- **Questions:** 9,693 Polymarket True/False & Multiple Choice questions  
- **Date Range:** April 2023 to October 2024 (18 months)  
- **Data Set Link:** [Polymarket Dataset](https://examplebucketedge.s3.us-east-2.amazonaws.com/polymarket_dataset.csv)  

**Explanation:**  
- **0.0 (Lowest Brier Score):** Represents perfect accuracy where probabilities match the actual outcomes.  
- **1.0 (Highest Brier Score):** Represents completely inaccurate probabilistic predictions.

**Evaluation (Very Important!):**  
- **System Evaluation Link:** [https://colintheadmin.com](https://colintheadmin.com)  

---

**System 1:**  
- **Outcome:** Brier Score of **0.5625**
- **Technology:** One "LLama 3 8B Instruct" instance
- **Knowledge Cutoff:** March 2023
- **Model Link:** [Hosted on Replicate](https://replicate.com/meta/meta-llama-3-8b-instruct)  
- **System Codebase:** [Github Link](https://github.com/Forecasting-Research-NExT/testing_framework_system_one)
- **Endpoint Link:** [https://ptzpqa9nnv.us-east-2.awsapprunner.com](https://ptzpqa9nnv.us-east-2.awsapprunner.com)

**System 2:**  
- **Outcome:** Brier Score of **0.36**
- **Technology:** One "LLama 3 8B Instruct" instance of a Director Agent, with an infinite number of Specialist Agents (more LLama 3 8B Instruct instances) to answer specific subquestions, to help the Director Agent answer the original question
- **Knowledge Cutoff:** March 2023
- **Model Link:** [Hosted on Replicate](https://replicate.com/meta/meta-llama-3-8b-instruct)  
- **System Codebase:** [Github Link](https://github.com/Forecasting-Research-NExT/testing_framework_system_two)
- **Endpoint Link:** Not yet evaluated in cloud environment

