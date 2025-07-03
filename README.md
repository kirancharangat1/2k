# 2k

This project is inspired by my love for NBA 2k. To give a background, I would play rec games with my friends and at the end of each game, we are given a box score which displays our basic stats like points, rebounds, and assist for that game. Over time I started to ask myself questions such as: "I wonder how many points me and my teammates average in the rec games we play?", "I wonder how many points we average when we win vs when we lose", "I wonder how our stats look like over time and see if anyone is making any steady improvements". So I decided to answer these questions. 

The first step in answering these questions was collecting the data. I did this manually by taking a screenshot of our box score at the end of each game, and then manually inputing the box score stats in an excel file. I did this for both our team and the opposing team. Now while we had a different opposing team every game, I still thought it to be benefical to collect the opposing teams stats to see what insights we can get from them. 

Next I did some feature engineering where I created new statistics too look at like field goal percentage and 3 point percentage to obtain a more in depth view on our performances. Next I did some actual analysis where I computed our team and the opposing team's averages for each statistic, like points, rebounds, assists etc where I was able to identify what players excel at what. 

Next I computed an average of our team stats which is just an accumulation of our individual averages and compared this with the opposing team averages. I did this to gain insight into what we do better or worse than compared to the opposing team on average. For example, our team combines for an average of 72.4 points per game whereas the opposing team combines for an average of 66.2 points per game. This means that we as a team average 6.2 more points than the opposing team. 

Next I computed our teams averages based on wins and losses to gain insights into how much better or worse we play based the end result being a win or loss. As you would logically assume, we all usually play better when we win and conversely play worse when we lose. 

Next I created a grpah that visualizes our trend of wins and loses over time. From this graph we are able to visualize when we go on winning streaks, when we go on losing streaks, and how long-lasting those streaks may be. 

![image](https://github.com/user-attachments/assets/922d207d-ea40-4473-8782-477380a6af6c)

Finally, I created a graph that displays our average stats over time. In this graph, we are able to visualize the average of any specific stat over time for any specific player. For example, the graph below displays the average file dgoal percentage over time for the speficied players in the graph. THis gives us insights into the fluctations of field goal perentage and we are able to visualize how unstable or stable these flucations are. 

![image](https://github.com/user-attachments/assets/3216efbf-a8a7-4022-8cd7-e6598dd1eb2f)

