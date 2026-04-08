##Key steps

-Data preprocessing
Load dataset and review structure using .info() and null checks
Remove irrelevant columns such as customer ID, gender, and tenure
Handle missing values by dropping incomplete rows
Standardise categorical fields by removing leading whitespace in province names
Create derived variables including Age_Group and Defaulted indicators
-Feature engineering
Encode digital banking usage into numerical values
Create age group segments using binning
Generate default indicator from loan status
Prepare variables for correlation and segmentation analysis
-Exploratory analysis
Plot bar charts to compare default rates across provinces and digital usage
Create scatter plots for income vs credit score and income vs account balance
Analyse relationships between customer demographics and financial behaviour
Calculate correlations between digital usage and default risk
-Risk segmentation
Compare default rates across income and digital usage segments
Identify behavioural patterns linked to higher default probability
Evaluate regional variation in customer risk profiles
