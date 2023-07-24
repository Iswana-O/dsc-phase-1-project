# Phase 1 Project-MICROSOFT MOVIE STUDIO ANALYSIS
## Student name: JULLIET ISWANA
## Student pace: part time 
## Scheduled project review date/time:



### OVERVIEW
![](IMAGES/studio%20set.jpg)

  Over-The-Top (OTT) is a media distribution model that has gained popularity in recent years. It allows content providers to deliver television shows, movies, and videos directly to viewers via the Internet, bypassing traditional distribution methods such as broadcast, cable, and satellite TV providers. By using OTT platforms, content creators can reach a global audience without the need for intermediaries, giving them more control over their content and a broader reach. OTT service providers have various ways of acquiring new content to offer to their subscribers. The three primary methods are Purchasing Content, Producing Content, and Licensing content. Each of these approaches has its advantages and challenges. Purchasing existing content can provide immediate access to popular titles while producing original content allows the platform to build a unique brand identity. Licensing content can offer a cost-effective way to expand the content library, but it might come with restrictions or competition from other platforms seeking the same content.

   This disruptive distribution model has transformed the media landscape and altered the way audiences consume entertainment content. Major players in this industry are Netflix, Hulu, Disney+, Prime Video, ESPN +, and HBO Max to name but a few. Another Key player interested in this industry is Microsoft who has seen all the big companies creating original video content and they want to get in on the fun. My goal in this project was to analyze box office movies  and translate the findings into actionable insights that Microsoft can use in decision-making in regard to their new venture of creating a new movie studio.



### BUSINESS PROBLEM
Microsoft's decision to venture into the movie industry presents exciting opportunities, but also potential challenges due to their lack of experience in creating films. To ensure a successful entry into this competitive market, it is important for them to understand the types of movies that are currently thriving at the box office. Analysis of the current trends and translating these findings into actionable insights, Microsoft can make informed decisions on the types of films it should produce to maximize its chances of success.


### THE DATA
11 Datasets were compiled by the school for the project from the below sources for this analysis:

Box Office Mojo

IMDB

Rotten Tomatoes

TheMovieDB

The Numbers

The data available was in CSV and TSV formats. I made use of Python Libraries such as Pandas to read data into data frames. Represented tabular data with an integrated index, so data can be selected a manipulated using rows or columns. For visualization, I made use of matplotlib and seaborn libraries. Data cleaning formed  the foundation for exploring the data. Once I identified the data I wanted to work with, I converted data to the correct data types especially numeric data, deleted duplicates, and also deleted unwanted columns from some tables.  I merged the 11 data frames into 2 combined data sets (tmdb_movies_budgets_df(TMDB dataset) and movies_df(IMDB dataset)) seeking to answer key questions that will help Microsoft Studio make the right decisions.
 Below are the questions that guided my analysis:
 1. How does Microsoft Studio ensure the consistent production of high-quality content that resonates with both audiences and critics? What strategies can they adopt to gauge the success of their movies based on genre distribution and ratings?
 2. How can Microsoft Studio strike a balance between investing in high-budget blockbusters and smaller, riskier projects? What financial management practices should they employ to optimize movie budgets and maximize returns on investment?
 3. What marketing and distribution strategies should Microsoft Studio employ to ensure their films reach their intended audience effectively? How can they use release timing, along with other factors like budget and release month, to boost a movie's success?
 4. How important is award recognition for the long-term viability of a movie studio? How can Microsoft Studio work towards achieving critical acclaim and awards for their films, considering the changing trends in audience preferences and increasing competition in the industry?
 5. How can Microsoft Studio embrace adaptability and innovation to stay ahead in the constantly evolving film industry? What steps can they take to diversify their film portfolio by producing movies in different languages to reach wider markets and demographics?

###  RESULTS

### TOP GENRES AND RATINGS.
A successful movie studio is typically characterized by several key factors that contribute to its achievements and long-term viability
These factors include:
1. High-Quality Content: Producing films that resonate with audiences and critics alike is crucial. Consistently delivering well-made, engaging, and innovative movies. It was important to analyze the genres' distribution and their ratings so Microsoft Studio can produce movies that captivate viewers and leave a lasting impression. Drama and comedy are the most commonly produced movies. Microsoft should be keen on how the distribution of the produced movies and can opt to combine popularly produced genres with the most votes like drama and top genres with the highest average ratings which can be a viable strategy for their movie studio

    A successful movie studio understands the importance of diversifying its film portfolio. 
 By producing a range of genres and styles, the studio can attract different audience demographics and increase its potential market reach



