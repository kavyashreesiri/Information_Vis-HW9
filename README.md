1. __Introduction__
The H-1B is an employment-based, non-immigrant visa category for temporary foreign workers in the United States.    For a foreign national to apply for H1-B visa, an US employer must offer a job and petition for H-1B visa with the US immigration department. This is the most common visa status applied for and held by international students once they complete college/ higher education (Masters, PhD) and work in a full-time position.   



__Data__  
*Dataset Source*   
        The Office of Foreign Labor Certification (OFLC) generates program data that is useful information about the immigration programs including the H1-B visa. The disclosure data updated annually is available at https://www.foreignlaborcert.doleta.gov/performancedata.cfm   
* __Data Attributes__   
These are the attributes that are relevant to my analysis and were obtained after processing the original dataset.  
    * Case Status: This Describes the Details about status of an applicant after LCA processing, whether he/she is eligible for applying to H-1B.  
      Typically there are four values for this attribute:   
      Type: Categorical data      
        * Certified: This means that the application is processed by LCA and is eligible for filing a petition at USCIS for H1-B. 
        * Certified withdrawn: This status means that the application was processed by LCA and is certified for applying to H-1B but is withdrawn by the company or individual, typically there are very less cases pertaining to this case. 
        * Rejected: This means that the application is rejected by LCA for filing H-1B at USCIS.  
        * Withdrawn: This status means that the application is not processed by LCA and is withdrawn by the individual. 
    * Employer Name: This field denotes the Name of the employer who applies for H-1B on behalf of the employee.    
      Type: Categorical Data   
    * SOC Name: Based on Standard Occupational Classification systems code, a name is given to the category of job application.    
      Type: Categorical Data    
    * Job Title: Employees job title specific to company.   
      Type: Categorical Data 
    * Full Time Position: Y or N is assigned based on employees work status, either full time or part time.   
      Type: Categorical Data 
    * Prevailing Wage: Average salary for particular position in USD paid by the employer to its employee at the time of application.    
      Type: Quantitative Data 
    * Year: Visa petition is filed in this year.    
      Type: Quantitative Data 
    *  Worksite: Employers communication address with city and state as its value.    
      Type: Categorical/Ordered 
    * LAT: latitude location co-ordinate of Worksite.      
      Type: Quantitative Data 
    * LON: longitude location co-ordinate of the Worksite.    
      Type: Quantitative Data   
__Visualization__
* Description:  


* Interactive elements you employed:  
        * Tooltip  
        * Zoom in and Zoom out

* Narrative storytelling elements  


* Address how the visualization answers the questions you raised in the Introduction  
 
 
__Design decisions__
 choice of visualization type, size, color, scale, and other visual elements, as well as the use of sorting or other data transformations  
 
__Development Process__
* a commentary on the development process  

* Roughly how much time did you spend developing your application?  
*  aspects took the most time?   

__References__   
http://maptimeboston.github.io/d3-maptime/  
https://bl.ocks.org/mbostock/3885705  
https://github.com/maptimeBoston/d3-maptime  
https://www.congress.gov/bill/115th-congress/senate-bill/180   
https://www.congress.gov/bill/115th-congress/house-bill/170  
https://redbus2us.com/h1b-visa-bills-latest-news-updates-reforms-passed-status-tracker/  
http://dimplejs.org/advanced_examples_index.html  
http://christopheviau.com/d3list/   


