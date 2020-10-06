# TaxonomyService
This taxonomy service is a framework to standardize the taxonomy used by HR or different ATSes. 

#Introduction
Taxonomy service is .net core api project which has endpoint that returns taxonomy items based on specified category. 
Various taxonomy lists for different languages are defined via JSON files.

#Swagger 
Use Swagger link to test this api  : /swagger/index.html

#End Point : /v1/Taxonomy
Parameter are taxonomy item type and ui culture which can be supplied via query string 

Valid values for taxonomy items
JobFunctionArea = 1,
EmploymentType = 2,
ExperienceLevel = 3,
Location = 4

Valid values for ui culture are 2 letter ui culture values
en,
no,
da,
sv  etc.


