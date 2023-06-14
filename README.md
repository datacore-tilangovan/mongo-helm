# mongo-helm
helm charts for mongo 

standalone_enabled=true >> For enabling standalone mongo
cluster_enabled=true >> For enabling clustered mongo(HA)  
statefulset single_replica_sc=mayastor >> For single replica storageclass name
multi_replica_sc=mayastor-3 >> For multi replica storage class name
volume_replication_enabled=true >> for enabling multi replica (by defaut 3)
