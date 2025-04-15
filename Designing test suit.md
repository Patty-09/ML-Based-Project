
### **Software Testing – Overview**

**Software Testing** is a critical part of the software development lifecycle aimed at ensuring the **quality**, **reliability**, and **correctness** of a software product. As per ANSI/IEEE 1059, testing involves analyzing a software item to detect defects and evaluate its features.

### **Purpose of Testing**
- **Verification**: Checks whether the product is built according to specifications.
- **Validation**: Ensures the product meets the user's needs.
- **Defect**: A deviation from expected results due to faults in specification, design, or coding.

### **Standards for Software Testing**
Common IEEE standards include:
- **IEEE 829** – Test Documentation
- **IEEE 1008** – Unit Testing
- **IEEE 1012** – Verification & Validation
- **IEEE 1028** – Inspections
- **IEEE 1044/1044.1** – Anomaly Classification
- **IEEE 730** – Quality Assurance Plans
- **IEEE 1061** – Software Quality Metrics
- **IEEE 12207** – Software Life Cycle Processes
- **BS 7925** – Testing Vocabulary & Component Testing

### **Testing Frameworks**
- **JUnit** – Java unit testing
- **Selenium** – Web automation testing
- **HP QC (ALM)** – Test management
- **IBM Rational** – Software lifecycle support

### **Need for Testing**
- Identifies and helps fix faults
- Improves **reliability**, **usability**, **maintainability**
- Ensures compliance with legal and industry standards (e.g., aerospace, railways)
- Prevents critical failures like the **Millennium Bug**


### **Test Cases and Test Suites**
- A **test case** includes inputs (preconditions and actual inputs) and expected output.
- A **test suite** is a collection of test cases.

### **Types of Software Testing**

#### **1. Unit Testing**
- Tests individual components or functions.
- Two approaches:
  - **Black Box**: Based on inputs and outputs (e.g., Equivalence Partitioning, Boundary Value Analysis)
  - **White Box**: Based on code structure (e.g., control flow, data flow)

#### **2. Integration Testing**
- Tests interactions between modules.
- Approaches:
  - **Top-down**: Starts from top modules to bottom
  - **Bottom-up**: Starts from low-level modules upward

#### **3. System Testing**
- Tests the complete system against requirements.
- Types:
  - **Alpha Testing**: By developers or users with developers present
  - **Beta Testing**: By selected end users before release
  - **User Acceptance Testing (UAT)**: Ensures system meets user requirements

#### **4. Regression Testing**
- Ensures new changes or bug fixes haven’t broken existing functionality.
- Reuses previous test cases to validate unmodified parts.

### **Example**
**Program**: Compute square of number in range 1–100  
**Test Cases**:  
- I1: -2 → O1: Beyond range  
- I3: 1 → O3: Square is 1  
- I4: 100 → O4: Square is 10000  
- ... and so on.

### **Important Notes**
- **Testing is a continuous process**, not just post-coding.
- Begins with **test case preparation** after requirements are finalized.
- Good testing not only proves correctness but **reveals bugs**.
