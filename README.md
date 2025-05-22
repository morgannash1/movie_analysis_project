# Movie Analysis Project
**Author**: [Morgan Nash](mailto:morganmichellenash@gmail.com)

# Business Understanding

The purpose of this project is to answer questions about past films in order to give recommendations to our company, who is new to creating movies. By cleaning, organizing, and analyzing various data sets, the following questions are answered:

1. Which movie genres receive the highest ratings?
2. Is there a trend in the relationship between production budget and profit?
3. When is the best time of year to release a movie?
4. What studios make the most money?

# Data Understanding 
The data provided for this project comes from various sources and comes in different formats:

**Box Office Mojo** is primarily focused on tracking the financial performance of movies.
**IMDb** relies heavily on user ratings and calculates a weighted average rating for movies.
**Rotten Tomatoes** aggregates reviews from professional critics.
**The Movie Database** focuses on user ratings and community-driven content, similar to IMDb.
**The Numbers** focuses on the financial performance of movies, tracking box office gross, budgets, and profitability.

### Data Preparation & Analysis



### Visualizations & Findings
![common movie genres](images/common_movie_gen.png)

Genre: 
![top movie genre combos](images/top_movie_gen_comb.png)
![top movie genres separated](images/top_movie_gen_sep.png)

Production Budget:
![average profit by budget group profitable](images/avg_prof_by_bud_group_prof.png)
![average profit margin](images/avg_prof_margin.png)

When to Release:
![average profit by month](images/avg_prof_by_month.png)

Studio:
![top 5 studios average profit](images/top_5_studio_avg_prof.png)
![top 5 studios total profit](images/top_5_studios_by_total_prof.png)



# Conclusions

## Limitations
It's important to be aware of any limitations that can affect the accuracy and completeness of our insights.

"Best" Bias: "Best" is subjective. Some of the data used in this project comes from public sources where general users are relied on to provide ratings and reviews. This introduces bias; user ratings can be influenced by hype, recency bias, as well as the users who actively rate movies might not represent the entire movie-watching public. (The sample might not be representative of the entire population.)

Quality of Numbers: The numbers available publicly about films are frequently estimates, especially for production costs, marketing, and distribution. Similarly, "profit" figures can be complex, as studios might use different accounting methods.

Changing Environment: Historical box office data might not be directly comparable to the success of new films to be released, as the popularity of streaming platforms increases, where older films didn't have to compete with streaming.

## Recommendations
1. When deciding which type of movie to produce, I have two recommendations based on findings about film ratings:
   
- For broad appeal and critical acclaim, consider the following genre combinations: Comedy/Documentary/Fantasy, Documentary/Family/Musical, and History/Sport. These combinations have been rated well historically, suggesting a blend that resonates well with audiences.

- For niche, high-quality content, genres like Shorts, Game-Shows, and News have historically achieved exceptionally high ratings, although not as common as other genres. This suggests a strong potential for creating highly regarded content that could be valuable for building critical prestige within our portfolio.

2. Evaluate production budget:
   
- To maximize profitability, the analysis of average profit margins across budget groups suggests a clear trend: investing more in a film's production budget tends to yield higher average profit margins. I recommend evaluating production budgets with a goal to enter the higher budget tiers. While initial investment will be higher, the potential for greater returns is also considerably enhanced in the higher budget groups.

3. Aim to release movies during the Summer Blockbuster Season or the Holiday Season

- Summer Blockbuster Season (May, June, July): Releasing films during these months, particularly in May, correlates with higher average profits, and aligns with the traditional summer movie season, capitalizing on school breaks and increased leisure time, which drives peak box office attendance.

- Holiday Season (November, December): November and December movie releases leverage the extended holiday breaks and increased consumer spending.

4. Working with Top Studios:

- Since our company is new to making movies, we should work with studios like Walt Disney, DreamWorks, Fox, Warner Bros., Universal, and Sony.

- Why? They make the most money! These studios consistently earn the highest profits. By teaming up with them, we can use their proven ways of making and selling movies, helping us learn quickly and make more money too.

## Next Steps
This preliminary analysis is straightforward and relies on publicly available data: IMDb for audience ratings and The Numbers for financial performance. While this initial look provides guidance, I believe there's significant value in pursuing more in-depth research. The next steps the company should take involve more research in the following areas:

- Studio-Specific Genre Performance: Do the recommended top studios perform better in specific genres than others? This could refine our studio partnership recommendations.

- Do certain genres always benefit from higher budgets, or is there an optimal budget range per genre?

- How do different marketing budget levels or distribution strategies impact box office and profit?

- Talent Impact: Does the presence of "A-list" directors or actors correlate with higher profit margins, especially in specific genres or budget tiers?


## For More Information

See the full analysis in the [Jupyter Notebook](notebook.ipynb) 

## Repository Structure

```
├── images
├── README.MD
├── movie_analysis_presentation.pdf
└── notebook.ipynb

```
