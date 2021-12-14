# Ontology based Literature Mining and Indexing of Leukemia

# Introduction

The development of most types of leukemia increases with age, also different types of leukemia have different types of risk factors involved. In this project we have discussed the problem of finding the right research paper for a particular topic. Our topic is Leukemia and its subtypes(AML,ALL,CML,CLL). When we were trying to find articles related to leukemia there were many other papers being displayed in the search result. For the dataset we have downloaded abstracts for each type of leukemia and converted the TXT format files into XML format with help of Mendeley and structured our own dataset. Our aim here is to develop a model that automatically classifies the abstracts of the literature into one of the leukemia related categories using machine learning method when they are entered. Such a model would allow people to search the literature more efficiently and improve the accuracy of the search.

# Authors
Ziyuan Xu, Shijie Zhou, Minakshi

# Dataset

We’ve downloaded 50 abstracts of literature on each subtype of leukemia(AML, ALL, CML, CLL) from PubMed respectively and acquired a total of 200 TXT format files. These texts are unstructured natural language texts, so we need to structure and classify them. In this project, we are using Mendeley to convert these texts into XML format files. Then, in order to build our own dataset, we extracted some important attributes from these XML files: authors, title, year, electronic-resource-num, periodical, abstract. These attributes will be used as column names. Additionally, we added an attribute to the column name, namely paper_id. 

# Screenshot of dataset

![Capture](https://user-images.githubusercontent.com/96027933/145858538-d39d3006-c4b1-461e-829f-8a5b0d1f4c46.PNG)

  
# Steps to run code

First download Python

Go to your browser-> type python-> Download latest version from www.python.org/downloads/ -> Install it on your machine

To check if python is installed on machine-> type cmd on window search-> type py and enter-> it will show the result

Again go to your browser-> type anaconda-> Download anaconda individual edition from www.anaconda.com/products/individual -> Install it on your machine

To check if anaconda is installed on machine-> type anaconda on window search-> open anaconda navigator

pip install tensorflow and jupyter notebook in Anoconda prompt 

Activate tensorflow then open jupyter notebook -> upload the project file and run

# Screenshot of code

![MicrosoftTeams-image](https://user-images.githubusercontent.com/96027933/145917694-53aa6f76-fced-450a-8ca5-ef08ff72aa5b.png)

![MicrosoftTeams-image (1)](https://user-images.githubusercontent.com/96027933/145917738-c3e7d5d3-9f7a-4314-8507-867ff43d9832.png)

![MicrosoftTeams-image (2)](https://user-images.githubusercontent.com/96027933/145917787-d700768f-4360-4bc2-a6df-0da610e7e86f.png)

![MicrosoftTeams-image (3)](https://user-images.githubusercontent.com/96027933/145917833-96f4397c-7836-4717-ad18-838e49bec698.png)

![MicrosoftTeams-image (4)](https://user-images.githubusercontent.com/96027933/145917873-83590c23-119a-4944-a376-85a117eec36c.png)

![MicrosoftTeams-image (5)](https://user-images.githubusercontent.com/96027933/145917926-dbf7269b-0d6c-48eb-a4c2-d052948699c9.png)

![MicrosoftTeams-image (6)](https://user-images.githubusercontent.com/96027933/145917982-fb30c51d-acad-4084-a62a-e63f50c7b63d.png)

![MicrosoftTeams-image (7)](https://user-images.githubusercontent.com/96027933/145918055-c0643dd0-a52c-47be-970e-7f52a2125d43.png)

