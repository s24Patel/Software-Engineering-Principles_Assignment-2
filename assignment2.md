# **Assignment #2: Understanding the Requirements**

## **Current Two Requirements**

### **Requirement 1: Organizing Training Data**
**As a developer, I want to organize training questions separately from answers so that I can manage training data efficiently.**

#### Assumptions & Validation:
- **Assumption:** Developers want an easy way to organize training data.
- **Validation:** Conduct interviews with developers to confirm their data organization preferences.

#### **Preliminary Tasks:**
- Create a system that enables questions and answers to be stored separately.
- Utilize the search and filter functions to make data retrieval simple.
- Create a user-friendly interface for data management and organization. 

#### **Outcome:**
- Developers can quickly find and categorize training data, improving efficiency and reducing errors.

---

### **Requirement 2: Checking for Bias in Training Data**
**As a developer, I want to ensure that the training data is balanced so that I can create fair and accurate AI models.**

#### **Assumptions & Validation:**
- **Assumption:** There are reliable tools that can help detect bias in AI training data.
- **Validation:** Test bias detection tools and get feedback from developers.

- **Assumption:** Balanced training data leads to better AI performance.
- **Validation:** Compare AI models trained with and without balanced data.

#### **Preliminary Tasks:**
- Investigate and incorporate AI technologies for detecting bias. 
- Put in place a warning system to draw attention to any biases.
- Create a manual review procedure for biases that have been reported. 

#### **Outcome:**
- AI models perform more fairly and accurately, avoiding biased decision-making.


## **Additional Requirements**

### **Requirement 3: Legal Compliance**
**As a system owner, I want to ensure that the collected data is legal to use so that we comply with regulations.**

#### **Assumptions & Validation:**
- **Assumption:** The data being collected is legal to use.
- **Validation:** Consult legal experts to ensure compliance with data regulations.

#### **Preliminary Tasks:**
- Research relevant legal guidelines on AI training data.
- Implement consent mechanisms for data usage.
- Develop a data compliance checklist.

#### **Outcome:**
- The system remains legally compliant, avoiding potential legal risks.


### **Requirement 4: Secure System Access**
**As a system administrator, I want to restrict access to training data so that only authorized users can modify it.**

#### **Assumptions & Validation:**
- **Assumption:** Only approved users should be able to access certain features.
- **Validation:** Conduct security audits to ensure access controls work correctly.

#### **Preliminary Tasks:**
- Implement user authentication and role-based access control.
- Set up logging to track modifications and access attempts.
- Encrypt stored data to prevent unauthorized access.

#### **Outcome:**
- Unauthorized users are blocked, ensuring data security and integrity.


### **Requirement 5: Performance Optimization**
**As a developer, I want the system to handle large amounts of data efficiently so that it remains fast and responsive.**

#### **Assumptions & Validation:**
- **Assumption:** The system should handle large amounts of data quickly and efficiently.
- **Validation:** Test performance with large datasets and measure response times.

#### **Preliminary Tasks:**
- Optimize database queries for speed.
- Implement caching mechanisms for frequently accessed data.
- Conduct load testing to ensure stability under high usage.

#### **Outcome:**
- The system remains fast, even with large data loads, improving developer productivity.


### **Requirement 6: Generating Reports and Insights**
**As a developer, I want to generate reports on how balanced the training data is so that I can track improvements.**

#### **Assumptions & Validation:**
- **Assumption:** Developers need insights into training data balance.
- **Validation:** Gather feedback from developers on the usefulness of generated reports.

#### **Preliminary Tasks:**
- Build a dashboard to display training data statistics.
- Create reports that visualize data balance.
- Allow users to download reports in different formats.

#### **Outcome:**
- Developers can monitor and improve AI training data over time.


## **Functional Requirements:**

### **Requirement 7: Data Collection Automation**
**As a system, I should be able to automatically scrape and collect publicly available training data so that developers do not have to do it manually.**

#### **Assumptions & Validation:**
- **Assumption:** Web scraping can be automated effectively.
- **Validation:** Test different web scraping frameworks for efficiency.

#### **Preliminary Tasks:**
- Identify trusted data sources for training.
- Develop a web scraping script to automate data collection.
- Implement error handling to manage failed scrapes.

#### **Outcome:**
- Developers save time by having automated data collection.


### **Requirement 8: Data Cleaning and Preprocessing**
**As a system, I should be able to clean and preprocess collected training data so that developers receive high-quality input for AI models.**

#### **Assumptions & Validation:**
- **Assumption:** Collected data will require preprocessing to be usable.
- **Validation:** Analyze raw data to determine common preprocessing needs.

#### **Preliminary Tasks:**
- Implement algorithms to remove duplicate and irrelevant data.
- Standardize formatting across different data sources.
- Develop a logging system for tracking preprocessing steps.

#### **Outcome:**
- AI models receive clean, high-quality training data, improving performance.


### **Requirement 9: Model Training Workflow**
**As a system, I should provide a seamless workflow for training AI models with the processed data so that developers can efficiently build models.**

#### **Assumptions & Validation:**
- **Assumption:** Developers want an integrated system for data preprocessing and model training.
- **Validation:** Gather feedback from developers on their training workflow needs.

#### **Preliminary Tasks:**
- Design a pipeline that connects preprocessed data to model training.
- Implement logging and reporting features for training runs.
- Allow developers to configure model parameters easily.

#### **Outcome:**
- AI model training becomes easier and more efficient.
