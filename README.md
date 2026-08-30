# 🏏 IPL Pandas Data Analysis Project

## 📌 Project Overview

This project is a complete **IPL Match Data Analysis project using Python and Pandas**.

The main purpose of this project is to develop practical skills in:

* Data Inspection
* Data Selection
* Data Filtering
* Categorical Data Analysis
* Sorting
* GroupBy
* Aggregation
* Feature Analysis
* Pivot Tables
* Exploratory Data Analysis

The project contains **75 practical questions**, starting from basic Pandas operations and gradually progressing toward advanced analysis.

---

# 🎯 Project Objectives

By completing this project, the following Pandas concepts will be practiced:

```text
Data Loading
Data Inspection
Column Selection
Row Selection
loc
iloc
Boolean Filtering
isin
unique
nunique
value_counts
sort_values
groupby
agg
Feature Comparison
Pivot Table
Data Analysis
```

The project is designed to move from **basic Pandas operations → real-world IPL analysis → advanced analytical questions**.

---

# 📊 Dataset

The dataset contains IPL match-level information including:

* Match ID
* Season
* City
* Date
* Team 1
* Team 2
* Toss Winner
* Toss Decision
* Result
* DL Applied
* Winner
* Win by Runs
* Win by Wickets
* Player of the Match
* Venue
* Umpires

---

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook / VS Code

---

# 📚 Project Questions

## 🟢 Level 1 — Basic Inspection

### Q1

Dataset mein **total rows aur columns** kitne hain?

### Q2

Dataset ke tamam column names display karo.

### Q3

Dataset ke **data types** check karo.

### Q4

Dataset ki first 10 rows display karo.

### Q5

Random 7 rows display karo.

### Q6

Dataset mein total **matches** kitne hain?

### Q7

`season` column ki unique values identify karo.

### Q8

`city` column mein kitni unique cities hain?

### Q9

`team1` mein kitni unique teams hain?

### Q10

`winner` column mein kitni unique teams hain?

---

# 🟡 Level 2 — Categorical Data

### Q11

Har city mein kitne matches hue?

### Q12

Top 10 cities find karo jahan sabse zyada matches hue.

### Q13

Har team ne `team1` mein kitni baar appearance di?

### Q14

Har team ne `team2` mein kitni baar appearance di?

### Q15

Sabse zyada toss kis team ne jeeta?

### Q16

`toss_decision` ki frequency find karo.

### Q17

`result` ki frequency find karo.

### Q18

Top 10 **Player of the Match** find karo.

### Q19

Top 10 venues find karo jahan sabse zyada matches hue.

### Q20

`winner` ki frequency find karke top 10 winning teams nikalo.

---

# 🟠 Level 3 — Filtering

### Q21

Sirf **2017 season** ke matches nikalo.

### Q22

Sirf **2017 aur 2018** ke matches nikalo.

### Q23

Aise matches find karo jahan `win_by_runs > 100`.

### Q24

Aise matches find karo jahan `win_by_wickets >= 8`.

### Q25

Sirf woh matches nikalo jahan **Mumbai Indians** winner thi.

### Q26

Sirf woh matches nikalo jahan toss decision **bat** tha.

### Q27

Sirf woh matches nikalo jahan `result = tie`.

### Q28

Sirf woh matches nikalo jahan **DL method apply** hua.

### Q29

Aise matches find karo jahan toss winner aur match winner **same** team thi.

### Q30

Aise matches find karo jahan toss winner aur match winner **different** teams thi.

---

# 🔵 Level 4 — `loc` / `iloc`

### Q31

Dataset ki first 5 rows se sirf `team1`, `team2`, `winner` columns select karo using `loc`.

### Q32

`iloc` se first 10 rows aur first 5 columns select karo.

### Q33

Sirf `season`, `city`, `winner` columns display karo.

### Q34

`winner` Mumbai Indians wale matches mein sirf `season`, `city`, `venue`, `winner` display karo.

### Q35

Dataset ki last 10 rows `iloc` se nikalo.

---

# 🔴 Level 5 — GroupBy

### Q36

Har season mein kitne matches hue?

### Q37

Har season mein sabse zyada matches kis season mein hue?

### Q38

Har team ki total wins calculate karo.

### Q39

Har season mein har team ki wins calculate karo.

### Q40

Har city mein matches ki count calculate karo.

### Q41

Har venue par matches ki count calculate karo.

### Q42

Har team ne toss kitni baar jeeta?

### Q43

Har team ne toss jeet kar **batting** kitni baar choose ki?

### Q44

Har team ne toss jeet kar **fielding** kitni baar choose ki?

