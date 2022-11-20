
 # MICROSOFT MOVIE DATA ANALYSIS PROJECT


 # Project Overview
Our client, Microsoft, is planning to open a new Movie Studio. 
The goal of this project is to define what factors to look at for 
a successful movie production then translate those findings in to 
actionable insights that the head of Microsoft’s new movie studio 
can use to help decide what type of films to create. 

 # Business Problem
Microsoft is launching a movie studio that can compete with other 
successful movie studios. However, they don’t know anything about 
creating movies. In order to be successful from the start, I will 
have to consider the following questions:

    What genres have the highest ratings?

    What genres have the highest grossings?

    Which is the most successful movie studio with a high 
    number of gross?

    What genre is popular in the box office?

    Who are the top directors from the standpoint of movies 
    profitability?

    Who are the top screen writers from the standpoint of 
    movies profitability?

    Correlation between production budgets vs profits vs movie?

I assume that the answers to these questions are one of the main 
parts of the steps that should be taken into account to create 
the most cost-effective film in the digital world. 

# Data Understanding
It involves using things like budget, income, popularity, profit, 
timing, rating, popularity, genres, ratings, directors and 
script/screen writers. This project analyzes data from IMDB, 
Rotten Tomatoes, The Movie DB and Box Office Mojo, pulling data 
from over 2,000 movies over the past years.

# Data Preparation
Here, I will ensure that raw data being readied for processing and 
analysis is accurate and consistent so the results will be valid. 
Mostly this data is commonly created with missing values, 
inaccurcies, or other errors and separate data sets often have 
different formats that need to be reconciled when they are combined. 

# (1A). Data Cleaning
Now that we have a view of how the data sets look like, i shall 
begin to detect, correct corrupt records, identitfy incomplete or 
irrevelant parts of the data within those different datasets then 
replace, modify or delete the coarse data.

# (1B) Merging of data
* Put together the combination of bommo_df with rtmo_df to make one 
   dataframe.
* Put together the combination of movie_basics_df with movie_ratings_df
  to make one dataframe.
* Inorder to avoid contamination within the data, I checked if 
   there were any duplicates. 

# Exploratory Data Analysis
After polishing our data, I shall now move on to drawing conclusions 
using statistics. This means use of statistical and graphic tecniques 
to present information about the data set.




### 1. What genres have the highest ratings?


<img src = "GENRE RATINGS.png">
Most genres are rated R while least are NR. If most movies are 
rated R then this means that the audience is most probably 
aged 2 - 12 years. It could also conclude that as a movie studio, 
it can draw a line on which kind of movies to produce most to 
target a certain audience.

### 2. What genres have the highest grossings?


<img src = "GENRES HIGHEST GROSSINGS.png">
Drama|Mystery and Suspense made the highest total gross.
This enlightens a movie studio on the kind of movie genre they 
should invest in to bring income to the movie studio.

### 3. Which is the most successful studio with a high number of gross?


<img src = "SUCCESSFUL HIGH GROSSING STUDIO.png">
From this output we can tell in what order who will be the main 
competitors to Microsoft Movie Studio in the movie industry empire 
starting with WB being the first.

### 4. What genre is popular?


<img src = "GENRE POPULARITY.png">
Clearly, we can see that Action and Adventure|Mystery and Suspense 
trends more in box office. With that info, the Microsoft Movie Studio 
can take action on which films to make or begin with in order to be 
on top and make crazy profits at the same time.

### 5. Who are the top directors from the standpoint of movies profitability?


<img src = "TOP DIRECTOR.png">
We notice that Clint Eastwood has the highest number of total gross 
income meaning his films are selling and are loved and followed up 
by a big audience. This means that the Movie Studio can hire Clint 
Eastwood as their director with assurance that he will bring benefits 
to the new company.

### 6. Who are the top screenwriters from the standpoint of movies profitability?


