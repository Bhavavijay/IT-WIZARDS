## Skill Navigator Application
**Project Overview**
The Skill Navigator Application is designed to streamline the training program process by collecting essential candidate details, facilitating batch allocation, tracking training progress, and generating detailed reports. The application aims to enhance the efficiency and effectiveness of training programs through automated batch assignments, progress tracking, and insightful reporting.
**Work Flow Design Using Figma:**
The views of Skill Navigator Application using Figma are uploaded in a Desktop View Link.
Desktop View:
https://www.figma.com/proto/CKIPj5BFRzTOmKpEC02Jax/SKILL?node-id=49-22&node-type=FRAME&t=T0N3JGgC8nC0ROJ7-0&scaling=scale-down&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=49%3A22

---


**Features**
**1. Candidate Information Collection:**
Collects candidate details including Name, Email ID, Degree, Specialization, Phone Number, Certifications, Internship Details, Completed Courses, LinkedIn Profile, GitHub Profile, and Programming Languages Known.
Options to upload eCertificates for Certifications, Internships, and Completed Courses.
**2. Batch Allocation Criteria:**
Java Batch: Candidates with AWS certification or any Java certification.
.NET Batch: Candidates with Azure certification or any .NET certification.
Data Engineering Batch: Candidates with Python certification.
Batch Sizes: Minimum of 25 candidates, Maximum of 30 candidates.
**3. Workflow**
Collect candidate details.
Process batch allocation based on specific criteria.
Track learning progress and generate reports.
**4. Training Progress Tracking**
Capture self-reported course completion percentages.
Record scores for Multiple-Choice Questions (MCQs).
Record scores for project evaluations.
**5. AI Recommendations**
Analyze candidate scores and recommend topics for further focus.
Provide personalized learning paths and improvement strategies.
**6. Feedback Collection**
Automate feedback collection post-topic completion.
Analyze feedback and generate actionable insights.
**7. Reports**
Individual Candidate Report: Detailed performance report including self-reported percentages, MCQ scores, project evaluations, AI recommendations, and feedback.
Trainers' Feedback Analysis Report: Aggregated feedback for trainers with insights and recommendations.
Batch-wise Score Card: Performance report for each batch including average scores, completion percentages, and comparative analysis.
College-wise Score Card: Performance comparison of candidates from different colleges.
Topper List: Identify top-performing candidates.
Batch Comparison Report: Compare performance across batches and provide recommendations.
**8. Analysis**
Performance trends, feedback analysis, comparison metrics, and success metrics to improve training programs.

---

## Technical Specification
# System Architecture

**Frontend**
Framework: React.js / Angular
Languages: JavaScript, HTML5, CSS3
UI Components: Material-UI / Bootstrap
Forms and Validation: Formik, Yup

**Backend**
Framework: Node.js with Express.js / Django (Python) / Spring Boot (Java)
Languages: JavaScript (Node.js) / Python (Django) / Java (Spring Boot)
Database: PostgreSQL / MySQL
ORM: Sequelize (Node.js) / Django ORM / Hibernate (Java)
Authentication: JWT (JSON Web Tokens) / OAuth2

**AI and Data Processing**
AI Frameworks: TensorFlow / PyTorch
Languages: Python
Data Processing: Pandas, NumPy
Machine Learning: Scikit-learn

**File Storage and Management**
Cloud Storage: AWS S3 / Google Cloud Storage / Azure Blob Storage
File Upload Handling: Multer (Node.js) / Django File Uploads / Spring Boot Multipart

**Feedback System**
Feedback Collection: Google Forms / Typeform Integration
Data Analysis: Python (NLP and sentiment analysis)

**Reporting and Visualization**
Reporting Tools: JasperReports / Apache POI (for Excel reports)
Visualization: D3.js / Chart.js
Export Formats: PDF, Excel

**Deployment**
Containerization: Docker
Orchestration: Kubernetes
CI/CD: Jenkins / GitHub Actions / GitLab CI
Hosting: AWS EC2 / Google Cloud Compute Engine / Azure VMs

**Security**
Encryption: TLS/SSL for data in transit, AES for data at rest
Authentication and Authorization: JWT / OAuth2 / Role-Based Access Control (RBAC)
Vulnerability Scanning: OWASP ZAP / Snyk

 ---
 
## Detailed Components ##

**Frontend:** Responsive UI, interactive forms, and admin dashboard.
**Backend:** RESTful API, batch allocation logic, training progress tracking.
**AI and Data Processing:** Recommendations and feedback analysis.
**File Storage and Management:** Secure file upload and scalable storage.
**Feedback System:** Automated feedback collection and sentiment analysis.
**Reporting and Visualization:** Automated report generation and data visualization.
**Deployment:** Docker, Kubernetes, CI/CD, and hosting solutions.
**Security:** Data encryption, authentication mechanisms, and access control.

## Implementation ##
**Data Collection:** Automated from submissions and feedback.
**Data Processing:** Aggregate, analyze, and visualize data.
**Reporting Tools:** Generate PDF and Excel reports.
**AI Analysis:** Implement recommendations and insights.
**Feedback Integration:** Continuously improve based on feedback.
