# movie-correlation-project
The objective of this project was to analyze a movie dataset to identify the variables that are correlated with movie revenue. By leveraging Python and Jupyter Notebook, I conducted exploratory data analysis to uncover insights into the factors influencing a movie's financial success.
Dataset Description
The dataset consisted of a CSV filed with 6820 movies in the dataset (220 movies per year, 1986-2016). The dataset comprised various attributes related to movies, including budget, production company, country of origin, director, genre, revenue, rating, release date, duration, IMDb user rating, number of user votes, main actor/actress, writer, and year of release.

Methodology:
1. Data Acquisition and Preprocessing: I began by obtaining the dataset and performing data preprocessing tasks such as handling missing values, data type conversions, and ensuring data consistency.  
2. Exploratory Data Analysis (EDA): EDA involved examining the distribution of each variable, identifying outliers, and exploring relationships between variables using statistical measures and visualizations such as scatter plots, histograms, and correlation matrices.
3. Correlation Analysis: The primary focus of the analysis was to identify variables correlated with movie revenue. I calculated Pearson, Kendall and Spearman correlation coefficients between revenue and other variables to quantify the strength and direction of their relationships.
The correlation analysis shows that:
•	There is high correlation between budget and gross(revenue)
•	There is high correlation between votes and gross(revenue)

4. Feature Selection: Based on correlation analysis results, I selected the most relevant features that exhibited significant correlations with movie revenue(budget and votes) for further investigation.

Results
1. Correlated Variables: Through correlation analysis, I identified the variables that significantly correlated with movie revenue, which included budget and the number of user votes.
  
2. Impact of Budget: The budget of a movie was found to have a strong positive correlation with re venue, indicating that higher-budget films tend to generate higher revenues.

3. Votes: The number of user votes showed significant positive correlations with revenue, suggesting that audience engagement play vital roles in determining a movie's financial success.
 

Conclusion:
This project provided valuable insights into the factors driving movie revenue, highlighting the importance of budget allocation and audience engagement in the film industry. By leveraging basic data analysis techniques and Python programming skills, I was able to uncover meaningful relationships within the dataset and draw actionable conclusions for stakeholders in the entertainment sector.


Skills Demonstrated
- Data acquisition and preprocessing
- Exploratory data analysis (EDA)
- Correlation analysis
- Data visualization
- Python programming
- Critical thinking and problem-solving in a data-driven context

Tools Used:
- Python (including libraries such as Pandas, NumPy, Matplotlib, and Seaborn)
- Jupyter Notebook