<img src = "TOP SCREENWRITER.png">
We notice that Brian Helgeland has the highest number of total 
gross income meaning his skills on script writing is selling within 
the movie industry. This means that the Movie Studio can hire Brian 
Helgeland as their writer with assurance that he will bring profits 
to the new company. We can conclude that with both the efforts of 
both Clint Eastwood and Brian Helgeland, Microsoft Movie Studio 
can make triple in profits.

### 7. Correlation between production budget vs profit vs movie?


<img src = "PRODUCTION BUDGET VS MOVIE.png">


<img src = "PROFIT VS MOVIE.png">
From the above graphs, you will notice that movies with high a 
production budget end up being movies with the highest profits. 






# Conclusion
* Most genres are rated R while the least are NR.
* Drama|Mystery and Suspense genre made the highest total gross.
* WB studio is the highest ranking studio making a high gross and 
  definitely a major competitor to Microsoft Movie Studio.
* Action and Adventure|Mystery and Suspense trends more in box office.
* Clint Eastwood has the highest number of total gross as a director.
* Brian Helgeland has the highest number of total gross  as a  script writer.
* Movies with high a production budget end up being movies with the highest profits. 

# Recommendations
 I would consult Microsoft to:-
* Determine the company's niche. What type of content do you plan to 
  specialize in creating? It’s important to narrow your company's 
  brand identity to guide you when choosing projects to produce
* Draft a business plan. A solid business plan is the key to a 
  financially sound and functioning production company. Employ a 
  business model that lets you gradually build your business entity 
  to a larger one. In particular, plan for your startup costs, from 
  labor to office space to state and federal taxes. Draft a mission 
  statement that summarizes your film company's goals and how you plan 
  to profit from your video production business. Then, think about 
  where you want to be after your first year. What business 
  opportunities do you see yourself pursuing in five years? 
  Strike the balance between ambitious and achievable.
* Hire an attorney. The steps necessary to start a production company 
  are complex, so you'll want an entertainment lawyer who specializes 
  in production services to give you legal advice throughout the  
  process. Your attorney will review all the documents you need to 
  start your business, and once you're up and running, they can 
  assist you in hiring your staff and creating the contracts for 
  your projects.
* Seek funding. In order to grow, a production company needs money. Unless you're independently wealthy, you will likely have to use your business plan to secure a small business loan. Make sure your risk isn't so great that you risk financial ruin if things don't work out.
* Get your paperwork in order. When you're in charge of your own film production company, you're responsible for a lot of workaday minutia. You'll need to set up a business bank account, get an employer identification number, and file an operating agreement and articles of organization. Depending on your business location, states and municipalities may require business licenses, and they typically charge annual business taxes.
* Assemble an all-star team of executives. Great ideas tend to come from teams of people, so you'll need to search for exemplary employees to help make your ideas a reality. You'll want to hire positions for your executive team: a head of development (who decides what scripts to produce and guides the creative team), a head of production (who's in charge of budgeting and the physical production process), a head of post-production (who oversees the editing process) and a head of distribution (who's in charge of marketing and selling your content). Other creative filmmaking positions such as writers, actors, directors, and cinematographers are usually hired on a per-project basis rather than working full-time with one company.
* Hire a production accountant. Entertainment payroll is a complicated job, so you'll need a certified public accountant trained in entertainment financing to take care of your company's accounting. Production accountants are trained to handle the constantly rotating crew that are common to the film production world, along with the various rules and regulations associated with the different entertainment unions.
* Purchase production insurance. Accidents happen in film production—from crew members slipping on set to stunt performers getting injured while filming dangerous feats. In the event any unexpected incidents occur, you'll need a good insurance policy to protect you.
* Build a website and create a social media presence. Players need to be able to find your company online, so hire a website designer to create a simple but informative website for your company. Less is usually more with production company websites—your contact info and brief examples of your work are usually all you need. It's important to have a social media presence as well, but until your company expands to have a constant stream of content, it may be unnecessary to hire someone specifically to run your social pages.
