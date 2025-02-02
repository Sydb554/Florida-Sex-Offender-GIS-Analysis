# Florida-Sex-Offender-GIS-Analysis
Personal Project: Geospatial analysis of 78,000+ Florida sex offender records using Python and QGIS. Identified _____+ potential violations of 1,000-foot legal restriction

### Project Overview:
***
This project involved a comprehensive analysis of over 78,000 records of registered sex offenders in Florida, using geospatial analysis. The objectives were to clean and validate data inconsistencies, assess compliance with legal proximity restrictions, and create effective visualizations of geographic data. The analysis was performed using Python for data cleaning and validation, and both QGIS and Python were utilized for geospatial analysis to ensure accurate findings. This was a personal project that I pursued due to passion for keeping victims of sex crimes safe. 

### Objectives:
*** 
* Data Cleaning and Validation: Employ Python libraries (Pandas and NumPy) to analyze and rectify discrepancies in sex offender records, enhancing data reliability.
* Geospatial Analysis: Utilize QGIS and Python to perform dual analyses on compliance with the 1,000-foot legal restrictions around protected areas, identifying potential violations and cross-validating results.
* Data Visualization: Developed infographic visualizations using Matplotlib and Seaborn to effectively communicate complex geographical data insights. This visualization was crucial in mapping the locations of non-compliant offenders.

### Specific Data Inclusions:
*** 
* Public Parks: Focus on registered parks in Florida with playgrounds, sourced from official state and local government resources.
* Other Protected Areas: Included schools and daycare facilities identified through government databases and direct queries to local authorities.

### Clarifications:
***
* Scope of Data: Analysis was strictly limited to the permanent addresses of registered sex offenders.
* State Laws: While some counties or cities have their own laws for sex offenders regarding distances, the state law states 1,000 ft (measured in a straight line from the offender's residence to the nearest boundary of the prohibited place).
* GitHub Code: The code on this page is only the Python scripts used for collecting, cleaning, and checking the data, and doesn't include the mapping visuals or the results from QGIS.

### Conclusions:
*** 
* Key Findings: Over ______ potential compliance violations were identified, with data validation through Python and QGIS reinforcing the reliability of the findings.
* Implications for Policy and Enforcement: Highlights the need for enhanced monitoring and enforcement of legal restrictions, offering a methodological approach that can be adapted for broader public safety applications.
* Outcomes: In December 2024, counties and cities with sex offenders violating the 1,000 ft rule were contacted. They were alerted about the violators, their violating addresses, and the nearby school, public park, or childcare center within 1,000 feet. This outreach was facilitated by a script I wrote to find contact info and automate sending the emails.
