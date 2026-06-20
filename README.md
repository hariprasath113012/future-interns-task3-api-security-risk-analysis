# API Security Risk Analysis

## Project Overview

This project was completed as part of the Future Interns Cyber Security Internship Program.

The objective of this project was to analyze a public API, inspect authentication requirements, review API responses and headers, identify potential security risks, classify risk severity, and provide remediation recommendations.

This task focused on practical API security assessment, risk analysis, security reporting, and understanding common API security concerns, which are essential skills for Security Analysts, SOC Analysts, and Application Security professionals.

## Objectives

- Analyze a public API endpoint
- Review authentication requirements
- Inspect API response data and headers
- Identify potential API security risks
- Classify risks based on severity levels
- Assess business impact
- Provide remediation recommendations
- Improve understanding of API security concepts

## Tools Used

- Insomnia
- JSONPlaceholder API
- Browser-Based API Inspection
- Microsoft Word
- PDF Documentation

## API Information

**API Name:** JSONPlaceholder

**API Endpoint:**
https://jsonplaceholder.typicode.com/posts

**Request Method:** GET

**Testing Tool:** Insomnia

## Security Risks Identified

### 1. No Authentication Required

**Severity:** Medium

The API endpoint can be accessed without requiring authentication, API keys, or user credentials. While acceptable for a public testing API, similar behavior in production environments could expose sensitive information to unauthorized users.

### 2. Open Data Exposure

**Severity:** Low

The API returns data directly to users accessing the endpoint. If sensitive business information were exposed in a similar manner, it could increase the risk of information disclosure.

### 3. No Visible Rate Limiting

**Severity:** Medium

No visible rate-limiting controls were observed during testing. Without rate limiting, excessive requests may impact service availability and increase the risk of abuse.

## Risk Classification

### Risk 1

**Risk:** No Authentication Required

**Severity:** Medium

### Risk 2

**Risk:** Open Data Exposure

**Severity:** Low

### Risk 3

**Risk:** No Visible Rate Limiting

**Severity:** Medium

## Business Impact

Weak API security controls may result in:

- Unauthorized access to information
- Information disclosure
- API abuse
- Service disruption
- Increased security risks

Organizations should regularly assess API security configurations to protect sensitive information and maintain service availability.

## Remediation Recommendations

- Implement authentication for sensitive API endpoints.
- Apply role-based access controls.
- Minimize unnecessary data exposure.
- Implement API rate limiting.
- Monitor API usage and access logs.
- Conduct regular API security assessments.
- Follow API security best practices.

## Project Structure

```text
future-interns-task3-api-security-risk-analysis
│
├── README.md
├── API_Security_Risk_Analysis_Report.pdf
│
└── evidence
    ├── 01_api_request.png
    └── 02_response_headers.png
```

## Evidence Included

The repository contains screenshots demonstrating:

### API Request and Response Data

<img width="1920" height="1080" alt="01_api_request" src="https://github.com/user-attachments/assets/dacedede-676a-4537-a81c-589b06ecffc0" />


### Response Headers Analysis

<img width="1920" height="1080" alt="02_response_headers" src="https://github.com/user-attachments/assets/3c77ceed-bc50-4510-82db-bade2d8d5b82" />


## Skills Demonstrated

- API Security Assessment
- API Risk Analysis
- Authentication Review
- Threat Identification
- Security Reporting
- Documentation and Evidence Collection
- Application Security Fundamentals
- Cybersecurity Fundamentals
- Blue Team Concepts
- SOC Analyst Fundamentals

## Learning Outcomes

Through this project, I gained practical experience in:

- Inspecting API requests and responses
- Reviewing API security controls
- Identifying security risks
- Understanding authentication concepts
- Assessing business impact
- Developing remediation recommendations
- Creating professional security reports
- Applying API security fundamentals

## Author

Hari Prasath R

Future Interns – Cyber Security Internship
