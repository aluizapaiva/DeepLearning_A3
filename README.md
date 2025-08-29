# Job Fraud Detection System for Jiving Jobs

## Project Overview
This project develops ML fraud detection system for 'Jiving Jobs' to help identify fake job listings using natural language processing and artificial neural networks. The solution protects job seekers from fraudulent postings while reducing manual validation workload for the platform.

## Business Context
**Problem**: Fraudulent job listings damage platform reputation and waste applicants' time:
- Nearly 5% of job listings are fraudulent (1 in 20 applications leads nowhere)
- Current detection methods either miss sophisticated scams or flag legitimate posts
- Manual validation of all listings isn't practically feasible
- Fraud erodes user trust and platform credibility

**Solution**: A hybrid machine learning system that analyzes both company data and language patterns to detect fraud with 75% accuracy, enabling automatic flagging for manual review.

## Technical Approach

### Model Architecture
- **Primary Model**: Artificial Neural Network (ANN) with text processing capabilities
- **Task Type**: Binary classification (fraudulent vs. legitimate job posting)
- **Input**: Job descriptions and posting metadata
- **Output**: Fraud probability score and recommendation for manual review

### Dataset
- **Source**: Manually validated job listings (job_listings.csv)
- **Size**: 18,000+ job postings
- **Features**: Job descriptions, company information, posting details
- **Target Variable**: Fraudulent flag (binary)

### Performance Results
- **Detection Accuracy**: 75% (catches 3 out of 4 fraudulent posts)
- **Processing Speed**: Real-time analysis of new postings
- **False Positive Rate**: Minimized to protect legitimate employers
- **Platform Impact**: Automated screening reduces manual review by 80%

## Repository Structure
```
job-fraud-detection/
├── job_fraud_analysis.ipynb        # Main technical notebook
├── management_report.pdf           # Executive summary for Jiving Jobs management
├── data/                          # Dataset files
│   └── job_listings.csv
├── models/                        # Saved model files
├── results/                       # Performance metrics and fraud pattern analysis
└── README.md                      # This file
```

## Key Fraud Detection Insights
- **Language Patterns**: Fraudulent posts often use "urgent hiring" combined with vague job duties
- **Company Information**: Legitimate posts have consistent company data and clear contact details
- **Hybrid Approach**: Combining company verification with text analysis outperforms single methods
- **Behavioral Economics**: Trust-building reduces user churn and increases legitimate employer engagement

## Strategic Impact
- **User Protection**: Automatic fraud screening improves platform safety
- **Operational Efficiency**: Reduces manual review workload by 80%
- **Trust Building**: Creates "safe by default" user experience
- **Legal Risk Reduction**: Proactive fraud prevention minimizes platform liability
- **Competitive Advantage**: Superior fraud detection vs. other job platforms

## Technologies Used
- **Python**: Primary programming language
- **ANN Architecture**: Text-processing neural networks for classification
- **Natural Language Processing**: Analysis of job description patterns
- **Text Analytics**: Feature extraction from job posting content
- **Google Colab**: Development and training environment

## Model Comparison Results
| Approach | Detection Rate | Key Strength | Limitation |
|----------|---------------|--------------|------------|
| Company Data Only | 65% | High precision | Misses sophisticated fraud |
| Text Analysis Only | 68% | Catches language patterns | High false positives |
| Hybrid Model | 75% | Best of both approaches | Requires more data |

## Installation & Usage
1. Clone this repository
2. Install required dependencies: `pip install tensorflow pandas numpy matplotlib seaborn scikit-learn nltk`
3. Open `job_fraud_analysis.ipynb` in Jupyter or Google Colab
4. Follow the notebook cells for model training and evaluation

## Reports Included
- **Management Report**: Business-focused analysis for platform management and fraud team
- **Technical Report**: Detailed Jupyter notebook with complete NLP methodology and code

## Academic Context
**Course**: DTSC301 - Deep Learning Through Neural Networks  
**Institution**: Bond University  
**Assessment**: Written Report 3 (30% weighting)  
**Focus**: Real-world application of ANNs in fraud detection and natural language processing

## Implementation Strategy
1. **Technical Deployment**: 4-6 weeks integration and testing
2. **Human Integration**: Automated routine screening, manual review for flagged posts
3. **Resource Requirements**: 1 ML engineer + 1 senior reviewer for deployment
4. **Performance Monitoring**: Continuous tracking of detection rates and false positives

## Ethical Considerations
- **Transparency**: Clear communication about automated screening to employers
- **Fairness**: Regular bias testing to ensure equal treatment of all job categories
- **Privacy**: Secure handling of company and applicant data
- **Human Oversight**: Final fraud determination remains with human reviewers

## Business Benefits
- **24/7 Operation**: Continuous fraud monitoring without human resource constraints
- **Cost Efficiency**: Reduces manual review costs while improving detection
- **User Experience**: Creates safer job search environment
- **Platform Growth**: Higher trust leads to increased user engagement and employer adoption

## Contact
Ana Luiza Lerch Paiva  
Data Analyst Student, Bond University  
GitHub: @aluizapaiva

---
*This project demonstrates the application of neural networks and natural language processing to combat online fraud and protect digital platform users.*
