---

## **Fandango Movie Ratings Analysis: Detecting Rating System Bias**

### **Project Overview**

This project investigates whether Fandango's movie rating system exhibits systematic bias or inflation in displayed ratings. The analysis leverages comparative data science techniques to examine rating patterns before and after a public controversy, providing actionable insights into data integrity issues within consumer-facing rating platforms.

### **The Problem**

In October 2015, data journalist Walt Hickey published research revealing that Fandango's 5-star rating system displayed systematically inflated ratings compared to actual user scores. Hickey's analysis demonstrated that Fandango was rounding user ratings upward in a non-transparent manner—a practice that appeared to boost the perceived quality of movies displayed to potential customers. 

Fandango claimed this was an unintentional bug rather than a deliberate deceptive practice and committed to fixing the issue. However, the central question remained: **Did Fandango actually resolve the rating inflation problem, or did it persist in subsequent years?**

### **The Solution**

This analysis employs a comparative data science approach to answer this critical question:

**Methodology:**
- **Dual Dataset Comparison**: Analyzed two distinct samples of movie ratings:
  - **Pre-Analysis Data** (2014-2015): Collected before Hickey's public investigation and Fandango's stated remediation
  - **Post-Analysis Data** (2016-2017): Collected after the controversy and claimed system correction
  
- **Multi-Source Rating Integration**: Cross-referenced Fandango ratings against industry-standard rating sources including:
  - Rotten Tomatoes (critics and user scores)
  - Metacritic (critics and user scores)
  - IMDb ratings
  - This multi-source validation ensures we're measuring rating inflation accurately against independent benchmarks

- **Statistical Quantification**: Calculated systematic rating differences and normalized scores across platforms to detect and quantify any remaining bias

**Key Technical Features:**
- Data cleaning and feature engineering (extracting release years, normalizing scales)
- Comparative statistical analysis between rating systems
- Temporal comparison to isolate the impact of Fandango's stated corrections
- Normalization

### **Business Impact**

This analysis provides:
1. **Transparency Verification**: Determines whether Fandango honored its commitment to fix rating bias
2. **Platform Credibility Assessment**: Evaluates the trustworthiness of rating systems that consumers rely upon for purchasing decisions
3. **Evidence-Based Insights**: Delivers quantified evidence that can inform consumer protection discussions and platform accountability

The findings have implications for:
- Consumer trust in digital rating platforms
- Platform governance and transparency practices
- Market competitiveness among rating aggregators
- Data integrity standards in the entertainment industry

### **Technical Stack**

- **Python**: 
- **Pandas**: Data manipulation and analysis
- **Matplotlib**: Data visualization
- **Jupyter Notebook**: Interactive analysis and documentation

---
