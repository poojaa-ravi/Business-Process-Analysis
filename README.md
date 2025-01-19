# **Hive Systems CMMC Level 2 Assessment Tool**  
**A User-Friendly Self-Assessment Tool for CMMC Level 2 Compliance**  

## **Overview**  
Many companies struggle with the intricacy of cybersecurity compliance requirements, finding it difficult to navigate various standards, regulations, and frameworks. This tool simplifies the process, making it accessible and affordable for businesses of all sizes.  

### **Objective**  
To develop a user-friendly self-assessment CMMC Level 2 tool, enabling companies to streamline their compliance journey.  

## **Features**  
- **Controls Categorization**:  
  1. **Base Bucket**: Standard scoring logic.  
  2. **Special Bucket**: Unique scoring conditions.  
  3. **POA&M Bucket**: Editable within 180 days post-compliance test.  

### **Control Scoring Logic**  
#### **Base Controls**  
- Do not change score only if all sub-controls are `MET` or `NOT APPLICABLE`.  
- Subtract a score if any sub-control is `NOT MET`.  

#### **Special Controls**  
- **Remote Access**:  
  -  Subtract score if remote access is not allowed.  
  - Otherwise, Do not change a score only if all sub-controls are `MET`.  
- **Absence of SSP**:  
  - Deduct 110 points if control is `NOT MET`.  
  - No deduction if `MET` or `NOT APPLICABLE`.  

---