### Q45

Har season ka **most successful team** find karo.

---

# 🟣 Level 6 — `agg()`

### Q46

`win_by_runs` ka **maximum, minimum aur average** calculate karo.

### Q47

`win_by_wickets` ka maximum, minimum aur average calculate karo.

### Q48

Har team ke liye:

* Total wins
* Average win by runs
* Maximum win by runs

### Q49

Har season ke liye:

* Total matches
* Average win by runs
* Maximum win by runs

### Q50

Har city ke liye:

* Total matches
* Average win by runs

---

# 🟤 Level 7 — Sorting

### Q51

Matches ko `win_by_runs` ke descending order mein sort karo.

### Q52

Top 10 biggest wins by runs nikalo.

### Q53

Top 10 biggest wins by wickets nikalo.

### Q54

Teams ko total wins ke according descending order mein arrange karo.

### Q55

Cities ko number of matches ke according descending order mein arrange karo.

---

# 🚀 Level 8 — Advanced Pandas

### Q56

Ek naya column `toss_match_winner` banao jo bataye ke toss winner match bhi jeeta ya nahi.

### Q57

Toss winner ke match jeetne ka **percentage** calculate karo.

### Q58

Har team ka **toss wins vs match wins** compare karo.

### Q59

Har season ka **most awarded Player of the Match** find karo.

### Q60

Har venue ka most successful team find karo.

### Q61

Har season mein sabse zyada Player of the Match awards kis player ne jeete?

### Q62

Har team ka total `win_by_runs` calculate karo.

### Q63

Har team ka total `win_by_wickets` calculate karo.

### Q64

Kaunsi team **runs se sabse zyada matches** jeeti?

### Q65

Kaunsi team **wickets se sabse zyada matches** jeeti?

---

# 🏆 Final Challenge — Boss Level

These questions should be solved **without being told which Pandas function to use**.

### Q66

**Top 5 teams** find karo based on total match wins.

### Q67

Har season ki **top winning team** find karo.

### Q68

Find karo ke **toss jeetna match jeetne mein kitna helpful** raha.

### Q69

Top 10 players find karo based on **Player of the Match awards**.

### Q70

Top 10 venues find karo based on number of matches.

### Q71

Find the **biggest win by runs** and show:

```text
season
team1
team2
winner
win_by_runs
```

### Q72

Find the **biggest win by wickets** and show:

```text
season
team1
team2
winner
win_by_wickets
```

### Q73

Har season mein total matches aur total wins calculate karo.

### Q74

Ek **pivot table** banao showing:

```text
season × toss_decision
```

aur values mein match count ho.

### Q75 🔥

**Final analysis:** IPL dataset se **5 important insights** nikalo jo kisi cricket analyst ke liye useful hon.

---

# 📈 Skills Practiced

| Skill                | Questions |
| -------------------- | --------- |
| Dataset Inspection   | Q1–Q10    |
| Categorical Analysis | Q11–Q20   |
| Filtering            | Q21–Q30   |
| `loc` / `iloc`       | Q31–Q35   |
| `groupby()`          | Q36–Q45   |
| `agg()`              | Q46–Q50   |
| Sorting              | Q51–Q55   |
| Advanced Analysis    | Q56–Q65   |
| Final Challenges     | Q66–Q75   |

---

# 🧠 Learning Strategy

The project follows a progressive learning structure:

```text
Beginner
   ↓
Inspection
   ↓
Selection
   ↓
Filtering
   ↓
Categorical Analysis
   ↓
loc / iloc
   ↓
GroupBy
   ↓
Aggregation
   ↓
Sorting
   ↓
Advanced Analysis
   ↓
Final Challenges
```

The objective is to **solve the questions independently** instead of simply copying solutions.

---

# 🏁 Expected Outcome

After completing all 75 questions, you should be comfortable with the core Pandas operations required for:

* Data Analysis
* Data Cleaning
* Exploratory Data Analysis
* Data Preparation
* Machine Learning preprocessing

Most importantly, you should be able to look at a real dataset and decide **which Pandas operation is appropriate for the problem**.

---

# 👨‍💻 Project Status

**Status:** In Progress 🚧

**Dataset:** IPL Match Dataset

**Total Questions:** 75

**Primary Library:** Pandas

**Difficulty:** Beginner → Intermediate → Advanced

---

# ⭐ Future Improvements

After completing the 75 Pandas questions, the project can be extended with:

* Matplotlib visualizations
* Seaborn EDA
* Advanced feature engineering
* Statistical analysis
* Machine Learning
* Team win prediction
* Match outcome prediction
* Model evaluation
