## US Medical Insurance Costs

### Description

The dataset provides information on health insurance costs for people from different regions of the United States.<br>
All the information is contained in the **insurance.csv** file.

The dataset consists of the following columns:
- ***age*** - numeric discrete variable;
- ***sex*** - categorical binary variable;
- ***bmi*** - numeric continuous variable;
- ***children*** - numeric discrete variable;
- ***smoker*** - categorical binary variable;
- ***region*** - categorical nominal variable;
- ***charges*** - numeric continuous variable.

### Project Aims

- Determine which variables have the greatest impact on insurance costs (charges).
- Find the average insurance costs for each value, for each group.
- Visualize results with charts.
- Draw conclusions.

### Installation

**NOTE:** Python3 must be already installed.

```
git clone https://github.com/Vasyl-Poremchuk/us-medical-insurance-costs

cd us-medical-insurance-costs

python -m venv venv

venv\Scripts\activate (Windows) or source venv/bin/activate (Linux or macOS)

pip install -r requirements.txt
```