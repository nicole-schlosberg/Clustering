# Clustering

Two data files are included in this repo, *engagement-data.csv* represents weekly engagement with the online course for each student. It contains the following variables:

* **id** - student id number
* **modality** - the modality the student was engaging with the platform:  
  * logins - how many times a student logged in that week  
  * video - how many minutes of course videos the student watched that week  
  * forum - how many forum posts the student made that week  
  * game - how many levels of an educational game the student completed that week  
* **measure** - the numerical measure corresponding to the modality (IE - log ins, minutes, posts, levels)  

*student-level.csv* represents student characteristics including assessment results for the students

* **id** - student id number
* **assignment (1-5)** - scores on class assignments (0-100)
* **quiz (1-5)** - score on quizes (0-20)  
* **exam** - score on final exam (0-100)
* **gender** - student self identified gender (a, b, c, d)
* **parent.ed** - highest level of education of parent/guardian
* **race.eth** - student self identified race/ethnicity
* **free-lunch** - whether or not student recieves a free school meal
    
