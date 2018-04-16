1. __Introduction__  
The H-1B is an employment-based, non-immigrant visa category for temporary foreign workers in the United States.    For a foreign national to apply for H1-B visa, an US employer must offer a job and petition for H-1B visa with the US immigration department. This is the most common visa status applied for and held by international students once they complete college/ higher education (Masters, PhD) and work in a full-time position.   
  * Motivation   
    The main motivation behind considering this dataset is the fact that most of the strength are international students and I wanted to let them know what are the statistics of H-1B visas for a particular Industry and particular job type. Following the Recent Presidential Elections, there has been a lot of chaos in the United States about the H1-B visas and skilled immigrants, this was also a contributing factor in making us think about this dataset.   
  * Questions  
    My goal was to understand favourable conditions to obtain a H-1B Visa employment.
    So, I have aggregated few other data sets that helped me understand the growth in H-1B visa petitions,Salary range with respect to state,education qulaification,Job positions,States with more number of H1-B visa.  
2. __Data__  
  * *Dataset Source*   
        The Office of Foreign Labor Certification (OFLC) generates program data that is useful information about the immigration programs including the H1-B visa. The disclosure data updated annually is available at https://www.foreignlaborcert.doleta.gov/performancedata.cfm   
  * *Additional dataset*   
        This data set provides information about the hiring practices of employers who petition for foreign national workersand it is made available by U.S Citizenship and Immigratio services Department.It has data from 2007-2017 which I have used to understand the growth in Recieved and Approved H-1B Petition Flings over years.  Data is available at : https://www.uscis.gov/tools/reports-studies/immigration-forms-data  
        One more data set considered i stheh Population in each state of United States.
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
3. __Visualization__
   * Description:  
     Through the implementation of visualizatioons, I am trying to figure out various parameters that are very important to be able to get H-1B Visa or to be more likely to obtain H-1B Visa.
     There are 5 visulaizations that help the user to underastand the factors that will help in understanding favourable conditions to obtain H-1B visa.
    * Visulaization 1-   
    __Line Chart:Approved H-1B petition Vs recieved H-1b Petition applications.__  
      Approvals are the numberof H-1B visa got approved by the Governmant  
      Receipts are the number of H-1B Appplications recived in the duration  
      Analysis:In the year 2017,due to the changes made in the Employment eligibility rule,the approved H1-B visa number decreased.  
      So,now we know that H1-B visa count had been increasing consistently,we can now get into further details of factors.    
      Story telling elements: Annotation of trends.
    * Visualization 2-  
    __Line Chart:Shows the trend in Approved H-1B applications count based on educational qualifications.__  
    Analysis:Increase in Master's degree after 2016 is because of the Employment eligibility rule, whihc has reservation of 20,000 for those who studied in Master's or bachelor's in US.
    Applicants with higher educational qualifications have more chances to obtain H1-B.
* Interactive elements you employed:  
        * Tooltip  
        * Zoom in and Zoom out
        * Highlighting

   * Narrative storytelling elements  


   * Address how the visualization answers the questions you raised in the Introduction  
 
 
4. __Design decisions__
 Choice of visualization type, size, color, scale, and other visual elements, as well as the use of sorting or other data transformations  
 
5. __Development Process__
  * The development process  
    The whole process of implenting and learning was exciting and interesting.Went through few tutorilas to get basics strong.Especially the GeoJSON map of United States and binding data to Map took a lot of time.Understanding the difference betwen TopoJSON,GeoJSON,Leaflet and how they work consumed a lot of time. 
    I had a huge CSV file which has more than 2.5 million records and GeoJSON which togetehr take a lot of time to load.It was difficult to implement changes and check.
    I have spent 8-9 hours all the three weeks to learn about different interactive tools and techniques.
    I got to know about many good sources and interactive visualization tools available.D3 community sources awere really helpful.
 

__References__   
http://maptimeboston.github.io/d3-maptime/  
https://bl.ocks.org/mbostock/3885705  
https://github.com/maptimeBoston/d3-maptime  

https://www.congress.gov/bill/115th-congress/senate-bill/180   
https://www.congress.gov/bill/115th-congress/house-bill/170  
https://redbus2us.com/h1b-visa-bills-latest-news-updates-reforms-passed-status-tracker/  

http://dimplejs.org/advanced_examples_index.html  
http://christopheviau.com/d3list/   
http://bl.ocks.org/mgold/6a32cec6380b6ce75c1e  
https://onlinehelp.tableau.com/  

Data sources  
Main Dataset-  
https://www.census.gov/data/tables/2016/demo/popest/state-total.html  
Additional datasets-   
https://www.uscis.gov/tools/reports-studies/reports-and-studies  
https://www.foreignlaborcert.doleta.gov/performancedata.cfm  
https://www.uscis.gov/tools/reports-studies/immigration-forms-data