![](/IMAGES/Distribution%20of%20Movie%20Genres.png)

![](/IMAGES/Top%20Genres%20with%20Highest%20Average%20Ratings.png)


2. Strong Financial Management: Successful studios are adept at managing budgets and financial resources effectively. 
They strike a balance between investing in high-budget blockbusters and smaller, riskier projects that may have the potential for significant returns.
Optimize the movie's budget to allocate resources efficiently. High-quality production values are essential, but excessive spending doesn't always guarantee success. Comparing Avatar and Avengers Age of Ultron both have relatively higher(close to $500M) and comparable budgets but the profit for Avatar is significantly higher.

   In the Correlation analysis of budgets and revenue: The positive sign indicates that there is a positive relationship between the two variables. As the production budget increases, the domestic gross tends to increase as well. This suggests that movies with higher production budgets are more likely to generate higher domestic grosses at the box office. Like the domestic gross the positive sign indicates a positive relationship between the production budget and the worldwide gross which tends to increase as when the production budget increases. This implies that movies with higher production budgets are more likely to generate higher worldwide grosses at the box office.

   The strong positive correlation between production budget and worldwide gross can be seen as an opportunity for Microsoft movie studios.
   Allocating larger budgets to movies with higher potential can lead to increased worldwide grosses and better returns on investment. While a strong correlation indicates a robust relationship between the variables.

![](/IMAGES/Top%2030%20Movies%20Net%20Profit.png)

![](/IMAGES/Correlation%20between%20Production%20Budget%20and%20Domestic%20Gross.png)

![](/IMAGES/Correlation%20between%20Production%20Budget%20and%20worldwide_gross%20Gross.png)

3. Effective Marketing and Distribution: Even the best films need effective marketing and distribution strategies to reach their intended audience. Release Timing is an important part of marketing and distribution.
   In the below analysis, I am examining the impact of Release Timing on a movie's success, along with other factors like budget and release month.
![](/IMAGES/Average%20Box%20office%20Performance%20by%20Release%20Month.png)

5. Award Recognition: While not the sole indicator of success, receiving critical acclaim and awards for their films can enhance a studio's reputation and potentially boost box office performance.
   Recognition is influenced by the average ratings a movie gets. From the data set, most movies receive a mean rating of 6.261905. The average rating has been increasing throughout the years peaking in 2018 while the number of votes reducing  therefore could  signify that  the competitors have significantly improved the quality of movies produced. Also indicates that the target audience is becoming niche It is important to be aware as they get into the film industry
   There is a Moderate Positive correlation of 0.4 between the number of votes and average ratings; when the number of votes increases, average ratings increase moderately. There is minimal close to zero correlation between the runtime in minutes  and average ratings of movies. However, it is important for Microsoft Studio to note that Average Runtime over the Years has been increasing


![](/IMAGES/Average%20Rating%20Over%20the%20Years.png)

![](/IMAGES/Number%20of%20Votes%20over%20the%20Years.png)

![](/IMAGES/Correlation%20Between%20Rating%2CVotes%20and%20Runtime.png)

![](/IMAGES/Average%20Runtime%20over%20the%20Years.png)

5. Adaptability and Innovation: The film industry is constantly evolving, and successful studios are quick to adapt to changing market trends and technologies.
   Embracing new filmmaking techniques, distribution methods, and consumer preferences can give a studio a competitive edge. In the analysis I am exploring how consumer preferences can give Microsoft an edge by reaching wider markets.  the analysis is centered around the performance of movies based on their original language, considering metrics such as popularity, vote_average, and vote_count. Microsoft need not restrict production to only English. Movies can be diversified and produced in different languages and can be translated into others based on demand

![](/IMAGES/Average%20Popularity%20by%20Original%20Language.png)







## Summary
Overall,  from the data, Microsoft Studio can increase its chances of success by producing high-quality content across various genres, effectively managing its finances, implementing strong marketing and distribution strategies, aiming for award recognition, and staying adaptable and innovative in the ever-changing film industry. However, I would not recommend Microsoft setting up a new movie yet since there are other options available;
They can opt to Purchase existing content and can provide immediate access to popular titles
Microsoft can partner with content and studio providers to license rights for other titles.
intellectual Property (IP) Management: Microsoft can start Building and managing valuable intellectual properties, such as successful franchises or book adaptations prior to setting up studio first
Further Research- analyze more recent data for the film industry


