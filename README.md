# Data Analysis: Video Game Industry Insights

This project features an exploratory and statistical analysis of historical video game sales and review data. The primary objective is to identify regional consumption patterns to drive data-informed marketing strategies and product launch planning.

## 📊 Dataset Structure

The dataset contains detailed information for over 16,000 titles, structured across the following variables:

| Column | Description |
| :--- | :--- |
| **Name** | Title of the game. |
| **Platform** | Release platform (e.g., PS4, Xbox, PC). |
| **Year_of_Release** | The year the title was officially released. |
| **Genre** | Game category (Action, RPG, Sports, etc.). |
| **NA_sales** | Sales in North America (in millions USD). |
| **EU_sales** | Sales in Europe (in millions USD). |
| **JP_sales** | Sales in Japan (in millions USD). |
| **Other_sales** | Sales in the rest of the world. |
| **Critic_Score** | Aggregate score from professional critics (Metacritic). |
| **User_Score** | Aggregate score from the player community. |
| **Rating** | ESRB content rating (E, T, M, etc.). |

## 🔍 Key Insights & Conclusions

Segmenting the analysis by region revealed distinct consumer behaviors that are critical for strategic decision-making:

* **Regional Cultural Divergence:** A comparison between North America and Japan highlights significant differences in market preferences. The North American audience shows a high affinity for the **PlayStation** ecosystem, **Action** titles, and **Mature (M)** rated content. Conversely, the Japanese market is dominated by **Nintendo** hardware, with a strong preference for **Role-Playing Games (RPGs)** and **Teen (T)** rated content.
* **Strategic Application:** These insights allow for more efficient marketing budget allocation. For instance, if a company were to launch a new adult-oriented action title, marketing efforts should be heavily intensified in North America to maximize ROI. Meanwhile, RPG titles with a younger target demographic should remain the focus for Asian market operations.

## 🛠️ Tech Stack

* **Python**
* **Pandas & NumPy:** Data cleaning and manipulation.
* **Matplotlib & Seaborn:** Data visualization and trend analysis.
* **SciPy:** Statistical hypothesis testing (T-tests and Chi-Square tests).

---

### How to run this project:
1. Clone the repository.
2. Install dependencies: pip install -r requirements.txt
3. Run the Jupyter Notebook `notebook_projeto_final.ipynb` to view the full analysis.