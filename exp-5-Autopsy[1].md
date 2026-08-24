# Experiment-5: Use Autopsy to Create a Case and Import Evidence

**Course / Lab:** Digital Forensics Lab  
**Experiment No.:** 5  
**Title:** Use Autopsy to Create a Case and Import Evidence  


---

## Aim
To analyze a forensic disk image using Autopsy and extract digital evidence.

---

## Requirements
- Autopsy (installed on Windows, Linux, or macOS)  
- Forensic disk image or data source to analyze  

---

## Description
Autopsy is an open-source digital forensics platform used for analyzing and extracting data from digital devices.  
It provides modules for file system analysis, keyword search, timeline visualization, hash analysis, and reporting.  
This experiment demonstrates how to create a case, import evidence, analyze data, and generate reports using Autopsy.  

---

## Procedure — Steps to Analyze Evidence Using Autopsy

**Step-1: Installation**  
- Download and install Autopsy from the official website.  
- Follow installation instructions based on your operating system (Windows, Linux, or macOS).  


**Step-2: Starting a New Case**  
- Create a new case by clicking on **New Case**.  
- Enter the case name and location where case data will be stored.  
- Fill in details such as case number, examiner’s name, etc., and click **Next**.


![(images/exp5-step2.png)](https://github.com/baddiputi/Digital-Forensic-Lab-Exercises/blob/f90da30830306f35655735d52eb562bfd33a352f/images/WhatsApp%20Image%202025-09-01%20at%2012.29.59.jpeg)

**Step-3: Enter Case Details**  
- Enter the case name and location where the case data will be stored. Fill in the details like the case number, examiner's name, etc., and click Next.

![(images/exp5-step2.png)](https://github.com/baddiputi/Digital-Forensic-Lab-Exercises/blob/f90da30830306f35655735d52eb562bfd33a352f/images/WhatsApp%20Image%202025-09-01%20at%2012.30.16.jpeg)

**Step-4: Adding a Data Source**  
- Choose the type of data source.  
- Select the data source (e.g., disk image, local drive, logical files).  
- Configure **Ingest Modules** (to analyze files, search keywords, extract metadata, etc.).  
- Start the analysis.

![(images/exp5-step3.png)](https://github.com/baddiputi/Digital-Forensic-Lab-Exercises/blob/f90da30830306f35655735d52eb562bfd33a352f/images/WhatsApp%20Image%202025-09-01%20at%2012.31.16.jpeg)

**Step-5: Initial Analysis and Overview**  
- Monitor **Ingest Progress**.  
- Explore the resulting artifacts.  
- Use the Tree Viewer to navigate evidence categories.  
![(images/exp5-step5.png)](https://github.com/baddiputi/Digital-Forensic-Lab-Exercises/blob/f90da30830306f35655735d52eb562bfd33a352f/images/WhatsApp%20Image%202025-09-01%20at%2012.31.26.jpeg)

**Step-6: Detailed Analysis**  
- **Keyword Search:**  
  - Perform searches using the Keyword Search module.  
  - Use pre-configured lists or enter custom keywords.  
- **File Analysis:**  
  - Navigate files and folders under File Types or File System.  
  - Open, view, or export files for further examination.  
- **Timeline Analysis:**  
  - Use the Timeline module to visualize events by timestamps.  
  - Helps track user activity over time.  
- **Hash Analysis:**  
  - Compare file hashes against known databases to identify known good/bad files.

![(images/exp5-step6.png)](https://github.com/baddiputi/Digital-Forensic-Lab-Exercises/blob/f90da30830306f35655735d52eb562bfd33a352f/images/WhatsApp%20Image%202025-09-01%20at%2012.31.37.jpeg)

**Step-7: Reporting**  
- Generate a report by selecting **Generate Report** from the toolbar.  
- Choose report type (HTML, CSV, Excel, etc.).  
- Select which analysis results to include.  
- Export findings: export individual files or artifacts for reporting or further analysis.  
- Final Review: check that the report includes all relevant details.  
- Save or print the report for case documentation.  

![(images/exp5-step6.png)](https://github.com/baddiputi/Digital-Forensic-Lab-Exercises/blob/f90da30830306f35655735d52eb562bfd33a352f/images/WhatsApp%20Image%202025-09-01%20at%2012.31.52.jpeg)

- Report Generation Progress

![(images/exp5-step6.png)](https://github.com/baddiputi/Digital-Forensic-Lab-Exercises/blob/f90da30830306f35655735d52eb562bfd33a352f/images/WhatsApp%20Image%202025-09-01%20at%2012.32.03.jpeg)

- Reports

![(images/exp5-step6.png)](https://github.com/baddiputi/Digital-Forensic-Lab-Exercises/blob/f90da30830306f35655735d52eb562bfd33a352f/images/WhatsApp%20Image%202025-09-01%20at%2012.32.15.jpeg)

- Text in the report

![(images/exp5-step6.png)](https://github.com/baddiputi/Digital-Forensic-Lab-Exercises/blob/f90da30830306f35655735d52eb562bfd33a352f/images/WhatsApp%20Image%202025-09-01%20at%2012.32.38.jpeg)

**Step-7: Case Closure**  
- Close the case once the investigation is complete.  
- Archive all data and reports according to organizational policies.  

---

## Result

The experiment successfully demonstrated the use of Autopsy for creating a case, importing evidence, analyzing digital artifacts, and generating reports, thereby validating its effectiveness as a digital forensic investigation tool.

---
