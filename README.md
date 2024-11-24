# JobConnect

JobConnect is a job-seeking platform designed for seekers and Talent Acquisition Managers of companies to facilitate recruitment of deserving candidates.

---

## Project Description

JobConnect enables the following functionalities:

- **For Job Seekers**: 
  - Enter your details and constraints to view recommended job opportunities along with a recommendation percentage calculated using machine learning algorithms.
  - Apply for desired jobs directly through the platform without requiring third-party software.

- **For Talent Acquisition Managers**: 
  - Provide job details and constraints to view recommended job seekers with their respective recommendation percentages.
  - Manage applications by accepting or rejecting them.

The platform streamlines the job application and hiring process with automated recommendations and application tracking.

---

## Installation Guide

### Steps to Compile:
1. Open your terminal and navigate to the directory where the application files are stored using the `cd` command.
2. Compile the C files using one of the following commands:
   - `make`
   - `gcc main.c seeker.c company.c recommend_jobs.c recommend_seekers.c ScoreCalculation/score.c applications.c validation.c sha256.c -o app`

### Steps to Run:
1. After successful compilation, execute the application using:
   ```bash
   ./app
   ```

> **Note**: Ensure that you are in the correct directory before compiling or running the application.

---

## How to Use the Application

1. **Registration and Login**:
   - Create a new account as either a job seeker or a talent acquisition manager by providing the required details.
   - Login using your credentials to access your dashboard.

2. **For Job Seekers**:
   - View recommended jobs along with their recommendation percentages.
   - Apply for desired job positions directly through the platform.

3. **For Talent Acquisition Managers**:
   - View recommended job seekers with their respective recommendation percentages.
   - Manage applications by accepting or rejecting them.

4. **Notifications**:
   - Job seekers are notified of their application status when they log in.
   - Talent acquisition managers are notified of new applications upon login.

---

## Important Notes

- Do not edit or modify any files, especially the `.dat` files in the directory, to avoid issues with application functionality.

---

## Authors

- **Shaun Allan. H** (3122 22 5001 127)  
- **Saisandeep Sangeetham** (3122 22 5001 119)  
- **Shreyamanisha C. Vinay** (3122 22 5001 130)  

---

## License

This project is developed for educational purposes and is subject to modification or redistribution under proper guidance.
```

This README file is properly formatted and ready for inclusion in your GitHub repository. It outlines the project description, installation steps, usage instructions, and author credits.
