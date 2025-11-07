# gaming-behavior
Analysis of the behavior gamers give off different games they play

[https://www.kaggle.com/datasets/wasiqaliyasir/online-gaming-behavior-datasetLinks to an external site.](https://www.kaggle.com/datasets/rabieelkharoua/predict-online-gaming-behavior-dataset)

The data did not need cleaning as the author of the dataset in Kaggle already cleaned it out beforehand.

Data Manipulation
	I filtered out 'PlaytimeHours' to exclude values that were less than 1 hour, so it makes my data more concise and easier to understand.
	I then used groupby to group 'game genre' and 'age' so I can calculate the mean for each game genre and use that to create a graph.

Data Visualization
	I created three different graphs to visualize this data set.
	I visualized Average Age per Game Genre by using a barplot, and the results conclude that there is no significant relationship between 
age and game genre, it is evenly spread out.
<img width="624" height="479" alt="image" src="https://github.com/user-attachments/assets/f8d81eb7-4d24-4bf8-bf12-d209231a4fac" />

	Next, I used a countplot to visualize the Number of Players by Location and Game Genre. It showed me that there are more players in the
USA then any other country, and that sport games are more popular in the USA.
	Next I did a bar graph to see if there was any relationship between in game purchases and average achievements, to see if its worth it
to add extra achievements in order to expect more revenue, and I found out there is no relationship between them as their average is tied.	
<img width="659" height="459" alt="image" src="https://github.com/user-attachments/assets/c68907b1-7368-46b1-a3d1-96371657433d" />


	Next I made a pie chart to see the ratio of men and women in the video game world and the pie chart shows that there are 59.8% men 
and 40.2% women. This is useful to make better ads that advertise games more to men than women.
achievements unlocked :  whether makes ingame purchases
<img width="546" height="450" alt="image" src="https://github.com/user-attachments/assets/3a1312e9-4597-4126-ab63-4b18f8509ee8" />

Statistical Analysis
	I made a table that shows the mean, median, and count of achievements based on hours played, and I found that 
there is no clear trend with achievements and hours played. Playing more does not necessarily mean more achievements.
