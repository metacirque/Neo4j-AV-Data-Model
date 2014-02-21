metaCirque
==========

mcDemo AV database in Neo4j 2.0

metaCirque mcDemo Neo4j database (210 nodes, 503 relationships; hand coded & subject to error), dated 2014-02-17
Cypher code provided under Creative Commons Attribution & ShareAlike 4.0 International License from Laurence Cook & metaCirque, as governed by Neo4j Creative Commons 3.0 License
Promote flow & grow. Thanks for being there. - Laurence Cook, 2014

This database is in Neo4j 2.0. It is the first public iteration, for test purposes. 

The cypher code stored within "metaCirque_mcDemo_20140217.txt" creates instance of clustered nodes representing 13 media instances (below), and a bit of test descriptive metadata.

  mcDemo_01: digital8 Master; and
  mcDemo_01_01: Ingest Master

  mcDemo_02: digital8 Master;
  mcDemo_02_01: Ingest Master; and
  mcDemo_02_01_01: Access Derivative

  mcDemo_03: Edited Master; and
  mcDemo_03_01: Access Derivative

  mcDemo_p: Place Descriptive Metadata (adhoc for test on mcDemo_03 & mcDemo_03_01; non-schema specific);
  mcDemo_e: Subject Descriptive Metadata (adhoc for test on mcDemo_03 & mcDemo_03_01; non-schema specific);
  mcDemo_c: Contributor Descriptive Metadata (adhoc for test on mcDemo_03 & mcDemo_03_01; non-schema specific); and
  mcDemo_d: Dialogue escriptive Metadata (adhoc for test on mcDemo_03 & mcDemo_03_01; non-schema specific)

  mcDemo_04: Edited Master; and
  mcDemo_04_01: Access Derivative

  mcDemo_05: Music CD (Physical); and
  mcDemo_05_01: Music CD (Ingest Master)

  mcDemo_06: Asymmetrical Edit Master; and
  mcDemo_06_01: Asymmetrical Access Copy

The node clusters created are atypical for a Neo4j database. They are designed to provide label-based arrays of 5+ nodes (typically, 6 nodes for a video object) under a single UMID, with each node having a distinct NID (node identifier) to indicate its relative position within the array structure. 

For more details, read the 16 page pdf presentation to be found at:

http://www.metacirque.com/metaCirque_avDataModel_Presentation20140218.pdf

Blog tutorial and update explanations to be found at http://www.metacirque.com/blog/

Contact: Laurence Cook, connect@metacirque.com

Twitter: @metacirque

Upload the code into a Neo4j 2.0 db, and play with it. See what errors you can find (there are some), and help improve it.



