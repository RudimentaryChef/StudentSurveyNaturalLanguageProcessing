# StudentSurveyNaturalLanguageProcessing
As of 12/08/23 This is my current project
**Repository and File Information**
- NLP_Courses.ipynb: The current code base for all Python code regarding cleaning data and model

- TestData.csv: Sample Data. Due to FERPA, I can not publish real student data/survey that we will train the model on. To this end, I have used chatGPT to generate data to train my model for this demo.
  
- ReadME.MD: This file 
  
- .ipynb_checkpoints: Ignore this, these are just some checkpoints for my Jupyter Notebook file
  
**Project Story**

- Large online courses have surveys that instructors need to manually sort through which may take hours of time, and for certain MOOCs may be borderline impossible
  
- Dr. Mayer, a professor I have researched with and my former Linear Algebra and Multivariable Calculus professor brought this problem up with me.
  
- To reduce instructor effort in large courses, this project serves to categorize survey responses using machine learning and then automate the appropriate instructor action (send an email with a response to the FAQ) or flag certain responses that require instructor attention.
  
- I am working with Dr. Mayer on this project 

**Important Dates**

- 10/31/23: First Sprint Deadline (Minimum Viable Product) ✅

- 11/6/23: Proposal Deadline ✅

- 4/15/23 -> 4/16/23: University System of Georgia Education Conference 🔵


**Current Progress**

- Sprint 1 complete, basic three-pronged classifier created with tensor flow.
  No major issues were detected in testing.
  
- Sprint 2 complete, 4-pronged classifier that combines various flows.
  Sprint 2 issues: The model has been overfitted due to majority of data being NC it started categorizing every response as NC. 
  Possible Options to fix the problem in Sprint 2 (model categorizes everything as no concern due to a large amount of no concern within the data set):

    1. Organically make my data better by adding more options that have concerns and less options that are "no concern" (This would be the best for JUST this problem BUT LACKS Generalization)
    2. Data Augmentation (maybe just cloning?) (I think this might be the best option right now as far as long term expansion goes)
    3. Changing to semi supervised learning (Not enough data)
    4. Convert to a model that uses transfer learning instead (Need to look into this more)
       
- Sprint 3 complete, Back Translation Augmentation Attempt:
    Sprint 3 issues: Major Roadblock. Google Translate API is extremely slow and unreliable. An alternative solution needs to be found.

- Sprint 4 Ongoing, Alternate Data Augmentation Method using Open AI API. 
    Important Resource: [https://cookbook.openai.com/examples/how_to_handle_rate_limits](url)
  
    
