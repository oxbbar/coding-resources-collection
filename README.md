# Coding Resources Collection

A curated list of resources, guides, cheatsheets, and tools I've found useful across various coding topics.

## Contents

- [Coding Resources Collection](#coding-resources-collection)
  - [Contents](#contents)
  - [Version Control](#version-control)
  - [Python Ecosystem](#python-ecosystem)
  - [R Ecosystem](#r-ecosystem)
  - [Databases \& SQL](#databases--sql)
  - [Machine Learning](#machine-learning)
  - [Data Formats \& Serialisation](#data-formats--serialisation)
  - [Data Platforms \& Sources](#data-platforms--sources)
  - [Business Intelligence Tools](#business-intelligence-tools)
  - [Text Editors \& General Dev Tools](#text-editors--general-dev-tools)
  - [Learning \& Practice](#learning--practice)
  - [Documentation \& Presentation](#documentation--presentation)
  - [Sections to Investigate and Add](#sections-to-investigate-and-add)

## Version Control

<details>
<summary>Git & GitHub Concepts</summary>

- [GitHub Docs](https://docs.github.com/en)
- [Pro Git Book](https://git-scm.com/book/en/v2/)
- [Atlassian - Getting Git Right](https://www.atlassian.com/git)
- [Javatpoint - GitHub Tutorial](https://www.javatpoint.com/github)
- [git/github guide, a minimal tutorial - Karl Broman](https://kbroman.org/github_tutorial/)
- [The Git Parable](https://tom.preston-werner.com/2009/05/19/the-git-parable.html)
- [What is Git? Explained in 2 Minutes! (YouTube)](https://www.youtube.com/watch?v=2ReR1YJrNOM)

</details>

<details>
<summary>Git</summary>

- [Git](https://git-scm.com/downloads)
- [How to install Git on Windows 10 | Updated 2022 (YouTube)](https://www.youtube.com/watch?v=cJTXh7g-uCM)
- [Git Installation On Windows (YouTube)](https://www.youtube.com/watch?v=2j7fD92g-gE)

</details>

<details>
<summary>Git Commands & Usage</summary>

- [Git Reference Manual](https://git-scm.com/docs/)
- [How to Write a Git Commit Message](https://cbea.ms/git-commit/#seven-rules)
- [2.7 Git Basics - Git Aliases](https://git-scm.com/book/en/v2/Git-Basics-Git-Aliases/)
- [Git status on all repos in folder - wkjagt](https://coderwall.com/p/grmruq/git-status-on-all-repos-in-folder/)
> ```bash
> `find . -maxdepth 1 -mindepth 1 -type d -exec sh -c '(echo {} && cd {} && git status -s && echo)' \;
> ```
-  [Git Tutorial 8 - .gitignore file (YouTube)](https://www.youtube.com/watch?v=ErJyWO8TGoM)

</details>

<details>
<summary>GitHub Platform</summary>

- GitHub Desktop
    - [GitHub Desktop (Git GUI)](https://desktop.github.com/)
    - [How to Use GitHub Desktop: A GitHub Desktop Tutorial](https://www.simplilearn.com/how-to-use-github-desktop-tutorial-article)
    - [Git, GitHub, & GitHub Desktop for beginners (YouTube)](https://www.youtube.com/watch?v=8Dd7KRpKeaE)

- GitKraken
    - [GitKraken](https://www.gitkraken.com/)

- GitHub Pages
    - [GitHub Pages](https://pages.github.com/)
    - [Creating a GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)
    - [What is GitHub Pages? (YouTube)](https://www.youtube.com/watch?v=2MsN8gpT6jY)
    - [Getting Started with GitHub Pages (YouTube)](https://www.youtube.com/watch?v=QyFcl_Fba-k)

- Profile & Presentation
    - [GitHub Skills](https://skills.github.com/)
    - [How to present a GitHub project for your resume](https://thehftguy.com/2016/10/24/heres-how-to-make-a-good-github-project-for-your-resume/)
    - [GitHub Profile Readme (YouTube)](https://www.youtube.com/watch?v=KhGWbt1dAKQ)
    - [How to Edit Github Readme (YouTube)](https://www.youtube.com/watch?v=-0GjKG4gRmY)

</details>

## Python Ecosystem

<details>
<summary>Core Python</summary>

- [Python](https://www.python.org/downloads/)
- [Python 3 Documentation](https://docs.python.org/3/)
- [Detailed Python developer roadmap (Reddit)](https://www.reddit.com/r/Python/comments/z3gntf/detailed_python_developer_roadmap/)

</details>

<details>
<summary>Environment Management (Conda)</summary>

- [Miniconda](https://docs.conda.io/en/latest/miniconda.html)
- [Conda Documentation](https://docs.conda.io/projects/conda/en/latest/index.html)
- [Conda User Guide - Tasks](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/index.html)
- [Install Miniconda (Python) with Jupyter Notebook... (YouTube)](https://www.youtube.com/watch?v=XCvgyvBFjyM)
- [Can anyone explain the differences of Conda vs Pip? (Reddit)](https://www.reddit.com/r/Python/comments/w564g0/can_anyone_explain_the_differences_of_conda_vs_pip/)

</details>

<details>
<summary>IDEs & Editors (Python Focus)</summary>

- [Pycharm](https://www.jetbrains.com/pycharm/)
- [Visual Studio Code (Python Docs)](https://code.visualstudio.com/docs/languages/python)

</details>

<details>
<summary>Jupyter</summary>

- [Jupyter Project Documentation](https://docs.jupyter.org/en/latest/)
- [Jupyter Notebook Shortcuts](https://towardsdatascience.com/jypyter-notebook-shortcuts-bf0101a98330)
- [How To Setup Jupyter Lab in 2022 | Data Science for Developers | 14 minutes tutorial (YouTube)](https://www.youtube.com/watch?v=BtYXPY-A9_M)
- [Here's How to Run SQL in Jupyter Notebooks](https://towardsdatascience.com/heres-how-to-run-sql-in-jupyter-notebooks-f26eb90f3259)

</details>

<details>
<summary>Python Packages</summary>

- Numpy
  - [NumPy](https://numpy.org/)
  - [NumPy Manual (Latest)](https://numpy.org/doc/stable/)

- pandas
  - [pandas](https://pandas.pydata.org/)
  - [pandas documentation](https://pandas.pydata.org/docs/)

- scikit-learn
  - [scikit-learn](https://scikit-learn.org/stable/index.html)
  - [Scikit-learn User Guide](https://scikit-learn.org/stable/user_guide.html)
  - [Scikit-learn API Reference](https://scikit-learn.org/stable/api/index.html)
  - [Scikit-learn Tutorials](https://scikit-learn.org/1.4/tutorial/index.html)

- Matplotlib
  - [Matplotlib](https://matplotlib.org/)
  - [Matplotlib documentation](https://matplotlib.org/stable/index.html)

- seaborn
  - [seaborn](https://seaborn.pydata.org/)
  - [seaborn tutorial](https://seaborn.pydata.org/tutorial.html)

- statsmodels
  - [statsmodels](https://www.statsmodels.org/stable/index.html)
  - [statsmodels User Guide](https://www.statsmodels.org/stable/user-guide.html)

- PyGWalker
  - [PyGWalker](https://kanaries.net/pygwalker)
  - [PyGWalker docs](https://docs.kanaries.net/pygwalker)

</details>

## R Ecosystem

<details>
<summary>Core R</summary>

- [R](https://cran.rstudio.com/)
- [R Documentation](https://www.rdocumentation.org/)
- [CRAN (R Source/Downloads)](https://cran.rstudio.com/)

</details>

<details>
<summary>Tidyverse & ggplot2</summary>

- [Tidyverse.org](https://www.tidyverse.org/)
- [ggplot2 Documentation](https://ggplot2.tidyverse.org/)
- [ggplot2: Elegant Graphics for Data Analysis (Book Website)](https://ggplot2-book.org/index.html)
- [ggplot2 Cheatsheet (RStudio)](https://github.com/rstudio/cheatsheets/blob/main/ggplot2.pdf)

</details>

<details>
<summary>Learning R</summary>

- [Statistics Globe - Learn R Programming](https://statisticsglobe.com/r-programming-language)

</details>

<details>
<summary>IDEs (R Focus)</summary>

- [RStudio Desktop](https://posit.co/download/rstudio-desktop/)
- [RStudio Cheatsheets (General Link)](https://www.rstudio.com/resources/cheatsheets/)

</details>

## Databases & SQL

<details>
<summary>SQL Fundamentals & Style</summary>

- [SQL Style Guide](https://www.sqlstyle.guide/)

</details>

<details>
<summary>PostgreSQL</summary>

- [PostgreSQL Documentation](https://www.postgresql.org/docs/)
- [PostgreSQL Downloads](https://www.postgresql.org/download/)

</details>

<details>
<summary>SQLite</summary>

- [SQLite](https://www.sqlite.org/download.html)
- [Introducing SQLite (Tutorial)](http://sqlite.awardspace.info/syntax/sqlitepg01.htm)
- [Command Line Shell For SQLite](https://www.sqlite.org/cli.html)
- [SQLite Downloads](https://www.sqlite.org/download.html)
- [How to Install SQLite on Windows 10... (SQLite3)](https://cloudinfrastructureservices.co.uk/how-to-install-sqlite-on-windows-10-2016-2019-2022-sqlite3/)
- [DB Browser for SQLite (Tool)](https://sqlitebrowser.org/dl/)

</details>

<details>
<summary>Database Comparisons</summary>

- [SQLite vs MySQL vs PostgreSQL: A Comparison Of RDBMS](https://www.digitalocean.com/community/tutorials/sqlite-vs-mysql-vs-postgresql-a-comparison-of-relational-database-management-systems)

</details>

## Machine Learning

<details>
<summary>Core Concepts & Theory</summary>

- [Elements of Statistical Learning (Book - Advanced)](https://hastie.su.domains/ElemStatLearn/)
- [Introduction to Statistical Learning (Book - Applied w/ R Labs)](https://www.statlearning.com/)
- [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course)

</details>

<details>
<summary>Preprocessing & Pipelines</summary>

- Pipelines
  - [sklearn.pipeline.Pipeline](https://scikit-learn.org/stable/modules/generated/sklearn.pipeline.Pipeline.html)
  - [User Guide: Pipelines and Composite Estimators](https://scikit-learn.org/stable/modules/compose.html#pipeline)

- Scaling
  - [sklearn.preprocessing.StandardScaler](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html)
  - [sklearn.preprocessing.MinMaxScaler](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.MinMaxScaler.html)
  - [sklearn.preprocessing.RobustScaler](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.RobustScaler.html)
  - [User Guide: Preprocessing data (Scaling)](https://scikit-learn.org/stable/modules/preprocessing.html#scaling-features-to-a-range)

- Dimensionality Reduction (PCA)
  - [sklearn.decomposition.PCA](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html)
  - [User Guide: Principal component analysis (PCA)](https://scikit-learn.org/stable/modules/decomposition.html#pca)'

- Encoding Categorical Features
  - [pandas.get_dummies](https://pandas.pydata.org/docs/reference/api/pandas.get_dummies.html)
  - [sklearn.preprocessing.OneHotEncoder](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.OneHotEncoder.html)
  - [User Guide: Encoding categorical features](https://scikit-learn.org/stable/modules/preprocessing.html#encoding-categorical-features)

</details>

<details>
<summary>Model Selection & Hyperparameter Tuning</summary>

- GridSearchCV
  - [sklearn.model_selection.GridSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.GridSearchCV.html)
  - [User Guide: Tuning the hyper-parameters of an estimator](https://scikit-learn.org/stable/modules/grid_search.html)
  - [Grid Search VS Random Search VS Bayesian Optimization](https://medium.com/data-science/grid-search-vs-random-search-vs-bayesian-optimization-2e68f57c3c46)

- RandomizedSearchCV
  - [sklearn.model_selection.RandomizedSearchCV](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.RandomizedSearchCV.html)

- Cross-Validation
  - [User Guide: Cross-validation: evaluating estimator performance](https://scikit-learn.org/stable/modules/cross_validation.html)
  - [sklearn.model_selection.StratifiedKFold](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.StratifiedKFold.html)
  - [sklearn.model_selection.StratifiedShuffleSplit](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.StratifiedShuffleSplit.html)
  - [sklearn.model_selection.cross_val_score](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.cross_val_score.html)
  - [sklearn.model_selection.cross_validate](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.cross_validate.html) (Allows multiple metrics)

</details>

<details>
<summary>Model Evaluation & Metrics</summary>

- [User Guide: Model evaluation](https://scikit-learn.org/stable/modules/model_evaluation.html)

- Classification Metrics
  - [sklearn.metrics.accuracy_score](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.accuracy_score.html)
  - [sklearn.metrics.precision_score](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.precision_score.html)
  - [sklearn.metrics.recall_score](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.recall_score.html)
  - [sklearn.metrics.f1_score](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.f1_score.html)
  - [sklearn.metrics.classification_report](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.classification_report.html)
  - [sklearn.metrics.confusion_matrix](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.confusion_matrix.html)
  - [sklearn.metrics.ConfusionMatrixDisplay](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.ConfusionMatrixDisplay.html)

- ROC Curve & AUC
  - [sklearn.metrics.roc_curve](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.roc_curve.html)
  - [sklearn.metrics.auc](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.auc.html)
  - [sklearn.metrics.RocCurveDisplay](https://scikit-learn.org/stable/modules/generated/sklearn.metrics.RocCurveDisplay.html)

</details>

<details>
<summary>Specific Models</summary>

- Support Vector Machines (SVM)
  - [sklearn.svm.SVC](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html)
  - [User Guide: Support Vector Machines](https://scikit-learn.org/stable/modules/svm.html)

- Decision Trees
  - [sklearn.tree.DecisionTreeClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html)
  - [User Guide: Decision Trees](https://scikit-learn.org/stable/modules/tree.html)

- Naive Bayes
  - [sklearn.naive_bayes.CategoricalNB](https://scikit-learn.org/stable/modules/generated/sklearn.naive_bayes.CategoricalNB.html)
  - [User Guide: Naive Bayes](https://scikit-learn.org/stable/modules/naive_bayes.html)

- Logistic Regression
  - [sklearn.linear_model.LogisticRegression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)
  - [User Guide: Logistic Regression](https://scikit-learn.org/stable/modules/linear_model.html#logistic-regression)
  - [statsmodels.discrete.discrete_model.Logit](https://www.statsmodels.org/stable/generated/statsmodels.discrete.discrete_model.Logit.html) (If you want to keep the statsmodels reference)

</details>

## Data Formats & Serialisation

<details>
<summary>JSON (JavaScript Object Notation)</summary>

JSON (JavaScript Object Notation) is a lightweight data-interchange format. It is easy for humans to read and write. It is easy for machines to parse and generate. 

- [Introducing JSON](https://www.json.org/json-en.html) (Official Site & Grammar)
- [MDN Web Docs - JSON](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON)
- [JSONLint Editor](https://jsonlint.com/)
  - JSONLint is a validator and reformatter for JSON.
- [JSON Validator - Code Beautify](https://codebeautify.org/jsonvalidator)
  - JSON Validator is an easy-to-use tool to validate JSON data.

</details>

## Data Platforms & Sources

<details>
<summary>Kaggle</summary>

- [Main Site](https://www.kaggle.com/)
- [How to Use Kaggle (Docs)](https://www.kaggle.com/docs)
- [Kaggle Datasets](https://www.kaggle.com/datasets)
- [How to Enter a Kaggle Competition (using Kernels) | Kaggle (YouTube)](https://www.youtube.com/watch?v=GJBOMWpLpTQ)

</details>

<details>
<summary>Open Data Portals & Repositories</summary>

- [Google Dataset Search](https://datasetsearch.research.google.com/)
- [data.gov (US)](https://data.gov/)
- [data.gov.au (Australia)](https://data.gov.au/)
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets.php)
- [Earth Data (NASA)](https://earthdata.nasa.gov/)
- [CERN Open Data Portal](http://opendata.cern.ch/)
- [Global Health Observatory Data Repository (WHO)](https://apps.who.int/gho/data/node.home)
- [FBI Crime Data Explorer](https://crime-data-explorer.fr.cloud.gov/)
- [Datahub.io](https://datahub.io/collections)

</details>

<details>
<summary>Specific Datasets</summary>

- [BFI film industry statistics](https://www.bfi.org.uk/education-research/film-industry-statistics-research)
- [NYC Taxi Trip Data](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

</details>


## Business Intelligence Tools

<details>
<summary>Tableau</summary>

- [Tableau](https://www.tableau.com/)
- [Tableau Desktop](https://www.tableau.com/products/desktop)
- [Tableau Public](https://public.tableau.com/app/discover)
- [Tableau Public Desktop](https://www.tableau.com/products/public/download)

</details>

<details>
<summary>PowerBI</summary>

- [Power BI](https://www.microsoft.com/en-us/power-platform/products/power-bi)
- [Power BI Desktop](https://www.microsoft.com/en-us/power-platform/products/power-bi/desktop)

</details>

## Text Editors & General Dev Tools

<details>
<summary>Visual Studio Code</summary>

- [Visual Studio Code](https://code.visualstudio.com/)

</details>

<details>
<summary>Vim</summary>

- [Vim](https://www.vim.org/)
- [Vimtutor](https://vimschool.netlify.app/introduction/vimtutor/)
- [Vim Documentation: editing.txt](https://vimhelp.org/editing.txt.html)

</details>

## Learning & Practice

<details>
<summary>LeetCode</summary>

- [LeetCode - Easy Problems Filter](https://leetcode.com/problemset/all/?difficulty=EASY&page=1&status=NOT_STARTED)

</details>

<details>
<summary>Stack Overflow</summary>

- [Stack Overflow](https://stackoverflow.com/)

</details>

## Documentation & Presentation

<details>
<summary>General Documentation</summary>

- [The Documentation Compendium - race2infinity](https://github.com/race2infinity/The-Documentation-Compendium)

</details>

<details>
<summary>Markdown</summary>

- [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)

</details>

## Sections to Investigate and Add

- Cloud Platforms: AWS, Azure, GCP, Heroku, etc.
- Docker/Containers
- Web Frameworks: Flask, Django, FastAPI, Node.js, React, etc.
- Machine Learning Concepts/Theory
- Statistics Resources
- Shell/Command Line (Bash/Zsh)
- Regular Expressions