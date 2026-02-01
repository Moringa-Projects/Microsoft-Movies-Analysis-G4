## **MICROSOFT DEBUT STUDIO ANALYSIS** 

![microsoft image](https://github.com/user-attachments/assets/698df0d1-a48b-49d8-99e7-d8d270ca56c5)

### Overview
In this project, exploratory data analysis is applied to a movie industry dataset to provide data-driven insights for a business stakeholder. Microsoft plans to launch a new movie studio but lacks experience in film production. This analysis helps examine movie performances, audience reception, and genre trends across existing films to identify patterns associated with commercial success. The results aim to help Microsoft in decision-making about which types of movies to prioritize producing.

### Business Problem
Microsoft sees all the big companies creating original video content, and it wants to get in on the fun. Despite having no prior filmmaking experience, they made the decision to establish a new film studio. You are tasked with exploring which types of films are currently performing best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what types of films to create. 

### Objectives
*  Analyze movie industry data from multiple sources.

* Identify trends in movie performances.

* Determine key factors associated with high-grossing films.

*  Provide data-driven recommendations to Microsoft Studios.

### Key Business Questions
1.  Which factors should Microsoft prioritize when deciding what type of films to produce?

2.  How does production budget relate to box office performance?

3.  Do movies with higher ratings perform better financially?

4.  What characteristics are common among the highest-grossing films?

5.  Which movie genres generate the highest and lowest box office revenue?

6.  Which movie genres are being produced the most?

### Deliverables
*  Cleaned and enriched datasets from four sources(IMDb.title ratings, IMDb.title.basics,movie_gross, Tn.movie_budget).

*  Data visualizations illustrating the trend of movie genres, gross, and budget.

*  Features with the strongest positive and negative correlations.

*  A well-documented Jupyter notebook with data cleaning, exploratory data, visualizations, and interpretations.

### Final Goal
To provide Microsoft with data that will help them decide on what types of movies to produce to ensure their studio is both profitable and competitive.


## Findings:
In terms of the most produced movies, the drama and comedy do take a lead, although they did not take a lead in the well-rated categories as we'll see. On the contrary, sport and Documentary genres were the best rated. Microsoft is now presented 

with the decision on whether to choose what is most produced or best-rated categories. We shall investigate if the rating influences the money for us to make a data-driven decision.

<img width="533" height="425" alt="image" src="https://github.com/user-attachments/assets/e1494602-b5a7-432f-bafa-b5f9dd1852ea" />


<img width="458" height="338" alt="image" src="https://github.com/user-attachments/assets/7c785fcc-a2f4-401e-a9af-05ff1c730c91" />





To investigate how rating affects gross income, we first categorize rating into 3 i.e: Above Average, Average and Below Average. We then see the gross distribution across the categories.


<img width="779" height="215" alt="image" src="https://github.com/user-attachments/assets/cc2ae79a-86b5-4658-a140-6f1fa9a085bd" />

We now see that a high rating does not really mean the movie will gross highly. In fact it is the averagely rated movies that gross the highest while poorly rated movies gross more than highly rated. Therefore in terms of bringing back the money, rating is not a 

good indicator. We therefore choose the data-driven decision that the most produced movies as earlier seen are a better indication on what side of industry to venture into. Hence Drama genre is the most promising genre to venture into. It has a balance of both rating 

and profits.




Now let us have a look how the top studios have been performing over the years.

<img width="776" height="286" alt="image" src="https://github.com/user-attachments/assets/f125fd19-441d-47bb-bf3c-7ef8ff884bbf" />


Over the years, BV seems to have been leading the pack for the most part except for 2011 and 2014. Important to note is that WB has had a more downward trajectory and could be used a case study as well on what not to do/ avoid.



From an industry perspective, we finally look at the domestic gross over the years:

<img width="283" height="209" alt="image" src="https://github.com/user-attachments/assets/ae7e948f-41d2-47f4-a358-c83a37a28d2d" />


Except for 2014, the gross revenue has been on a steady rise over the years; implying the industry keeps growing hence investing has a good promise of growth of the investment. Microsoft should indeed invest in the movie industry to take part in the growth it promises.


## Conclusion

From our data-driven observations, we see Drama and Comedy being the genres with the most produced movies while Adult and Gameshow 

the least number of movies. 

When we look at the ratings we see Sport, Documentary and Biography rating quite highly. But drama is not doing badly either as it is 

in the top half.

On further investigate if a good rating translates to good income we realize highly rated movies infact gross less than poorly rated 

movies. The averagely rated movies gross extremely highly giving us an indication that rating alone is not a good decision making 

factor. We would therefore recommend producing high grossing movies i.e Drama and Comedy as they gross highly. A high gross could 

translate to high profits since these two variables are positevly correlated.

To understand the competition in the market, we see the studio gross trends places BV Studios as the averagely top studio over the 

years. And lastly, we see the that the industry has had a steady growth based on the sales except for one year. Film is therefore 

still a promising industry and we would recommend Microsoft ventures into it.



