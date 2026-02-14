**Project Description**

This assignment explores the practical use of distributed computing tools for processing large-scale datasets. The work involves installing and configuring Apache Hadoop on a local machine, executing MapReduce programs, managing data using HDFS, and performing advanced analytics with Apache Spark.

The tasks demonstrate how big data frameworks enable scalable storage, parallel computation, and efficient handling of large text collections.

🎯**Goals of the Assignment**

  🔹Set up a functioning Hadoop environment
  
  🔹Perform distributed data processing using MapReduce
  
  🔹Understand file storage and replication in HDFS
  
  🔹Evaluate performance parameters affecting job execution
  
  🔹Use PySpark for large-scale text analysis
  
  🔹Extract structured information from unstructured data
  
  🔹Compute document similarity using TF-IDF

  🔹Model relationships between authors based on publication data

💻**Environment Details**

  🔹Operating System: Ubuntu 22.04 LTS
  
  🔹Hadoop: Version 3.3.x
  
  🔹Apache Spark: Version 3.x
  
  🔹Python: Version 3.x
  
  🔹Java: OpenJDK

**Deployment Mode**: Single-node pseudo-distributed setup

⚙️ Hadoop Implementation (Q1–Q9)

🔹 MapReduce WordCount

The WordCount example program was executed to demonstrate distributed processing. The job divides input data into splits, processes them in parallel using mapper tasks, and aggregates results using reducers.

🔹 HDFS Operations

Key file system operations performed include:

  🔹Uploading files to HDFS
  
  🔹Listing directory contents
  
  🔹Understanding block storage
  
  🔹Observing replication behavior
  
  🔹Performance Evaluation

Execution time was measured to study how configuration parameters (such as input split size) influence performance.

⚡ Spark-Based Analysis (Q10–Q12)

🔹 Metadata Extraction

Metadata such as title, release date, language, and encoding was extracted from book headers using pattern matching techniques.

🔹 Document Similarity Analysis

A similarity model was implemented using TF-IDF and cosine similarity. The workflow included:

  🔹Cleaning and preprocessing text
  
  🔹Tokenization
  
  🔹Removing stop words
  
  🔹Generating TF-IDF vectors
  
  🔹Measuring similarity between documents
  
  🔹Author Relationship Network

An approximate influence network was constructed by connecting authors whose works fall within a defined time window. This provides insights into potential literary relationships.

🧠 **Concepts Applied**

  🔹Distributed file storage (HDFS)
  
  🔹Parallel computation with MapReduce
  
  🔹Resource management
  
  🔹Text mining techniques
  
  🔹Regular expressions
  
  🔹Vector space representation
  
  🔹Similarity measurement
  
  🔹Graph modeling using Spark

📊 **Key Observations**

🔹Hadoop efficiently handles large datasets using distributed processing.

🔹System performance depends on configuration and input characteristics.

🔹Spark enables faster analysis due to in-memory computation.

🔹TF-IDF highlights distinctive words while reducing common terms.

🔹Network modeling provides useful structural insights but remains approximate.

⚠️**Constraints and Assumptions**

🔹Influence relationships are inferred, not explicitly verified.

🔹Metadata quality varies across documents.

🔹Cross-join operations may become expensive for very large datasets.
