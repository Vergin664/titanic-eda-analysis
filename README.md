# titanic-eda-analysis

**Titanic Dataset - Exploratory Data Analysis (EDA)**

**Objective:**
To perform detailed Exploratory Data Analysis on the Titanic dataset to extract meaningful insights, detect patterns, and understand feature relationships related to passenger survival.

**Dataset Columns:**
* PassengerId: Unique identifier for each passenger
* Survived: Target variable (0 = No, 1 = Yes)
* Pclass: Ticket class (1st, 2nd, 3rd)
* Name: Passenger name
* Sex: Gender
* Age: Age in years
* SibSp: Siblings/Spouses aboard
* Parch: Parents/Children aboard
* Ticket: Ticket number
* Fare: Ticket price
* Cabin: Cabin number
* Embarked: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
  

**EDA Steps Performed:**

**1. Missing Value Analysis**
* Age has ~20% missing values
* Cabin has ~77% missing → dropped
* Embarked has <1% missing → imputed with mode

**2. Univariate Analysis**
* Numerical Columns: Histograms & Boxplots (Age, Fare, SibSp, Parch)
* Categorical Columns: Countplots (Sex, Pclass, Embarked, Survived)

**3. Bivariate Analysis**
* Survived vs Sex, Pclass, Embarked (Countplots)
* Boxplots of Age and Fare by Survived
* Correlation heatmap and scatter plots between numerical features

**4. Multivariate Analysis**
* Combined visualizations: Survived by Sex and Pclass
* Fare vs Age colored by Survived and styled by Pclass
* Catplots for survival across multiple categorical features


**Key Insights:**
* Females had a significantly higher survival rate than males
* 1st class passengers had better chances of survival
* Passengers who paid higher fares generally had higher survival
* Age didn’t have a strong direct correlation with survival
* Most passengers embarked from SouthamptonLarge families (high SibSp/Parch) were rare but often had lower survival.

**Deliverables:**
* Jupyter Notebook with observations, insights and visualizations
* This README file

**Tools Used:**
* Python
* Pandas
* Seaborn
* Matplotlib
* Jupyter Notebook



