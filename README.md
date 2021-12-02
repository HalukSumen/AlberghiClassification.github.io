
# Alberghi Classification


## Exploratory Data Analysis + Data Visualization + Modelling 

### 1 - Introduction

### 2 - Data

Dataset contains 6775 rows and 25 columns.
Description and Type of Each Column;

* __ID                       *int64*__   - id
* __PROVINCIA               *object*__   - id of state
* __COMUNE                  *object*__   - name of city
* __LOCALITA                *object*__   - name of town
* __CAMERE                   *int64*__   - number or rooms
* __SUITE                    *int64*__   - number of suites
* __LETTI                    *int64*__   - number of beds
* __BAGNI                    *int64*__   - number of bathrooms
* __PRIMA_COLAZIONE          *int64*__   - breakfast included or not
* __IN_ABITATO             *float64*__   - building or not
* __SUL_LAGO               *float64*__   - close to lake or not
* __VICINO_ELIPORTO        *float64*__   - close to heliport or not
* __VICINO_AEREOPORTO      *float64*__   - close to airport or not
* __ZONA_CENTRALE          *float64*__   - in the central or not
* __VICINO_IMP_RISALITA    *float64*__   -
* __ZONA_PERIFERICA        *float64*__   - suburb or not
* __ZONA_STAZIONE_FS       *float64*__   - close to station or not
* __ATTREZZATURE_VARIE      *object*__   - equipment types( elevator, park, restaurants etc.)
* __CARTE_ACCETTATE         *object*__   - accepted credit cards (visa,mastercard etc.)
* __LINGUE_PARLATE          *object*__   - spoken languages by host or hotel
* __SPORT                   *object*__   - sport options (football, table tennis etc.)
* __CONGRESSI               *object*__   - congress room(s)
* __LATITUDINE             *float64*__   - latitude
* __LONGITUDINE            *float64*__   - longitude
* __OUTPUT                  *object*__   - types of places

### 3 - Exploratory Data Analysis

Firslty, I checked data types and number of Nan in each columns. Later this process I decided which columns I will delete and which rows should I delete. So I deleted *LOCALITA - SPORT - CONGRESSI - LATITUDINE - LONGITIDUNE* columns and I deleted in NaN rows in *IN_ABITATO -SUL_LAGO - VICINO_ELIPORTO - VICINO_AEREOPORTO - ZONA_CENTRALE - VICINO_IMP_RISALITA - ZONA_PERIFERICA - ZONA_STAZIONE_FS* columns.

### 4 - Data Visualization

### 5 - Modelling 

* 5.1 - Logistic Regression
* 5.2 - K Neighbors Classification
* 5.3 - Decision Tree Classification
* 5.4 - Random Forest Classification
* 5.5 - AdaBoost Classification
* 5.6 - Gradient Boosting Classification
* 5.7 - XGB Classification
* 5.8 - ExtraTrees Classification
* 5.9 - Bagging Classification

### 6 - Result & Future Work
