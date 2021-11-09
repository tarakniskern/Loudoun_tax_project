# Loudoun_tax_project
scraping publicly available tax and assessment data to evaluate real estate tax equity
This project is still actively being worked on.
 
 A comprehensive list of jupyter notebooks that were used in the project
 11/8/2021
 
JupyterLab Notebook files list:

Getting the data and cleaning:

selenium_loudoun_parcel.ipynb
	get parcel data
	
selenium_loudoun_loop.ipynb
	get tax payment data
	
Clean_Loudoun_taxdata.ipynb
	clean the tax payment data
	
QC_Loudoun_taxdata.ipynb
	#check the quality of the tax payment data

Loudoun_assessment_loop3.ipynb
	get property assessment data

Data exploration and analysis:
Loudoun_taxdata_numerical_explore.ipynb

Based on articles such as https://www.nytimes.com/2021/04/03/opinion/sunday/property-taxes-housing-assessment-inequality.html, 
there appears to be systemic undervaluation of expensive properties and overvaluation of smaller properties. In some areas
of the US, the areas of overvaluation also have higher populations of POC.  Loudoun County, VA is one of the wealthiest counties in 
the US, has a highly educated and relatively young population. It is also a county that has seen large demographic changes over the last 
20 years. 
The project consists of 
  1) data scraping
  2) data cleaning
  3) data validation
  4) basic statistics and exploration adapting code from "Practical Statistics for Data Scientists, 2nd edition" Peter Bruce, Andrew Bruce, and Peter Gedeck
  5) evaluation and visualization
