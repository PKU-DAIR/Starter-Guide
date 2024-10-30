<p align="center">
    <h1 align="center">💽 Database方向</h1>
    <p align="center">入门指南</p>
    <p align="center">
        <a href="https://github.com/PKU-DAIR">
            <img alt="Static Badge" src="https://img.shields.io/badge/%C2%A9-PKU--DAIR-%230e529d?labelColor=%23003985">
        </a>
        <a href="https://github.com/PKU-DAIR">
            <img alt="Static Badge" src="https://img.shields.io/badge/PKU--DAIR-black?logo=github">
        </a>
    </p>
</p>

> 注:⚡为**基础必读**,💎为**基础选读**,💡为**进阶阅读**

### AI4DB

<details open>
<summary>

##### Survey

</summary>

- `⚡` 📄 [Database Meets Artificial Intelligence: A Survey](https://ieeexplore.ieee.org/abstract/document/9094012)

</details>


### Database Configuration

<details open>
<summary>

##### Knob Tuning

</summary>

- `⚡` 📄 [Facilitating Database Tuning with Hyper-Parameter OptimizationA Comprehensive Experimental Evaluation](https://arxiv.org/pdf/2110.12654)
- `⚡` 📄 [Automatic database management system tuning through large-scale machine learning](https://dl.acm.org/doi/pdf/10.1145/3035918.3064029)

</details>

<details open>
<summary>

##### Index Advisor

</summary>

- `⚡` 📄 [Magic mirror in my hand, which is the best in the land? An Experimental Evaluation of Index Selection Algorithms](https://www.vldb.org/pvldb/vol13/p2382-kossmann.pdf)
- `⚡` 📄 [An efficient, cost-driven index selection tool for Microsoft SQL server](https://www.vldb.org/conf/1997/P146.PDF)

</details>

### Database Design

<details open>
<summary>

##### Learned Index

</summary>

- `⚡` 📄 [The case for learned index structures](https://dl.acm.org/doi/10.1145/3183713.3196909)
- `⚡` 📄 [ALEX: An Updatable Adaptive Learned Index](https://dl.acm.org/doi/10.1145/3318464.3389711)

</details>

### Query Optimization

<details open>
<summary>

##### Cardinality Estimation

</summary>

- `⚡` 📄 [Are We Ready For Learned Cardinality Estimation?](https://www.vldb.org/pvldb/vol14/p1640-wang.pdf)
- `⚡` 📄 [Neurocard: One cardinality estimator for all tables](https://dl.acm.org/doi/10.14778/3421424.3421432)
- `⚡` 📄 [ALECE: An Attention-based Learned Cardinality Estimator for SPJ Queries on Dynamic Workloads](https://www.vldb.org/pvldb/vol17/p197-li.pdf)

</details>

<details open>
<summary>

##### Cost Estimation

</summary>

- `⚡` 📄 [An End-to-End Learning-based Cost Estimator](https://www.vldb.org/pvldb/vol13/p307-sun.pdf)

</details>

<details open>
<summary>

##### Query Rewrite

</summary>

- `💎` 📄 [A Learned Query Rewrite System using Monte Carlo Tree Search](https://www.vldb.org/pvldb/vol15/p46-li.pdf)

</details>

<details open>
<summary>

##### Plan Optimization

</summary>

- `⚡` 📄 [Neo: A Learned query optimizer](https://dl.acm.org/doi/10.14778/3342263.3342644)
- `⚡` 📄 [Bao: Making Learned Query Optimization Practical](https://dl.acm.org/doi/10.1145/3448016.3452838)

</details>

<details open>
<summary>

### Database Diagnosis

<details open>
<summary>

##### System Causes

</summary>

- `⚡` 📄 [DBPA: A Benchmark for Transactional Database Performance Anomalies.](https://dl.acm.org/doi/abs/10.1145/3588926)
- `⚡` 📄 [DBSherlock: A Performance Diagnostic Tool for Transactional Databases.](https://web.eecs.umich.edu/~mozafari/php/data/uploads/sigmod_2016.pdf)
  
</details>

### Classical database system

<details open>
<summary>

##### Overview of database systems

</summary>

- `⚡` 📄 [Architecture of a database system](https://dsf.berkeley.edu/papers/fntdb07-architecture.pdf)
- `⚡` 📄 [The Design of the POSTGRES Storage System](https://dsf.berkeley.edu/papers/ERL-M87-06.pdf)

</details>

<details open>
<summary>

##### Indexing

</summary>

- `⚡` 📄 [The Ubiquitous B-Tree](https://carlosproal.com/ir/papers/p121-comer.pdf)
- `⚡` 📄 [R-Trees: A Dynamic Index Structure for Spatial Searching](https://dl.acm.org/doi/10.1145/971697.602266)
- `⚡` 📄 [Improved Query Performance with Variant Indexes](https://pages.cs.wisc.edu/~nil/764/DADS/36_improved-query-performance-with.pdf)

</details>

<details open>
<summary>

##### column store

</summary>

- `⚡` 📄 [C-Store: A Column-oriented DBMS](https://web.stanford.edu/class/cs345d-01/rl/cstore.pdf)
- `⚡` 📄 [Column-Stores vs. Row-Stores: How Different Are They Really?](https://www.cs.umd.edu/~abadi/papers/abadi-sigmod08.pdf)

</details>

<details open>
<summary>

##### hierarchical storage

</summary>

- `⚡` 📄 [The 5 minute rule for trading memory for disc accesses and the 10 byte rule for trading memory for CPU time](https://dl.acm.org/doi/10.1145/38714.38755)
- `⚡` 📄 [The Five-Minute Rule Ten Years Later, and Other Computer Storage Rules of Thumb](https://www.cs.cmu.edu/~natassa/courses/15-721/papers/gray.pdf)

</details>

<details open>
<summary>

##### query processing

</summary>

- `⚡` 📄 [Data cube: A relational aggregation operator generalizing group-by, cross-tab, and sub-totals](https://web.stanford.edu/class/cs345d-01/rl/olap.pdf)
- `⚡` 📄 [Volcano An Extensible And Parallel Query Evaluation System](https://cs-people.bu.edu/mathan/reading-groups/papers-classics/volcano.pdf)
- `⚡` 📄 [Encapsulation Of Parallelism In The Volcano Query Processing System](https://cs-people.bu.edu/mathan/reading-groups/papers-classics/encapsulation-volcano.pdf)
- `⚡` 📄 [Query Evaluation Techniques for Large Databases](http://infolab.stanford.edu/~hyunjung/cs346/graefe.pdf)
- `⚡` 📄 [An Overview of Data Warehousing and OLAP Technology](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/sigrecord.pdf)

</details>

<details open>
<summary>

##### query optimization

</summary>

- `⚡` 📄 [Rapid Bushy Join-Order Optimization With Cartesian Products](https://dl.acm.org/doi/10.1145/235968.233317)
- `⚡` 📄 [Access Path Selection in a Relational Database Management System](https://courses.cs.duke.edu/compsci516/cps216/spring03/papers/selinger-etal-1979.pdf)
- `⚡` 📄 [An Overview of Query Optimization in Relational Systems](https://web.stanford.edu/class/cs345d-01/rl/chaudhuri98.pdf)
- `⚡` 📄 [R* Optimizer Validation and Performance Evaluation for Distributed Queries](https://www.seas.upenn.edu/~zives/05s/cis650/papers/r-star.pdf)

</details>

<details open>
<summary>

##### database views

</summary>

- `⚡` 📄 [Maintenance of views](https://dl.acm.org/doi/10.1145/971697.602293)
- `⚡` 📄 [Efficiently Updating Materialized Views](https://dsf.berkeley.edu/cs286/papers/mvupdate-sigmod1986.pdf)

</details>

<details open>
<summary>

##### concurrency control

</summary>

- `⚡` 📄 [On Optimistic Methods for Concurrency Control](https://www.eecs.harvard.edu/~htk/publication/1981-tods-kung-robinson.pdf)
- `⚡` 📄 [Efficient Locking for Concurrent Operations on B-Trees](https://www.csd.uoc.gr/~hy460/pdf/p650-lehman.pdf)
- `⚡` 📄 [Granularity of Locks and Degrees of Consistency in a Shared Data Base](https://www.cs.cmu.edu/~natassa/courses/15-721/papers/GrayLocks.pdf)
- `⚡` 📄 [A Critique of ANSI SQL Isolation Levels](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/tr-95-51.pdf)
- `⚡` 📄 [Paxos Made Simple](https://lamport.azurewebsites.net/pubs/paxos-simple.pdf)

</details>

<details open>
<summary>

##### Logging and recovery

</summary>

- `⚡` 📄 [ARIES: A Transaction Recovery Method Supporting Fine Granularity Locking and Partial Rollbacks Using Write Ahead Logging](https://cs.stanford.edu/people/chrismre/cs345/rl/aries.pdf)

</details>

<details open>
<summary>

##### main memory DBMS

</summary>

- `⚡` 📄 [Main Memory Database Systems: An Overview](https://www.cs.cmu.edu/~natassa/courses/15-721/papers/00180602.pdf)

</details>

<details open>
<summary>

##### non-relational database

</summary>

- `⚡` 📄 [Querying Object-oriented Databases](https://www3.cs.stonybrook.edu/~kifer/TechReports/xsql.pdf)

</details>

### LLM4DB

<details open>
<summary>

##### survey

</summary>

- `⚡` 📄 [How Large Language Models Will Disrupt Data Management](https://dl.acm.org/doi/abs/10.14778/3611479.3611527)

</details>

<details open>
<summary>

##### LLM for Data cleaning

</summary>

- `💎` 📄 [SEED: Domain-Specific Data Curation With Large Language Models]()
- `💎` 📄 [Can Foundation Models Wrangle Your Data?](https://www.vldb.org/pvldb/vol16/p738-narayan.pdf)

</details>

<details open>
<summary>

##### LLM for text2SQL

</summary>

- `💎` 📄 [From BERT to GPT-3 Codex: Harnessing the Potential of Very Large Language Models for Data Management](https://arxiv.org/abs/2306.09339)

</details>

<details open>
<summary>

##### LLM for knob tuning

</summary>

- `💎` 📄 [DB-BERT: a Database Tuning Tool that “Reads the Manual”](https://dl.acm.org/doi/pdf/10.1145/3514221.3517843)

</details>

### Vector database

<details open>
<summary>

##### survey

</summary>

- `⚡` 📄 [Survey of Vector Database Management Systems](https://arxiv.org/pdf/2310.14021)
- `⚡` 📄 [A comprehensive survey on vector database: Storage and retrieval technique, challenge](http://arxiv.org/pdf/2310.11703)

</details>

<details open>
<summary>

##### vector DB system

</summary>

- `💎` 📄 [Milvus: A purpose-built vector data management system](https://www.cs.purdue.edu/homes/csjgwang/pubs/SIGMOD21_Milvus.pdf)

</details>
