# Task_1.4_Data_Wrangling_Challenge

## Objetivo del Ejercicio
El desafío se llevó a cabo en pares, donde cada estudiante actuó en dos roles:

Data Creator (Creador de Datos): Seleccionar un dataset original y aplicar intencionalmente al menos 10 tipos de inconsistencias y errores (datos faltantes, outliers, inconsistencias de formato, etc.).

Data Cleaner (Limpiador de Datos): Recibir el dataset "sucio" del compañero, identificar sistemáticamente todos los errores, aplicar las técnicas de limpieza necesarias y, finalmente, realizar un análisis exploratorio básico.

## Enunciado (Inglés)

Step 1: Form Pairs
Students will form pairs (Student A & Student B).

Both students act as “Data Creator” and  “Data Cleaner”.

Firstly, you work as Data Creator and send a dirty dataset to your partner
Then, you work as Data Cleaner with the other dataset your partner have sent you
Step 2: Data Selection 
Each student chooses a dataset they are interested in (from sources like Kaggle, government open data portals, or their own research).

The dataset should have at least 100 rows and 5 columns.

Students do not share their dataset yet.

Step 3: Data Dirtying (Data Creator)
The Data Creator will modify the dataset to make it messy, including at least 10 types of errors from the list below:

Missing data: Remove or leave blank some values randomly.

Duplicated rows: Add exact or partial duplicates.

Outliers: Insert extreme values in numeric columns.

Format inconsistencies: Change date formats, numeric formats, or units.

Typographical errors: Introduce spelling mistakes in categorical columns.

Extra categories: Add unusual values in categorical columns to simulate errors.

Incorrect data types: Store numbers as strings or vice versa.

No default codification of file (utf-8?)
Incorrect headers
Extra punctuation symbols (1000€)
... Ask IA for creative ways to dirty a dataset
The data creator uses only python to dirty the original dataset.

Send the dirty dataset to the data cleaner.

Step 4: Data Cleaning (Data Cleaner)
Receive the dirty dataset from the Data Creator.

Identify and fix all inconsistencies and errors.

Tasks may include:

Filling missing data or deciding how to handle them.

Removing duplicates.

Correcting formatting and data types.

Correcting spelling mistakes and consolidating categories.

Handling outliers appropriately.

Step 5: Analysis
After cleaning, perform a basic analysis:

Summary statistics (mean, median, mode).

Frequency counts of categorical variables.

Basic visualization (histograms, bar plots, boxplots...)

...
Step 6: Submission
Submit two reports:

Dirty dataset and description: notebook explaining what and how errors were introduced.

Cleaned dataset and analysis report: Explain cleaning steps and findings.