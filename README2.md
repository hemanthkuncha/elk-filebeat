modified storage class "hostpath"
ad in pvc clain also


added pv.yml 

sudo mkdir -p /mnt/data/elasticsearch
sudo chown -R 1000:1000 /mnt/data/elasticsearch

apply pv.yaml first 

then deploy them one by one 

access kibana with nodeport

> stack management > Index Patterns - create index pattern as [ filebeat-* ]

