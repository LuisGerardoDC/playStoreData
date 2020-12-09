## Notion link
https://www.notion.so/PlayStore-09ad706ff4294690be05925dff4dc61c
# Play store data analysis

in this repository is made an analysis from data of apps in play store, this analysis was made to answer 3 questions:

- Wich is the most popular app on the play store?

- wich category is the most popular?

and as a plus, it was importat to know if the rate of the apps is influenced by costs

## Most popular app

In order to get the conclusion that Facebook is the most popular app, the data was cleaned, sorted by installs and after that it was clear that many apps had the same amount of installs, so those apps with 1,000,000,000 installs were sorted by number of reviews, then Facebook had over 78e8 reviews. 

![Most popular app](https://github.com/LuisGerardoDC/playStoreData/blob/master/images/popular_app_.png)


## Most popular category

The most popular category was found after added up the number of installs for each app in category, this operation left a data frame whit the name and the amount of installs for category. the most popular category is GAME whit over 10e9 installs. 

![Most popular category](https://github.com/LuisGerardoDC/playStoreData/blob/master/images/popular_category.png)

## Distribution (percentage) of ratings

The first aproach lead to thik that free apps have better ranking, but it is not compleatly true, these apps have more reviews because people is more likely to install free apps then paid apps. 

![rating by count](https://github.com/LuisGerardoDC/playStoreData/blob/master/images/rating_by_count.png)

For not being influenced by the diference in installs, the percentage is a better aproach, and now it is visible that the ratings is not diferente between paid and free apps

![rating by percentage](https://github.com/LuisGerardoDC/playStoreData/blob/master/images/rating_by_percentage.png)
