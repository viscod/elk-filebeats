### Run

```bash
cd elk-filebeats
sudo chown root filebeat.yml
sudo chmod go-w filebeat.yml
docker compose up -d 

 ```

 ### Access Kibana
```
 http://localhost:5601
 user: elastic
 password: password
```

 go to Observability  then Logs then streams