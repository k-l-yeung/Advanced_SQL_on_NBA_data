### <a id='overview'>1. Overview</a>

#### Motivation
- Use advanced SQL technique to answer some questions regarding the NBA 
- Some answers match successfully with independent reports

#### Method
- SQL technique applied
    - common table expression (CTE)
    - row_number() over()
    - rank() over()
    - left join, inner join
    - union all
    - min(), max(), round(), sum(), avg(), abs(), count()
    - alias for columns and tables
    - case ... when ...
    - group_concat()
- Python libraries used
    - pandas
    - sqlite3
    - os
    
 ### <a id='sam'>2. About the author: Kam Leung Yeung (Sam)</a>
 * PhD in Cognitive Psychology, Iowa State University in Ames, Iowa, USA

**Social media**:

* [LinkedIn](https://www.linkedin.com/in/kamleungyeung/)
* [Google Scholar](https://scholar.google.com/citations?user=OwUmaN8AAAAJ)
* [GitHub](https://github.com/k-l-yeung)
* [Tableau](https://public.tableau.com/app/profile/kam.leung.yeung#!/)

**Data source**
- [NBA game data from kaggle](https://www.kaggle.com/datasets/nathanlauga/nba-games?resource=download)

### <a id='toc'>3. Table of content</a>
1. <a href='#overview'>Overview</a>  
2. <a href='#sam'>About the author: Kam Leung Yeung</a> 
3. <a href='#toc'>Table of content</a> 
4. <a href='#eda'>Read in data</a>  
5. <a href='#df_to_sql'>Read pandas dataframe into sql database</a>  
6. <a href='#q'>Questions to be answered</a>  
 - <a href='#40'>Most **consecutive** 40+ pts game by a player</a>  
 - <a href='#top3'>The top 3 individual player score in every season between 2012 and 2022</a>  
 - <a href='#top5'>The top 5 score individual player score since 2004</a>  
 - <a href='#blown'>The biggest blown out in every season and the corresponding margin</a>  
 - <a href='#versatile'>Identify versatile players who started with most different positions</a>  
