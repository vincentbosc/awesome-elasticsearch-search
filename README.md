# wonderful-elasticsearch
Wonderful Elasticsearch - A classified list of useful links to blog-articles/documentations.
Inspired by the great [awesome-search repo](https://github.com/frutik/awesome-search), but focused on Elasticsearch.

## Topics

* [Traditional Search](#traditional-search)
  * [Sorting](#sorting)
* [Vector Search](#vector-search)
  * [Dense Vectors](#dense-vectors)
    * [HSNW](#hsnw)
    * [Quantization](#quantization)
  * [Sparse Vectors](#sparse-vectors)
    * [ELSER](#elser)
* [Hybrid Search]   
  * [Retrievers](#retrievers)
  * [RRF](#rrf)
* [Rerankers](#rerankers)
  * [Semantic rerankers](#semantic-rerankers)
  * [LTR](#ltr)
* [RAG](#rag)
* [NLP Tasks](#nlp-tasks)
* [Benchmarking](#benchmarking)
  * [Relevance](#relevance)
  * [Esrally](#esrally)
  * [Useful datasets](#useful-datasets)

# Search

* [Search tutorial](https://www.elastic.co/search-labs/tutorials/search-tutorial/welcome) - app in Flask

## Traditional Search (BM25)
* [Languages with compound words](https://www.elastic.co/search-labs/blog/compound-word-search)

  ### Sorting
* [Optimizing sort queries](https://www.elastic.co/blog/optimizing-sort-queries-in-elasticsearch-for-faster-results) - blog

## Vector Search
* [A quick introduction to Vector Search](https://www.elastic.co/search-labs/blog/introduction-to-vector-search) - blog
* [Elasticsearch vs Opensearch performance](https://www.elastic.co/search-labs/blog/elasticsearch-opensearch-vector-search-performance-comparison) - blog

  ### Dense vectors

    #### HSNW
* [Multi HSNW Graph Vector Search](https://www.elastic.co/search-labs/blog/multi-graph-vector-search) - blog
* [Elastic Meetup - How HSNW works](https://www.youtube.com/watch?v=ly_COu_sHtI) - video (in French)
* [Brute Force vs HSNW](https://www.elastic.co/search-labs/blog/knn-exact-vs-approximate-search) - blog
* [Improved filter + HNSW in v9](https://www.elastic.co/search-labs/blog/filtered-hnsw-knn-search) - blog

    #### Quantization
* [Scalar quantization](https://www.elastic.co/search-labs/blog/evaluating-scalar-quantization) - blog
* [RaBitQ binary quantization](https://www.elastic.co/search-labs/blog/rabitq-explainer-101) - blog
* [BBQ quantization vs Product Quantization](https://www.elastic.co/search-labs/blog/bit-vectors-elasticsearch-bbq-vs-pq) - blog
* [Scalar quantization optimization](https://www.elastic.co/search-labs/blog/optimized-scalar-quantization-elasticsearch) - blog
* [Scalar quantization optimization - Math heavy](https://www.elastic.co/search-labs/blog/scalar-quantization-optimization) - blog

  ### Sparse vectors

    #### ELSER

* [App which compares ELSER and BM25](https://github.com/elastic/elasticsearch-labs/tree/main/example-apps/relevance-workbench) - app in Flask and React (github)

## Hybrid Search

* [KNN and filters](https://softwaredoug.com/blog/2025/02/08/elasticsearch-hybrid-search) - blog

  ### Retrievers
* [Retrievers Introduction](https://www.elastic.co/search-labs/blog/elasticsearch-retrievers-ga-8.16.0) - blog
* [Retrievers using semantic reranking](https://www.elastic.co/search-labs/blog/semantic-reranking-with-retrievers) - blog

  ### RRF
* [Hybrid Search using RRF](https://www.elastic.co/search-labs/blog/hybrid-search-elasticsearch) - blog
* [Is RRF enough?](https://softwaredoug.com/blog/2024/11/03/rrf-is-not-enough) - blog

## Rerankers

  ### Semantic rerankers
* [Documentation](https://www.elastic.co/guide/en/elasticsearch/reference/current/semantic-reranking.html#semantic-reranking-in-es)
* [What is a semantic reranker?](https://www.elastic.co/search-labs/blog/elastic-semantic-reranker-part-1) - blog
* [How to - Use a reranker from Hugging Face](https://www.elastic.co/search-labs/blog/reranking-elasticsearch-hugging-face) - blog
* [Rethinking rerankers](https://haystackconf.com/eu2024/talk-2/) - Haystack video
 
  ### LTR
* [Documentation](https://www.elastic.co/guide/en/elasticsearch/reference/current/learning-to-rank.html)
* [LTR Introduction](https://www.elastic.co/search-labs/blog/elasticsearch-learning-to-rank-introduction) - blog
* [Personalized search with LTR](https://www.elastic.co/search-labs/blog/personalized-search-elasticsearch-ltr) - blog

## RAG
* [Rag demo](https://esre-openai-sample-app.prod-3.eden.elastic.dev/) - eden demo (internal)
* [Elastic Chat RAG App](https://github.com/elastic/elasticsearch-labs/tree/main/example-apps/chatbot-rag-app) - app in Flask (github)
* [Rag using Graph](https://www.youtube.com/watch?v=_oQzsOu2ok4) - video (in French)

## Facets
* [Fuzzy facets with binary vectors](https://www.youtube.com/watch?v=sJU_8mtzH7Y)

## NLP Tasks

## Benchmarking

  ### Relevance
* [What is a judgment list](https://softwaredoug.com/blog/2021/02/21/what-is-a-judgment-list) - blog
* [Rankeval](https://www.elastic.co/guide/en/elasticsearch/reference/current/search-rank-eval.html) - documentation
* [Rated Ranking Evaluator](https://github.com/SeaseLtd/rated-ranking-evaluator) - github
* [Quepid](https://github.com/o19s/quepid) - github
* [BEIR](https://github.com/beir-cellar/beir) - github

  ### Esrally
* [Official documentation]
* [Wikipedia example](https://github.com/elastic/rally-tracks/tree/master/wikipedia) - github
* [Guide to creating custom tracks](https://www.elastic.co/blog/creating-custom-es-rally-tracks-guide) - blog

  ### Useful datasets
* [Amazon shopping queries](https://github.com/amazon-science/esci-data/tree/main) - github
  * [Example of use](https://frutik.medium.com/playing-with-amazons-shopping-queries-datase-part-i-da24092aefa5) - blog
* [WANDS](https://github.com/wayfair/WANDS) - github
  * [Example of use with BM25](https://colab.research.google.com/drive/1yqSJg-99j1uv62CMKD4UC5ahdB1n7HO5?usp=sharing) - Google Collab
 
## Unordered links
* [Serverless going GA](https://www.elastic.co/search-labs/blog/elasticsearch-serverless-now-ga) - blog

