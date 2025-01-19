# Titanic Dataset Overview

The Titanic dataset provides information on the passengers aboard the Titanic, which sank after hitting an iceberg. The dataset is commonly used for binary classification tasks, such as predicting whether a passenger survived or not.

## Data Fields

- **PassengerId**: Unique identifier for each passenger.
- **Survived**: Survival status (0 = No, 1 = Yes).
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd).
- **Name**: Name of the passenger.
- **Sex**: Gender of the passenger.
- **Age**: Age of the passenger.
- **BirthYear**: Birth year of the passenger.
- **SibSp**: Number of siblings or spouses aboard the Titanic.
- **Parch**: Number of parents or children aboard the Titanic.
- **Ticket**: Ticket number.
- **Fare**: Passenger fare.
- **Cabin**: Cabin number.
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).

## Example Data
| PassengerId | Survived | Pclass | Name                                         | Sex    | Age | SibSp | Parch | Ticket    | Fare    | Cabin | Embarked | BirthYear |
|-------------|----------|--------|----------------------------------------------|--------|-----|-------|-------|-----------|---------|-------|----------|-----------| 
| 846         | 0        | 3      | Abbing, Mr. Anthony                          | male   | 0   | 0     | 0     | C.A. 5547 | 7.55    |       | S        | 1870      |
| 847         | 0        | 3      | Sage, Mr. Douglas Bullen                     | male   | 8   | 2     | 0     | CA. 2343  | 69.55   |       | S        | 1904      |
| 848         | 0        | 3      | Markoff, Mr. Marin                           | male   | 0   | 0     | 0     | 349213    | 7.8958  |       | C        | 1870      |
| 849         | 0        | 2      | Harper, Rev. John                            | male   | 0   | 1     | 0     | 248727    | 33      |       | S        | 1870      |
| 850         | 1        | 1      | Goldenberg, Mrs. Samuel L (Edwiga Grabowska) | female | 1   | 0     | 0     | 17453     | 89.1042 | C92   | C        | 1911      |

## Usage

This dataset can be used for various data analysis and machine learning tasks, such as:

- Predicting survival based on passenger attributes.
- Analyzing the impact of socio-economic status on survival rates.
- Exploring the demographics of the Titanic passengers.

## Source

The dataset is available on [Kaggle](https://www.kaggle.com/c/titanic/data).