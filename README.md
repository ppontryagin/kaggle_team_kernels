# kaggle_team_kernels
Kernels for team collaboration.

## House Prices: Advanced Regression Techniques

Kaggle competition

### Description

Competition Description

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

### How to run

1. Clone repo to disk
2. Start jupyter

    2.1 As a variant it is possible to run docker container
    ```
    docker run -d -p 8888:8888 -v ~/Documents/ML_Kaggle/kaggle_team_kernels:/opt playniuniu/jupyter-pandas
    ```

    -v will map your local folder to container folder(/opt)

    2.2 Run jupyter web page
    http://127.0.0.1:8888

    2.3 Run notebook House_Prices_Advanced_Regression_Techniques.ipynb
