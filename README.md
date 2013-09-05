elasticsearch-0.90.2-with-mongo
===============================

base elastic search set up with mongodb river installed

This package requires mongodb be installed with replica set enabled. See: http://docs.mongodb.org/manual/tutorial/convert-standalone-to-replica-set/

Make sure and set data path to default: /data/db/

To ensure compatibility, versions of these packages should be installed:
mongo 2.4.5
elastic search 0.90.2
elasticsearch mapper attachments 1.7.0 (bin/plugin -install elasticsearch/elasticsearch-mapper-attachments/1.7.0)
elasticsearch river mongodb 1.6.11 (bin/plugin -install richardwilly98/elasticsearch-river-mongodb/1.6.11)
