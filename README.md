# Capstone_Disney_AP_Grouping

This is a folder for NYUSH - NYU Stern DABC Master's Program's capstone. As a strategic pillar, annual pass (AP) of Shanghai Disney Resort not only serves as a plan to generate revenue, but also a plan to grow a community ties with the resort. Knowing AP’s importance, the project is built for analysts to generate more AP user insights and unlocking new business opportunities. Our objective is to develop an analytic model with algorithms to group current AP holders and understand their relationships using existing data. For this project, we first did data preprocessing, including cleaning data and converting data format. For the analytics model, we’ve tried Wechat grouping, network model, and clustering. Through the analysis, we found that the network model is relatively the most effective model for grouping AP holders, and Wechat grouping is helpful for validating the result produced by the network model.

It includes some coding files and the data they used. 

1. WeChat group. This file uses AP expired data to group the users which are binded on the same Wechat account.
2. Network model. https://colab.research.google.com/drive/1J6JTl4eqQnpdgAZhtKj93ScSrVuGffFa#scrollTo=szS-L8DIJGFY This file uses visitation data to build a network among the AP users. Then, the result from network is vailded by WeChat grouping result.
3. Hierarchical clustering. This file uses two kinds of clustering method to cluster the AP users by their Passtype and visitation time.
