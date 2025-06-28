Task:

      Conduct an in-depth Exploratory Data Analysis on a complex dataset.
      Focus on understanding data distributions, identifying missing values, detecting outliers, and uncovering relationships between variables. 
      Utilize visualizations like histograms, box plots, and heatmaps to support your findings.


Solution:
                Code Preview: Titanic EDA in Steps
    
          📦 Import Libraries
          
          pandas, numpy, seaborn, matplotlib
          
          warnings, IterativeImputer, RandomForestRegressor
          
          📥 Load Dataset
          
          Load Titanic dataset using sns.load_dataset('titanic')
          
          Preview shape, columns, and head of the dataset
          
          🧼 Handle Missing Data
          
          Visualize missing values using heatmap
          
          Impute:
          
          Numerical: IterativeImputer with RandomForestRegressor
          
          Categorical: Fill with mode
          
          📊 Univariate Analysis
          
          Countplots of survived, pclass, sex
          
          Histogram of age with KDE
          
          🔗 Bivariate Analysis
          
          survived vs sex, pclass, age_group
          
          Combine plots: sex + pclass vs survived
          
          🛳️ Embarkation & Fare Insights
          
          embarked vs survived
          
          fare distribution with survival overlay
          
          👨‍👩‍👧‍👦 Family & Age Groups
          
          Feature: family_size = sibsp + parch
          
          Feature: age_group (Child, Teenager, Adult, etc.)
          
          📈 Correlation & Outlier Detection
          
          Correlation heatmap of numeric features
          
          Boxplot for fare
          
          IQR method to detect fare outliers
          
          📋 Output:
          
          Summary stats, visual insights, outlier count, and head of outlier records
