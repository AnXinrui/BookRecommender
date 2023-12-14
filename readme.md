基于聚类(KNN) 与协同过滤的图书推荐系统

> pyspark 进行高效数据处理
>
> knn 实现协同过滤

[project address][https://book-recommender-fnq9.onrender.com/]

[data-link: book dataset](https://www.kaggle.com/datasets/ra4u12/bookrecommendation/data)

#### 目录结构

│  app.py\
│  Books-Recommender.ipynb  
│  readme.md\
│  requirements.txt\
│  
├─.ipynb_checkpoints\
│&emsp;app-checkpoint.py\
│&emsp;Books-Recommender-checkpoint.ipynb\
│&emsp;readme-checkpoint.md
│      
├─artifacts\
│&emsp;book_names.pkl\
│&emsp;book_pivot.pkl\
│&emsp;final_rating.pkl\
│&emsp;model.pkl
│      
└─data\
     &emsp;BX-Book-Ratings.csv\
     &emsp;BX-Books.csv\
     &emsp;BX-Users.csv\
        
   

#### 快速运行：

1. 克隆本仓库并下载

2. 创建虚拟环境并且进入项目目录

```bash
conda create -n env_name python=3.11 -y
```

```bash
conda activate env_name
```

3. 安装需要的包

```bash
pip install -r requirements.txt
```

4. 运行该项目

```bash
streamlit run app.py
```

