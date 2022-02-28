# MyAnimeList Prediction and White/Red Wine classification
![plot](https://github.com/TamirIsCool/DataScIntro/blob/main/photos/mal_pic.PNG)
![plot](https://github.com/TamirIsCool/DataScIntro/blob/main/photos/mal_dead.PNG)
Some funny pictures we took during our work on the project. <br> On the left side you can see how MyAnimeList.net blocked us due to excessive requests. <br> And on the right side you can our scraping program taking 500+ minutes to scrape.
## We would firstly like to say thanks, to Roi and Idan for all their help and useful information during the semester and for this opportunity to do a fun project instead of a simple exam.
# The project is divided into 3 parts.
## Simple math/programming questions (Individually done)
### Not much to collaborate here.
## Prediction of the popularity of anime shows on the site MyAnimelist.net
### This was defiently the most we had in the project. <br> Although we haven't reached steller results like we would have liked, we still got a much better result than what the dummies were predicting and we are very happy with it considering the large amount of animes and small amount of data we collected from the website. <br> Collecting the information from the website was quite simply put, a pain in the butt. From long scraping times to random blocks and simple programming errors it took us quite a while before we had usable information in-hand. <br> However once we got the information we needed we got straight to work using regresors like KNN/DecisionTree and Linear Regression.<br>More information can be found inside the files in the regression folder.
## Classification using a dataset from kaggle, in which we classify if a wine sample is from white wine or red wine.
![plot](https://github.com/TamirIsCool/DataScIntro/blob/main/photos/red_wine.PNG)
![plot](https://github.com/TamirIsCool/DataScIntro/blob/main/photos/White_Wine.PNG)
### We decided to do a little twist to the kaggle dataset question, and instead of answering the question inside the kaggle's dataset link<br>We noticed that the same person had posted 2 different yet similar datasets regarding 2 types of wine. So we decided that we will make a classification question ourselves and it will be to classify what wine is red and what wine is white using the data given to us from both CSV datasets.<br> Mid-answering we noticed the datasets were also unbalanced so we had to also solve that problem.<br>After we finished the question and had 3 classification models (KNN/Random Forest and Logistic Regression) we ended up with a 99%! accuracy in our classifications.
