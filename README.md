# Smart Resume AI - Project Overview

### Key Features
- **Resume Analysis**: AI-powered resume scanning and evaluation
- **Resume Builder**: Smart resume creation with templates
- **Job Search**: Job recommendation and market insights
- **Analytics Dashboard**: Performance metrics and visualization
- **Learning Resources**: Curated courses and videos for career development

### 🚀 Technologies Used
- Frontend: Streamlit
- AI/ML: Resume parsing and analysis algorithms
- Database: SQLAlchemy
- Visualization: Plotly
- Document Processing: Resume text extraction and formatting libraries

### Key Technologies
- Frontend: Python with Streamlit
- AI/ML: Resume analysis algorithms
- Database: SQLAlchemy for database operations
- Visualization: Plotly for analytics and visualizations
- Document Processing: Libraries for parsing and handling various resume formats

### Project Structure Overview
```bash
├── app.py                # Main Streamlit application entry point
├── ui_components.py      # UI building blocks for the application

# Core Functionality Modules
├── dashboard/
│   ├── __init__.py       # Imports DashboardManager
│   └── dashboard.py      # Contains DashboardManager class (analytics)
├── jobs/
│   └── job_search.py     # Job search and market trends visualization
├── utils/
│   ├── resume_analyzer.py # AI-powered resume analysis
│   ├── resume_parser.py   # Resume text extraction and parsing
│   ├── resume_builder.py  # Resume document generation
│   ├── excel_manager.py   # Excel data management
│   └── database.py        # Database connection handling

# Configuration
├── config/
│   ├── job_roles.py       # Job roles and requirement definitions
│   └── courses.py         # Learning recommendations and courses

# Styling
├── style.css              # Custom CSS styling for the application

# Assets
├── robot.json             # Lottie animation data

# Feedback System
├── feedback/
│   ├── feedback.py        # Feedback management functionality
│   └── schema.sql         # Database schema for feedback tables
```
### Clone the repository:
```bash
git clone https://github.com/Aarnavanand/job-traking
cd smart-resume-ai
```
### Install dependencies:
```
pip install -r requirements.txt
```
### Run the application:
```
streamlit run app.py
```
Live: https://job-tracking-hackathon.streamlit.app/

📜 License
This project is licensed under the MIT License.
