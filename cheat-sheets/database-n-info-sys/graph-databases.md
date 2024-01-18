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
	- CouchDB
		* ["open-source document-oriented NoSQL database"](https://en.wikipedia.org/wiki/Apache_CouchDB)
	- IBM Db2
		* graph database.
	- MarkLogic
		* graph database.
	- MongoDB
		* Not graph database.
		* source-available, cross-platform, document-oriented database program
	- OrientDB
		* Supports SQL.
		* graph database.
+ [list of graph databases & supported query languages (prioritize SPARQL)](https://en.wikipedia.org/wiki/NoSQL#Graph):
	- AllegroGraph
		* supports SPARQL
		* RDF triple store
	- Amazon Neptune
		* supports Gremlin
		* supports SPARQL
	- Apache Giraph
		* ["Apache project to perform graph processing on big data"](https://en.wikipedia.org/wiki/Apache_Giraph)
		* [No longer actively developed](https://giraph.apache.org/)
			+ https://attic.apache.org/projects/giraph.html
	- ***ArangoDB***
		* supports GraphQL
		* supports AQL
		* supports JavaScript
		* multi-model DBMS document, graph database and key-value store
	- Azure Cosmos DB
		* supports Gremlin
	- DEX/Sparksee
		* supports C++
		* supports Java
		* supports C#
		* supports Python
	- FlockDB
		* supports Scala
	- IBM Db2
		* supports SPARQL
		* RDF triple store added in DB2 10
	- InfiniteGraph
		* supports Java
	- JanusGraph
		* supports Java
	- MarkLogic
		* supports Java
		* supports JavaScript
		* supports SPARQL
		* supports XQuery
		* multi-model document database and RDF triple store
		* ["enterprise NoSQL database"](https://en.wikipedia.org/wiki/MarkLogic)
	- **s**
		* supports Cypher
		* ["ACID-compliant transactional database with native graph storage and processing"](https://en.wikipedia.org/wiki/Neo4j)
			+ "available in a non-open-source "community edition" licensed with a modification of the GNU General Public License, with online backup and high availability extensions licensed under a closed-source commercial license"
	- OpenLink Virtuoso
		* supports C++
		* supports C#
		* supports Java
		* supports SPARQL
		* middleware and database engine hybrid
	- Oracle
		* SPARQL 1.1
		* RDF triple store added in 11g
	- [OrientDB](https://en.wikipedia.org/wiki/OrientDB)
		* supports Java
		* supports SQL
		* multi-model document and graph database
		* "open source NoSQL database management system"
		* "multi-model database, supporting graph, document, key/value, and object models, but the relationships are managed as in graph databases with direct connections between records"
	- OWLIM
		* supports Java
		* supports SPARQL 1.1
		* RDF triple store
	- Profium Sense
		* Java
		* SPARQL
		* RDF triple store
	- RedisGraph
		* supports Cypher
	- Sqrrl Enterprise
		* supports Java
	- TerminusDB
		* supports JavaScript
		* supports Python
		* supports datalog
		* open source RDF triple-store and document store
	- [Virtuoso, Virtuoso Universal Server, OpenLink Virtuoso](https://en.wikipedia.org/wiki/Virtuoso_Universal_Server)
		* "middleware and database engine hybrid that combines the functionality of a traditional relational database management system (RDBMS), object–relational database (ORDBMS), virtual database, RDF, XML, free-text, web application server and file server functionality in a single system"
+ substitutes for the deprecated *Apache Giraph*
	- https://www.g2.com/products/apache-giraph/competitors/alternatives
		* GraphDB
		* Redis
		* Azure Cosmos DB
		* OrientDB
		* Elastic Stack
		* Amazon Neptune
		* Aerospike
		* Dgraph
	- https://slashdot.org/software/p/Apache-Giraph/alternatives
		* Amazon Neptune
		* Aster SQL-GR
		* AnzoGraph DB
		* TigerGraph
		* DataStax
		* Graph Engine, GE
		* TIBCO Graph Database
		* Neo4j
		* Cayley
		* HyperGraphDB
		* OrigoDB
			- commercial
		* Titan
		* Apache TinkerPop
		* JanusGraph
		* AllegroGraph
		* HugeGraph
		* Oracle Spatial and Graph
		* InfiniteGraph
		* Graph Story
			- commercial
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
			- commercial
		* GraphDB
		* Fluree
		* RecallGraph
		* VelocityDB
			- commercial
		* Apache Cassandra
		* Fauna
		* Blazegraph
		* data.world
			- commercial
		* GUN
		* Apache Spark
		* Apache Mahout













Information from [Wikipedia](https://en.wikipedia.org/wiki/Graph_database):
+ graph models
	- labeled-property graph
		* store properties as key-value pairs
			+ [name-value pair = attribute-value pair = key-value pair = field-value pair](https://en.wikipedia.org/wiki/Name%E2%80%93value_pair)
				- supported by JSON descriptions
	- [resource description framework, RDF](https://en.wikipedia.org/wiki/Resource_Description_Framework)
		* [GraphQL: an open-source data query and manipulation language for APIs. Dgraph implements modified GraphQL language called DQL (formerly GraphQL+-)](https://en.wikipedia.org/wiki/GraphQL)







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
