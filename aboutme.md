Skip to content
Search or jump to…

Pull requests
Issues
Marketplace
Explore
 
@alifarah94 
Learn Git and GitHub without any code!
Using the Hello World guide, you’ll start a branch, write comments, and open a pull request.


0
06.6kalifarah94/alifarah94.github.io
forked from daattali/beautiful-jekyll
 Code Pull requests 0 Projects 0 Security Insights Settings
alifarah94.github.io/_posts/Sumo
@alifarah94 alifarah94 Create Sumo
1849f10 5 minutes ago
43 lines (22 sloc)  2.2 KB
  
## Who wins in Sumo

Sumo wrestling is said to have been made 2000 years ago, rich in culture and deeply ingrained in the Japanese society it is now the national sport. 

![Sumo](https://upload.wikimedia.org/wikipedia/commons/a/ac/Kunisada_sumo_1851.jpg)


What intrigues me about sumo wresting is that there are no weight classes, everyone is able to fight everyone and what dictates who fights who is based on win/loss record in the tournament.


![Sumo](https://bjj-world.com/wp-content/uploads/2017/12/Screenshot_122.jpg)


I want to know who’s winning matches. How much do they weight? how tall are they? Are you more likely to win if your heavier than your opponent? Are you more likely to lose if your heavier than your opponent? 

The dataset I’m using has records of every professional match fought from January 1983 to September 2019. 


## How much do sumo weight
![Sumo](https://github.com/alifarah94/alifarah94.github.io/blob/master/img/total%20sumo%20weight.png?raw=true)

Here the data is showing every sumo that has fought at each weight (The data is showing weights of sumo’s at each fight and not individual sumo)

You can see that the majority of fighters are on the 150 kg mark.

![Sumo](https://github.com/alifarah94/alifarah94.github.io/blob/master/img/Mean%20weight.png?raw=true)

The mean weight validates this.

It seems that Sumo’s like to fight around the 150 kg weight. Lets look at wins by weight and see if we can find a correlation.

### Whos winning?
![Sumo](https://github.com/alifarah94/alifarah94.github.io/blob/master/img/matches%20won%20by%20weight.png?raw=true)

Visually we can see that graph 2 is identical to graph 1. When we look at the matches won axis, we can see that wins only go up to 2000 matches. If we look back at the previous graph the amount of sumo at the same weight numbered just over 4000, this suggest that the win rate around the mean weight is around 50/50.


### Crunching the numbers
If a sumo is heavier than his opponent, then he is 25% more likely to win
Also, if a sumo is lighter than his opponent then he has a 24% chance of winning his match 
And the numbers show the exact same for losing.
If a sumo is heavier than his opponent, then he is 25% more likely to lose and so on. 
