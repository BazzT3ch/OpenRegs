# Neo4j dump

The simplest way to setup the knowledge graph is to restore it from the `kg2_release.dump` with [Neo4j](https://neo4j.com/)
Just add the dump file in the Files section and select the `Create new DBMS from dump` option.

Please note that some people have experienced issues with loading the dump file into Neo4j, let me know if you also experience issues and I can send a link to another version of the file thanks (BazzT3ch).

# Raw cypher queries

`Raw` folder contains pickled cypher queries which were used to construct the graph. 
The ```src/upload_pkl_to_neo4j.py``` contains example on how to use them directly. 
