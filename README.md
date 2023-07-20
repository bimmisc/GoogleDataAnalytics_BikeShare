<h1>Google Data Analytics Certificate Case Study: Bike Share Program</h1>

<h2>Description</h2>

- For the Google Data Analytics Certificate, I chose Case Study 1 for my Capstone Project. <br />
- In brief, the scenario of this project was that the director of marketing believes the company's future success depends on maximizing the number of annual memberships.
- My team, the Marketing Analyst team at Cyclistic, a bike-share company in Chicago, was tasked to understand "how casual riders and annual members use Cyclistic bikes differently." and design a new marketing strategy to convert casual riders into annual members.<br />

- There were three questions that guide the future marketing program, and I, as a junior data analyst, was assigned the first question to answer:<br />
<b><p align="center">"How do annual members and riders use Cyclistic bikes differently?"</p></b>

- For my assignment, I collected (downloaded) <b>15 consecutive months</b> of data from a provided database. I used <b>Microsoft Excel</b> for the data preparation and processing (cleaning) steps.</b>

- After the "prepare" and "process" steps, I used <b>R programming (RStudio)</b> to analyze the cleaned data. </b>
- And below is the "Share" step, where I am sharing my findings represented in simple graphs and tables generated using RStudio. </b>
</b>


<h2>Data Analysis Program Used </h2>

- <b>Microsoft Excel</b>
- <b>RStudio</b>


<h2>Executive Summary</h2>

- <b>In this case study, I used 15 consecutive months of Cyclistic bike-share program data to evaluate: its bike rental performance, determine the trends of bike rentals by casual rides and members, and theorize what caused the differences in rental between the two categories of riders. I then developed an action plan based on those findings by suggesting 3 top recommendations</b>

- <b> Answers to the Question I was tasked with:
<p align="center">1) Member riders use Cyclistic bikes more frequently than Casual riders but for shorter durations on weekdays. The shorter rides by Member riders could be for daily commutes to and from work.
<p align="center">2) Casual riders had lower ride numbers but for longer durations in comparison to Member riders, especially on weekends, and they mostly used classic bikes than electric bikes.
<p align="center">3) Casual riders mostly used classic bikes than electric bikes compared to Member riders.</p></b>
(The Top 3 Recommendations are listed at the bottom of the page)


<h2>Findings</h2>


<b> 1) The first step in the analysis step was to find out the number of rides taken by Casual riders and Members. Figure 1 shows Members generated a higher number of rides than Casuals, especially on weekdays. And Members had higher usage on weekdays, which may be used for daily commutes to and from work.
However, on weekends, more rides were logged by Casual riders compared to members. This could be because of more visitors visiting the city on weekends. <b> <br/>
<p align="center">
<img src="Number of Rides.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p/><br />
<br />

2) The data was then analyzed for average ride durations logged by Casual riders and Members. Figure 2 shows Members had lower average ride durations Casual riders, but more often. The figure also shows Casual riders had longer ride durations on weekends than on weekdays, and this could be because they were visiting the city and used the bike for sightseeing. <br/>
<p align="center">
<img src="Average Ride Duration.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p/><br />

<br />
3) I also looked at the number of rides (3a) and average ride duration (3b) by month taken by Casual and Member riders. The overall trend shows that more rides were made in the Summer months, May to October, by both Casual and Member riders. Furthermore, higher average durations were logged from April to July. However, this trend did not coincide with the trend for the number of rides. <br/>
<p align="center">
3a)  <img src="Number of Rides By Month Dec to April.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p/><br />

<br /> <br/>
<p align="center">
3b)  <img src="Avg Ride Duration by Month Dec to April.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p/><br />

<br />
Lastly, I analyzed the data according to the type of bike used: how often and for how long. Figure  4a) show more Casual riders rented more electric bikes than casual bikes, while Member rides used both types of bikes relatively equally. Despite the higher usage of electric bikes, they were used for shorter durations than classic bikes. One of the reasons for this could be because of the higher price of renting electric bikes. <br/>
<p align="center">
4a)  <img src="Number of Rides by Bike Type.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p/><br />

<p align="center">
4b)  <img src="Duration of Ride by Bike Type.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p/><br />

<br />
The descriptive analysis for ride length was also calculated, as shown in the table below. Casual riders had longer average ride length than Member riders. Casual riders <br/>
<p align="center">
<img src="Descriptive Analysis.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<h2>My Top 3 Recommendations</h2>
<b><p align="center"> My top 3 recommendations to convert casual riders to annual members are:
<b><p align="center"> 1) Promote and advertise to Casual Riders that the annual membership provides cheaper rates with longer ride durations for renting electric bikes, especially on the weekends.
<p align="center"> 2) Promote about the benefits that come with the annual membership, including in-app recommendations for local attractions, discounted prices for entrance fees, at local retailers (cafes, restaurants), and other partnership discount.
<p align="center"> 3) Promote that the membership can be used in other cities's bike rental program.</p></b>

