# Fertility Rate, Life Expectancy, and Population Analysis (1960–2016)

This project explores how fertility rate, life expectancy, and population have changed globally from 1960 to 2016 using World Bank datasets.


---


## Objective:
To merge, clean, and visualize three major indicators — **fertility rate**, **life expectancy**, and **total population** — for each country and region over time.

---

## Datasets Used:
| File | Discription |
|------|-------------|
| `Metadata_Country.csv`| Country Code and Region information |
| `country_population.csv`| Total population from 1960–2016 |
|`fertility_rate.csv`| Fertility rates from 1960–2016 |
| `life_expectancy.csv` | Life expectancy from 1960–2016 |

---

## Key Steps:
- Cleaned and reshaped datasets (removed nulls, unwanted columns)
- Transformed data from wide to long format using `melt()`
- Merged all datasets into one final dataframe
- Removed incomplete rows to ensure clean visualization
- Created an **animated bubble chart** showing:
  - X-axis: Fertility rate (log scale)
  - Y-axis: Life expectancy
  - Size: Total population
  - Color: Country code
  - Animation: Year-wise trend from 1960 to 2016

---

## Bonus Feature:
Added a country code lookup tool to find a country's region by entering its 3-letter country code.

---

## Output:
A dynamic, year-wise visualization that highlights:
- Decline in fertility rates
- Rise in life expectancy
- Changes in population over time

This helps understand global development patterns and health indicators across regions.

---

## Connect

This project demonstrates foundational Data Engineering skills, from raw file ingestion to clean, analysed output.

Feel free to **star** the repo or **fork** for practice or extension!

Made with 💙 by Nivedhitha V 
[Github](https://github.com/Nivedhitha-V)
[Email](nivedhithav0407@gmail.com)
[LinkedIn](https://www.linkedin.com/in/nivedhitha-v/)
