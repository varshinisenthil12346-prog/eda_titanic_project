# EDA Report: Titanic Dataset

## 1. Dataset Overview
- Rows: 891, Columns: 15
- Target variable: `survived`
- Cleaning: dropped `deck` (too many missing values), filled `age` with median, `embarked` with mode

## 2. Key Findings
1. Overall survival rate was 38.4%.
2. Women survived at 74.2% vs men at 18.9%. Gender was the strongest factor.
3. 1st class survival was 63.0%, while 3rd class was only 24.2%.
4. Children had a survival rate of 58.0%, higher than other age groups.
5. Passengers travelling with family survived at 50.6% vs 30.4% for those alone.
6. Fare is positively related to survival (correlation = 0.26); class is negatively related (-0.34).

## 3. Conclusion
Gender, passenger class and age were the main factors influencing survival.
Women, children and first-class passengers had the highest chances of survival.
