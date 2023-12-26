# HiRegEx: Interactive Visual Query and Exploration of Multivariate Hierarchical Data

This is the code repository for HiRegEx/TreeQueryER.

We develop TreeQueryER, a novel visual analytics system that integrates our exploratory framework for multivariate hierarchical data.
TreeQueryER consists of top-down pattern specification, bottom-up data-driven inquiry, and context-creation data overview.
For the top-down mode, we introduce a visual construction approach supporting users in authoring HiRegEx query expressions interactively. 
For the bottom-up mode, we develop a recommendation algorithm based on hierarchical data collection and user-specified query expressions. 
For the context-creation mode, we propose a graph contrastive learning method considering the features of hierarchical data to construct an overview of hierarchical data collection.

**To help understand TreeQueryER, the YouTube URL of the video is:** https://youtu.be/_m4x0639SL4

## Pipeline
![](./image/pipeline.png)

## Run FrontEnd
```
cd ./FrontEnd
```

Project setup
```
npm install
```

Compiles and hot-reloads for development
```
npm run serve
```

Compiles and minifies for production (only for finishing the whole project)
```
npm run build
```

## Run BackEnd
```
cd ./BackEnd
```

Project setup
```
python communicator.py
```

