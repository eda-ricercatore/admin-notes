#	Graph Databases


#	Information about NoSQL: For Graph Databases


Information about [NoSQL](https://en.wikipedia.org/wiki/NoSQL):
+ [The following NoSQL databases provide support for ACID properties (Atomicity, Consistency, Isolation, Durability) or "joins"](https://en.wikipedia.org/wiki/NoSQL#ACID_and_join_support):
	- Apache Ignite
		* Not graph database.
		* distributed database management system
		* ["It natively supports classical training algorithms such as Linear Regression, Decision Trees, Random Forest, Gradient Boosting, SVM, K-Means and others. In addition to that, Apache Ignite has a deep integration with TensorFlow."](https://en.wikipedia.org/wiki/Apache_Ignite)
	- ArangoDB
		* graph database.
		* supports GraphQL
	- [Couchbase, Couchbase Server, originally known as Membase](https://en.wikipedia.org/wiki/Couchbase_Server)
		* "source-available,[2] distributed (shared-nothing architecture) multi-model NoSQL document-oriented database software package optimized for interactive applications"
		* https://www.couchbase.com/pricing/
	- CouchDB
		* ["open-source document-oriented NoSQL database"](https://en.wikipedia.org/wiki/Apache_CouchDB)
		* [Apache CouchDB](https://couchdb.apache.org/)
			+ Needs to set a password for [CouchDB admin](https://couchdb.apache.org/).
			+ Did not provide opportunity to set up username for the account, and authentication for CouchDB admin failed as a result.
		* https://courses.cs.washington.edu/courses/cse344/16wi/hw/hw5/hw5.html
			+ https://courses.cs.washington.edu/courses/cse344/16wi/
			+ Database Systems: The Complete Book, Hector Garcia-Molina, Jeffrey Ullman, Jennifer Widom
	- IBM Db2
		* graph database.
	- MarkLogic
		* graph database.
		* https://www.marklogic.com/
	- MongoDB
		* Not graph database.
		* source-available, cross-platform, document-oriented database program
		* https://www.mongodb.com/pricing
	- OrientDB
		* Supports SQL.
		* graph database.
+ [list of graph databases & supported query languages (prioritize SPARQL)](https://en.wikipedia.org/wiki/NoSQL#Graph):
	- [ ] AllegroGraph
		* supports SPARQL
		* RDF triple store
		* https://en.wikipedia.org/wiki/AllegroGraph
		* https://allegrograph.com/
	- [ ] Amazon Neptune
		* supports Gremlin
		* supports SPARQL
		* https://aws.amazon.com/neptune/
	- [ ] Apache Giraph
		* ["Apache project to perform graph processing on big data"](https://en.wikipedia.org/wiki/Apache_Giraph)
		* [No longer actively developed](https://giraph.apache.org/)
			+ https://attic.apache.org/projects/giraph.html
	- [x] ***ArangoDB***
		* supports GraphQL
		* supports AQL
		* supports JavaScript
		* multi-model DBMS document, graph database and key-value store
		* https://en.wikipedia.org/wiki/ArangoDB
		* Cytoscape with ArangoDB
			+ https://cytoscape.org/
			+ https://github.com/cytoscape/cytoscape-tutorials
		* https://arangodb.com/2013/12/visualize-graphs/
		* [open-source](https://en.wikipedia.org/wiki/Graph_database)
			+ "NoSQL native graph database system developed by ArangoDB Inc, supporting three data models (key/value, documents, graphs), with one database core and a unified query language called AQL (ArangoDB Query Language). Provides scalability and high availability via datacenter-to-datacenter replication, auto-sharding, automatic failover, and other capabilities."
		* https://arangodb.com/
			+ pricing for cloud services
				- https://dashboard.arangodb.cloud/home
			+ downloads:
				- https://arangodb.com/download-major/
				- supports
					* Docker
					* Kubernetes
					* Debian
					* Ubuntu
					* macOS (for Intel/Arm processors)
						+ The recommended way of using ArangoDB on macOS is to use the ArangoDB Docker images with, for instance, Docker Desktop.
						+ Running production environments on macOS is not supported.
	- [ ] Azure Cosmos DB
		* supports Gremlin
		* ["globally distributed, multi-model database service"](https://en.wikipedia.org/wiki/Cosmos_DB)
		* https://azure.microsoft.com/en-us/products/cosmos-db
		* https://learn.microsoft.com/en-us/azure/cosmos-db/introduction
		* https://cosmos.azure.com/
	- [ ] DEX/Sparksee
		* supports C++
		* supports Java
		* supports C#
		* supports Python
		* https://en.wikipedia.org/wiki/Sparksee_(graph_database)
		* https://www.sparsity-technologies.com/pricing/
	- [ ] FlockDB
		* supports Scala
		* https://github.com/twitter-archive/flockdb
			+ deprecated/archived
	- [ ] IBM Db2
		* supports SPARQL
		* RDF triple store added in DB2 10
	- [ ] InfiniteGraph
		* supports Java
		* distributed graph database
		* commercial product
		* ***Poorly supported product***
	- [ ] JanusGraph
		* supports Java
		* [open-source](https://en.wikipedia.org/wiki/Graph_database)
			+ "Open source, scalable, distributed across a multi-machine cluster graph database under The Linux Foundation; supports various storage backends (Apache Cassandra, Apache HBase, Google Cloud Bigtable, Oracle Berkeley DB);[29] supports global graph data analytics, reporting, and extract, transform, load (ETL) through integration with big data platforms (Apache Spark, Apache Giraph, Apache Hadoop); supports geo, numeric range, and full-text search via external index storages (Elasticsearch, Apache Solr, Apache Lucene)."
		* https://janusgraph.org/
			+ data storage supported for:
				- Apache Cassandra
				- Apache HBase
				- Google Cloud Bigtable
				- Oracle BerkeleyDB
				- ScyllaDB
			+ https://github.com/JanusGraph/janusgraph
	- [ ] MarkLogic
		* supports Java
		* supports JavaScript
		* supports SPARQL
		* supports XQuery
		* multi-model document database and RDF triple store
		* ["enterprise NoSQL database"](https://en.wikipedia.org/wiki/MarkLogic)
		* https://www.marklogic.com/
	- [ ] NebulaGraph
		* [open-source](https://en.wikipedia.org/wiki/Graph_database)
			+ "A scalable open-source distributed graph database for storing and handling billions of vertices and trillions of edges with milliseconds of latency. It is designed based on a shared-nothing distributed architecture for linear scalability."
		* ["open-source distributed graph database built for super large-scale graphs with milliseconds of latency"](https://en.wikipedia.org/wiki/NebulaGraph)
		* https://hub.docker.com/extensions/weygu/nebulagraph-dd-ext
			+ Docker installation.
			+ https://www.nebula-graph.io/
	- [ ] **Neo4j**
		* supports Cypher
		* ["ACID-compliant transactional database with native graph storage and processing"](https://en.wikipedia.org/wiki/Neo4j)
			+ "available in a non-open-source "community edition" licensed with a modification of the GNU General Public License, with online backup and high availability extensions licensed under a closed-source commercial license"
		* https://neo4j.com/pricing/
			+ GraphQL is not supported for free.
		* ***Search for Neo4j GraphQL solutions***
		* [open-source](https://en.wikipedia.org/wiki/Graph_database)
			+ "Open-source, supports ACID, has high-availability clustering for enterprise deployments, and comes with a web-based administration that includes full transaction support and visual node-link graph explorer; accessible from most programming languages using its built-in REST web API interface, and a proprietary Bolt protocol with official drivers."
	- [ ] OpenLink Virtuoso
		* supports C++
		* supports C#
		* supports Java
		* supports SPARQL
		* middleware and database engine hybrid
		* [open-source](https://en.wikipedia.org/wiki/Graph_database)
			+ "Multi-model (Hybrid) relational database management system (RDBMS) that supports both SQL and SPARQL for declarative (Data Definition and Data Manipulation) operations on data modelled as SQL tables and/or RDF Graphs. Also supports indexing of RDF-Turtle, RDF-N-Triples, RDF-XML, JSON-LD, and mapping and generation of relations (SQL tables or RDF graphs) from numerous document types including CSV, XML, and JSON. May be deployed as a local or embedded instance (as used in the NEPOMUK Semantic Desktop), a one-instance network server, or a shared-nothing elastic-cluster multiple-instance networked server"
		* https://virtuoso.openlinksw.com/
		* https://shop.openlinksw.com/license_generator/virtuoso-download/
	- [ ] Oracle
		* SPARQL 1.1
		* RDF triple store added in 11g
	- [ ] [OrientDB](https://en.wikipedia.org/wiki/OrientDB)
		* supports Java
		* supports SQL
		* multi-model document and graph database
		* "open source NoSQL database management system"
		* "multi-model database, supporting graph, document, key/value, and object models, but the relationships are managed as in graph databases with direct connections between records"
		* [open-source](https://en.wikipedia.org/wiki/Graph_database)
			+ "Second-generation[clarification needed] distributed graph database with the flexibility of documents in one product (i.e., it is both a graph database and a document NoSQL database); licensed under open-source Apache 2 license; and has full ACID support; it has a multi-master replication and sharding; supports schema-less, -full, and -mixed modes; has security profiling based on user and roles; supports a query language similar to SQL. It has HTTP REST and JSON API."
	- [ ] OWLIM
		* supports Java
		* supports SPARQL 1.1
		* RDF triple store
	- [ ] Profium Sense
		* Java
		* SPARQL
		* RDF triple store
	- [ ] RedisGraph
		* supports Cypher
	- [ ] Sqrrl Enterprise
		* supports Java
	- [ ] TerminusDB
		* supports JavaScript
		* supports Python
		* supports datalog
		* open source RDF triple-store and document store
		* [open-source](https://en.wikipedia.org/wiki/Graph_database)
			+ "Document-oriented knowledge graph; the power of an enterprise knowledge graph with the simplicity of documents."
	- [ ] TypeDB
		* [open-source](https://en.wikipedia.org/wiki/Graph_database)
			+ "TypeDB is a strongly-typed database with a rich and logical type system. TypeDB empowers you to tackle complex problems, and TypeQL is its query language. TypeDB allows you to model your domain based on logical and object-oriented principles. Composed of entity, relationship, and attribute types, as well as type hierarchies, roles, and rules, TypeDB allows you to think higher-level, as opposed to join-tables, columns, documents, vertices, edges, and properties."
			+ https://typedb.com/
	- [ ] [Virtuoso, Virtuoso Universal Server, OpenLink Virtuoso](https://en.wikipedia.org/wiki/Virtuoso_Universal_Server)
		* "middleware and database engine hybrid that combines the functionality of a traditional relational database management system (RDBMS), object–relational database (ORDBMS), virtual database, RDF, XML, free-text, web application server and file server functionality in a single system"
		* https://shop.openlinksw.com/license_generator/virtuoso-download/
+ substitutes for the deprecated *Apache Giraph*
	- https://www.g2.com/products/apache-giraph/competitors/alternatives
		* GraphDB
		* Redis
		* Azure Cosmos DB
		* OrientDB
		* Elastic Stack
		* Amazon Neptune
		* ***Aerospike***
		* ***Dgraph***
	- https://slashdot.org/software/p/Apache-Giraph/alternatives
		* Amazon Neptune
		* Aster SQL-GR
		* AnzoGraph DB
		* TigerGraph
		* DataStax
		* ***Graph Engine, GE***
			+ https://www.predictiveanalyticstoday.com/top-free-graph-databases/
			+ https://www.graphengine.io/
				- https://www.nuget.org/packages/GraphEngine.Core/
				- https://github.com/Microsoft/GraphEngine
		* TIBCO Graph Database
		* Neo4j
		* ***Cayley***
			+ https://www.predictiveanalyticstoday.com/top-free-graph-databases/
			+ https://cayley.io/
				- https://cayley.gitbook.io/cayley/
				- https://cayley.gitbook.io/cayley/getting-started
		* ***HyperGraphDB***
			+ http://www.hypergraphdb.org/
				- http://www.hypergraphdb.org/?project=hypergraphdb&page=Downloads
		* OrigoDB
			+ commercial
		* ***Titan***
			+ https://www.predictiveanalyticstoday.com/top-free-graph-databases/
		* Apache TinkerPop
		* JanusGraph
		* AllegroGraph
		* HugeGraph
		* Oracle Spatial and Graph
		* InfiniteGraph
		* Graph Story
			+ commercial
		* FlockDB
		* Memgraph
		* RelationalAI
		* Virtuoso
		* Grakn
		* IBM Cloud Databases
		* ArcadeDB
		* Nebula Graph
		* GraphBase
		* KgBase
		* OrientDB
		* Dgraph
		* ArangoDB
		* Sparksee
		* Locstat
		* Stardog
		* Luna for Apache Cassandra
		* Redis
		* TerminusDB
		* Graphlytic
			+ commercial
		* GraphDB
		* Fluree
		* RecallGraph
		* VelocityDB
			+ commercial
		* Apache Cassandra
		* Fauna
		* Blazegraph
		* data.world
			+ commercial
		* GUN
		* Apache Spark
		* Apache Mahout
+ additional options
	- [ ] GraphDB Lite
		* https://www.predictiveanalyticstoday.com/top-free-graph-databases/
	- [ ] MapGraph API
		* https://www.predictiveanalyticstoday.com/top-free-graph-databases/
	- [ ] BrightstarDB
		* https://www.predictiveanalyticstoday.com/top-free-graph-databases/
	- [ ] WhiteDB
		* https://www.predictiveanalyticstoday.com/top-free-graph-databases/
	- [ ] Orly
		* https://www.predictiveanalyticstoday.com/top-free-graph-databases/
	- [ ] Weaver
		* https://www.predictiveanalyticstoday.com/top-free-graph-databases/
	- [ ] sones GraphDB
		* https://www.predictiveanalyticstoday.com/top-free-graph-databases/
	- [ ] Filament
		* https://www.predictiveanalyticstoday.com/top-free-graph-databases/
	- [ ] DataStax Astra DB
	- [ ] Elastic
	- [ ] Pinecone
	- [G.V()](https://gdotv.com/)
	- [Tom Sawyer Graph Database Browser](https://www.tomsawyer.com/graph-database-browser)
+ From ***Databases of Databases***:
	- https://dbdb.io/browse?os=os-x&type=academic&type=educational&type=hobby&type=industrial-research&type=open-source&data-model=graph&data-model=network&q=
	- support for characteristics
		* Abandoned Project
		* Acquired Company
		* Blockchain
		* Cache
		* Failed Company
		* Immutable
		* Middleware
		* Mobile
		* Nearest Neighbor Search
		* NewSQL
		* NoSQL
		* OLAP
		* OLTP
		* Peer-to-Peer
		* Search Engine
		* Serverless
		* Streaming
		* Time-Series
		* Versioning
		* Web Browser
	- support for Project Types
		* Academic
		* Commercial
		* Educational
		* Hobby
		* Industrial Research
		* Internal / Non-Public
		* Open Source
	- support for Licenses
		* AGPL v3
		* Apache v2
		* Boost Software License
		* BSD
		* Business Source License
		* Code Project Open License
		* Commons Clause License
		* Creative Commons License
		* Eclipse Public License
		* Elastic License v2
		* Fair Source License
		* GPL v2
		* GPL v3
		* ISC License
		* LGPL v2
		* LGPL v3
		* Microsoft Reference Source License
		* MIT
		* Mozilla Public License
		* Mulan PubL v2
		* OpenLDAP Public License
		* Open Software License 3.0
		* Parity Public License
		* PostgreSQL License
		* Proprietary
		* Public Domain
		* Python License
		* Server Side Public License
		* VoltDB Proprietary License
		* Zope Public Licenses
	- support for checkpoints:
		* blocking
		* consistent
		* fuzzy
		* non-blocking
		* not supported
	- support for compression:
		* bitmap encoding
		* bit packing / mostly encoding
		* delta encoding
		* dictionary encoding
		* incremental encoding
		* naive (page-level)
		* naive (record-level)
		* null suppression
		* prefix compression
		* run-lenth encoding
	- support for concurrency control:
		* deterministic concurrency control
		* multi-version concurrency control (MVCC)
		* not supported
		* optimistic concurrency control (OCC)
		* timestamp ordering
		* two-phase locking (deadlock detection)
		* two-phase locking (deadlock prevention)
	- support for data model
		* array / matrix
		* column family / wide-column
		* document / XML
		* entity-attribute-value
		* entity-relationship
		* graph
		* hierarchical
		* key/value
		* multi-value
		* network
		* object-oriented
		* object-relational
		* relational
		* triplestore / RDF
		* vector
	- support for Fault Tolerance
		* Asynchronous Replication
		* Conflict Resolution
		* Quorum-based Replication
		* Read Repair
		* Synchronous Replication
	- support for foreign keys
	- support for Hardware Acceleration
		* Custom
		* FPGA
		* GPU
		* RDMA
	- support for Indexes
		* Adaptive Radix Tree (ART)
		* AVL-Tree
		* B-epsilon Tree
		* BitMap
		* Block Range Index (BRIN)
		* B+Tree
		* Bw-Tree
		* Hash Table
		* Hierarchical Navigable Small World (HNSW)
		* Inverted Index (Full Text)
		* K-D Tree
		* Log-Structured Merge Tree
		* MassTree
		* Not Supported
		* Patricia/Radix Trie
		* Red-Black Tree
		* R-Tree
		* Skip List
		* T-Tree
	- support for Isolation Levels
		* Cursor Stability
		* Not Supported
		* Read Committed
		* Read Stability
		* Read Uncommitted
		* Repeatable Read
		* Serializable
		* Snapshot Isolation
	- support for Joins
		* Broadcast Join
		* Hash Join
		* Index Nested Loop Join
		* Nested Loop Join
		* Not Supported
		* Semi Join
		* Shuffle Join
		* Sort-Merge Join
		* Worst-Case Optimal Join
	- support for Logging
		* Command Logging
		* Logical Logging
		* Not Supported
		* Physical Logging
		* Physiological Logging
		* Shadow Paging
	- support for Parallel Execution
		* Bushy
		* Inter-Operator (Vertical)
		* Intra-Operator (Horizontal)
	- support for Query Compilation
		* Code Generation
		* JIT Compilation
		* Not Supported
		* Stored Procedure Compilation
	- support for Query Execution
		* Materialized Model
		* Tuple-at-a-Time Model
		* Vectorized Model
	- support for Query Interface
		* Command-line / Shell
		* Custom API
		* Cypher
		* Datalog
		* GraphQL
		* Gremlin
		* HTTP / REST
		* PartiQL
		* PL/SQL
		* PromQL
		* QUEL
		* RDFS++
		* RPC
		* SPARQL
		* SQL
		* Stored Procedures
		* XPath
		* XQuery
	- support for Storage Architecture
		* Disk-oriented
		* Hybrid
		* In-Memory
	- support for Storage Format
		* Apache Arrow
		* Apache Avro
		* Apache CarbonData
		* Apache Hudi
		* Apache Iceberg
		* Apache ORC
		* Apache Parquet
		* CSV
		* Custom
		* DataFrame
		* HDF5
		* N-Triples
		* RCFile
		* SequenceFile
		* Trevni
	- support for Storage Model
		* Custom
		* Decomposition Storage Model (Columnar)
		* Hybrid
		* N-ary Storage Model (Row/Record)
	- support for Storage Organization
		* Copy-on-Write / Shadow Paging
		* Heaps
		* Indexed Sequential Access Method (ISAM)
		* Log-structured
		* Sorted Files
	- support for stored procedures
	- support for System Architecture
		* Embedded
		* Shared-Disk
		* Shared-Everything
		* Shared-Memory
		* Shared-Nothing
	- support for User-Defined Functions
		* Custom Language
		* Java
		* Javascript
		* Perl
		* PHP
		* PL/SQL
		* Python
		* R
		* Ruby
		* Rust
		* TCL
		* T-SQL
	- support for Views
		* Materialized Views
		* Not Supported
		* Virtual Views
	- results are:
		* https://dbdb.io/db/agensgraph
			+ AgensGraph
			+ https://bitnine.net/agensgraph-downloads/
			+ https://bitnine.net/agensgraph/?ckattempt=1
			+ https://github.com/bitnine-oss/agensgraph
			+ "./configure --prefix=$(pwd)" fails to generate Makefiles.
			+ '/opt/local/lib/libintl.8.dylib' (mach-o file, but is an incompatible architecture (have 'arm64', need 'x86_64'))
			+ additional resources:
				- https://bitnine.net/documentations/manual/operation/english/agens_graph_operation_manual_html.html?ckattempt=1
				- https://bitnine.net/documentations/manual/developer/english/agens_graph_developer_manual_html.html
				- https://bitnine.net/documentation/
					* https://bitnine.net/documentations/manual/quick_guide/agens_graph_quick_guide_html.html
				- https://github.com/bitnine-oss/agensgraph
				- https://github.com/bitnine-oss
				- https://github.com/bitnine-oss/agensgraph
		* https://dbdb.io/db/arangodb
			+ ArangoDB
		* https://dbdb.io/db/blazegraph
			+ Blazegraph
			+ https://github.com/blazegraph/database
			+ https://blazegraph.com/
			+ https://github.com/blazegraph/database/releases/tag/BLAZEGRAPH_2_1_6_RC
		* https://dbdb.io/db/dgraph
			+ Dgraph
			+ https://dgraph.io/
		* https://dbdb.io/db/hypergraphdb
			+ HyperGraphDB
			+ https://github.com/hypergraphdb/hypergraphdb
			+ http://www.hypergraphdb.org/?project=hypergraphdb&page=Downloads
		* https://dbdb.io/db/polypheny
			+ Polypheny
			+ https://docs.polypheny.com/en/latest/getting_started/setup/install#binaries
			+ https://github.com/polypheny/Polypheny-DB/releases/tag/v0.9.1
			+ https://github.com/polypheny/Polypheny-DB
			+ After clicking on the executable binary, it launches on a tab in a Web browser.
				- http://localhost:8080/#/views/monitoring
				- can create app at:
					* http://localhost:8080/#/views/schema-editing/
				- manage data at:
					* http://localhost:8080/#/views/data-table/
					* http://localhost:8080/#/views/data-table/bigotnetwork
			+ ***Annoying to edit/manage.***
		* https://dbdb.io/db/sparksee
			+ https://www.sparsity-technologies.com/#sparksee
			+ https://www.sparsity-technologies.com/form-academia/
			+ https://www.sparsity-technologies.com/UserManual/
			+ https://www.sparsity-technologies.com/wp-content/uploads/2021/05/UserManual.pdf
			+ Python, or C++
			+ macOS, Linux
		* https://dbdb.io/db/surrealdb
			+ SurrealDB is a multi-model DBMS that supports embedded and shared-nothing deployments. It uses a hybrid data model that combines documents with explicit graph edge relationships.
		* https://dbdb.io/db/typedb
			+ TypeDB is a strongly-typed database with a rich and logical type system. TypeDB empowers you to tackle complex problems, and TypeQL is its query language.
			+ https://github.com/vaticle/typedb
				- Vaticle: TypeDB
				- TypeDB: the polymorphic database powered by types
			+ https://typedb.com/lectures/typedb-polymorphic-database
				- polymorphic database
				- "There are three fundamental forms of polymorphism in computer science: inheritance polymorphism, interface polymorphism, and parametric polymorphism. In order to be fully polymorphic, a database must implement all three kinds. It must be able to interpret queries about a given type, that operate on instances of that type and all its subtypes. It must be able to interpret queries about a given interface type, that operate on instances of all types that implement it. And it must be able to interpret queries about parametrized types, that operate on instances of all types supplied as parameters."
				- Vaticle Ltd.: London, U.K..
			+ https://github.com/topics/polymorphic?o=desc&s=updated
	- https://dbdb.io/db/kyoto-cabinet
		* Kyoto Cabinet









+ additional database management systems, and frameworks for developing database management systems
	- Apache Calcite
		* "Apache Calcite is an open source framework for building databases and data management systems. It includes a SQL parser, an API for building expressions in relational algebra, and a query planning engine. As a framework, Calcite does not store its own data or metadata, but instead allows external data and metadata to be accessed by means of plug-ins."















Information from [Wikipedia](https://en.wikipedia.org/wiki/Graph_database):
+ graph models
	- labeled-property graph
		* store properties as key-value pairs
			+ [name-value pair = attribute-value pair = key-value pair = field-value pair](https://en.wikipedia.org/wiki/Name%E2%80%93value_pair)
				- supported by JSON descriptions
	- [resource description framework, RDF](https://en.wikipedia.org/wiki/Resource_Description_Framework)
		* [GraphQL: an open-source data query and manipulation language for APIs. Dgraph implements modified GraphQL language called DQL (formerly GraphQL+-)](https://en.wikipedia.org/wiki/GraphQL)
			+ https://github.com/dgraph-io/dgraph
			+ https://dgraph.io/



Favor solutions that support:
+ [GraphQL](https://en.wikipedia.org/wiki/GraphQL)
	- https://graphql.org/
	- https://github.com/graphql/graphql-spec



Graph database visualization:
+ https://neo4j.com/developer-blog/15-tools-for-visualizing-your-neo4j-graph-database/
	- [ ] Charts (reporting tool)
		* ***Check this out!!!***
	- [ ] Cytoscape with ArangoDB (development tool)
		* https://cytoscape.org/
		* https://github.com/cytoscape/cytoscape-tutorials
	- [ ] Data visualization tools for Neo4j graph databases.
		* Neo4j Browser (development tool)
		* Neo4j Bloom (exploration and analysis tool)
	- [Graphexp](https://github.com/bricaud/graphexp)
		* Gremlin server, or Apache TinkerPop™
			+ https://tinkerpop.apache.org/
			+ Gremlify:
				- https://tinkerpop.apache.org/
				- https://github.com/gremlify/gremlify
				- https://gremlify.com/
	- [ ] Graphileon (reporting tool)
		* dashboard development environment
	- [ ] Graphistry (analysis tool)
	- [ ] Graphlytic, graphlytic.biz
	- [ ] GraphXR
	- [ ] Hume
		* GraphAware Hume (exploration and analysis tool)
	- [Invana Studio](https://github.com/invana/invana-studio?tab=readme-ov-file)
	- [ ] Keylines (development tool)
		* From Cambridge Intelligence
	- [ ] Kineviz
		* Kineviz GraphXR (analysis tool)
	- [ ] Linkurious (exploration and analysis tool)
	- [ ] NeoDash (reporting tool)
		* ***Check this out!!!***
	- [ ] neovis.js (development tool)
		* https://github.com/neo4j-contrib/neovis.js/
			+ depends on Neo4j
		* https://visjs.org/
			+ wrapper for Vis.js
	- [ ] Perspectives
		* Tom Sawyer's Perspectives (exploration and analysis tool)
	- [PuppyQuery](https://puppygraph.com/)
		* https://docs.puppygraph.com/user-manual/docker-deployment
	- [ ] popoto.js (development tool)
		* ***Check this out!!!***
	- [ ] SamSpect
	- [ ] yWorks Neo4j Explorer (exploration and analysis tool)
	- "Embeddable libraries without direct Neo4j connection"
		* Cytoscape.js
		* D3.js
		* Sigma.js
		* Vivagraph.js









#	Additional Information

+ [multi-model database](https://en.wikipedia.org/wiki/Multi-model_database)
	- "In the field of database design, a multi-model database is a database management system designed to support multiple data models against a single, integrated backend."
	- "Document, graph, relational, and key–value models are examples of data models that may be supported by a multi-model database."
+ [triplestore](https://en.wikipedia.org/wiki/Triplestore)
	- "A triplestore or RDF store is a purpose-built database for the storage and retrieval of triples[1] through semantic queries. A triple is a data entity composed of subject–predicate–object, like "Bob is 35" (i.e., Bob's age measured in years is 35) or "Bob knows Fred"."






#	Author Information

The MIT License (MIT)

Copyright (c) <2016> Zhiyang Ong

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Email address: echo "cukj -wb- 23wU4X5M589 TROJANS cqkH wiuz2y 0f Mw Stanford" | awk '{ sub("23wU4X5M589","F.d_c_b. ") sub("Stanford","d0mA1n"); print $5, $2, $8; print " "; for (i=1; i<=1; i++) print "6\b"; print $9, $7, $6 }' | sed y/kqcbuHwM62z/gnotrzadqmC/ | tr 'q' ' ' | tr -d "\n" | tr -d 'ir' | tr y "\n"

Don't compromise my computing accounts. You have been warned.
