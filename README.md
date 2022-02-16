# dimensional-reduction
Biology is evermore dependent on high-dimensional data. In this context, it can be challenging to evaluate and explore how this dimension reduction is used to extract information, help with data visualization and provide better models. In this hands-on tutorial, we will use dimensional reduction techniques (PCA, ICA, Multidimensional Scaling, t-sne, and U-MAP) in data to see how they behave. Our goal is to provide students an overview of some frameworks that can be used in R to do, thus harvesting R's power. First,  students will use the tidy verse and tidy model frameworks to learn PCA and ICA. Secondly, they use other packages to learn Multidimensional Scaling. Thirdly, we will see how this field is still growing rapidly and how we can use reticulate to execute programs and code that has been written in python in R. We will then, use reticulate together with scikit-learn to do t-sne and U-Map from R. Lastly, students will discuss what they have learned and their main takeaways from the tutorial.
### Requirements

This tutorial is aimed at people who already have some familiarity with R (they should be able to import data, be familiar with some data frame manipulations) that come from a biological background or are interested in applying this in a biological context. However, familiarity with data analysis in OMICs data or ecology is not required. Neither is knowledge of the packages themselves nor python. Ideally, the person should just be motivated to learn how to compare and implement different types of dimensional reduction methods.


### Outline

Section 1: 
-Introduction (Slides)
-Explaining motivation behind dimensionality reduction (Slides)
-Examples from MultiOmics Data and Ecology (Slides)
-Theoretical overview of methodologies:
    -Principal component Analysis
    -Multidimensional scaling
    -Independent Component Analysis (ICA)
    -t-SNE
    -U-MAP
-  Jeopardy-like pooling for questions regarding methods (Slides - game playing)
- Importing data to R (Slides and coding) 
- Exploring data frame values (Slides and coding)
- Opening for more questions and student’s progress (No slides, just chatting)+

--- Fist break (10 minutes) ---

Section 2:
- Introduction to tidy models and usage of recipes for PCA and Independent Component Analysis (Slides)
- Building recipes for PCA (I will “live code” this recipe together with students to show them how a recipe work, and show them how they can find help if they are lost in how to do something)
- Building recipes - students (from the documentation and the links provided, students will try to bring their own recipe for ICA, students will have  time to try to this for themselves before we move on with check-ins and questions)
- Check-in and discussion from questions 
--- Second break  (10 minutes) --- 

Section three:
- Multidimensional scaling in R using other packages (Slides, showing some code, non-tidy verse)
- Writing a script for Multidimensional scaling with students (I write this code together with the students to see how they can use the docs to code with themselves before showing the answer)
- Students try Multidimensional scaling with other distances (students will have a time to try to this for themselves before we move on with check-ins and questions)
- Check-in and discussion from questions (pool to see how the students are feeling, is the rhythm okay?)
-- Third break (10 minutes)--

Section four:
--Introduction to new methodology: examples from recent research developments in the field (PHATE, autoenconders). (Slides)
- What if some method I am interested in was developed in python? 
- Introduction to reticulated (Slides)
- Introduction to how we can use scikit learn in python (Slides)
- Showing the docs and coding for the t-sne in python (I will be showing how to code for this)
- Coding for U-MAP with students (Collaborative coding, students will give me suggestions on how to code with this while we are working on this together).  
- Check-in with student's progress and question
- Wrapping up - Collaborative takeaways from this tutorial (Slides, polling)
