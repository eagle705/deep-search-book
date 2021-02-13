---
layout: default
title: Retrieval Model
parent: Information Retrieval
nav_order: 1
---

# 시작하기 전에

## Relevance
흔히들 검색을 얘기할때 가장 많이 등장하는 단어가 있습니다. 바로 Relevance입니다. 대학교 때 한학기 수업을 듣고나서 가장 마지막에 기억에 남는 단어이기도 하죠.
검색에서 Relevance는 매우 중요한 개념입니다. 검색 결과가 적합한지 따지는게 생각보다 복잡하기 때문입니다.

예를들어, ```에이브러햄 링컨```이라는 질의가 들어왔다고 가정해봅시다. 
결과로 나온 문서는 단순히 ```U.S presidents의 리스트```를 포함한 문서입니다. 과연 이 결과는 relevance한 결과라 볼 수 있을까요?
아마 사용자가 ```에이브러햄 링컨``` 이라고 검색했을땐, 단순히 ```U.S presidents의 리스트```가 아닌 링컨의 생애에 대한 더 자세한 정보를 원했을 겁니다. topcial relevance(주제 적합성) 관점에서 본다면, 적합한 결과라 볼 수 있지만, user relevance(사용자 적합성) 관점에서 본다면 적절하지 못한 결과라고 할 수 있습니다. 이처럼 relevance는 어떻게 바라보냐에 따라 질의에 대한 검색 결과가 적합하기도하고 그렇지 않기도 하다고 할 수 있습니다.

## Overview

- Older Models
    - Boolean Retrieval Model
    - Vector Space Model
- Probabilistic Models
    - BM25
    - Language models
- Machine Learning and Information Retrieval
    - Learning to Rank
    - Topic Models

    