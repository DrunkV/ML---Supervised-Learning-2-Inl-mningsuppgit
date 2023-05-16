# ML---Supervised-Learning-2-Inl-mningsuppgit

I det här projektet används Boston fil som har som categorical och numerical variabler, CRIM, ZN, INDUS, CHAS, NOX, RM, AGE, DIS, RAD, TAX, PTRATIO, B, LSTAT och target;

Vi inspekterar data med shape(), head() och tail(), value_counts(), dtypes(), och target();

Kolumner som behövs inte eller är duplicates, använder vi drop() för att dropna dessa alltså, vi dropade "Unnamed" kolumn;

Describe() vissar oss numerical data och isnull() om det finns nulla värde som behövs fyla i in.

Skapade en ny dataframe bara med variabler som var relevanta till X;

Concat för att slår ihop X och y;

corr för korrelationen;

För korrelationens visualization, använt vi Seaborn heatmap;

train_test_split module delar data medan träna och testa dataset. Tränning blir 70% och testa 30%;

LinearRegression för att tränar modellen med data;

Ridge och Lasso är andra regressionsmodeller 

Predic och R2 för att ser hur bra är modellen;

Mean och Absolute error för att ser modellens error;

Med K - Cross Validation module (cross_val_score) validerar vi om hur bra är modellen;

Med GridSearchCv väljer vi bästa kombination värde från k-cross-validation;

RandomizedSearchCV används slump kombinationer för att hitta en score. Är snabbare än GridSearch fast inte så rätt som GridSearch;

Till slut har vi två andra regressionsmodeller: Elasticnet och RandomForestRegessor. Dessa två har jag bara lekt lite och jag inte riktig förstått
till vilka data passar bättre.


