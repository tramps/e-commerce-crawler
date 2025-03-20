#spider
#crawler
crawler for shopee dd temu tk dy

## 项目结构

```bash
├── crawler
├── crawler-api-shopee
        create task：create task by itemid shopid, later fetch data via query task api
                curl -X 'POST' \
                  'http://101.200.91.78:2048/api/v1/task/create?taskType=item&itemId=10318204034&shopId=32987252&page=1&sort=relevancy&channel=github' \
                  -H 'accept: */*' \
                  -H 'X-API-Token: github' \
                  -d ''
        query task: fetch data by taskid, you can get the raw data in the data field of the response
                curl -X 'GET' \
                  'http://101.200.91.78:2048/api/v1/task/query?channel=github&taskId=543134' \
                  -H 'accept: */*' \
                  -H 'X-API-Token: github'
├── crawler-api-dd
        create task
        query task
├── crawler-api-temu
        create task
        query task
├── crawler-api-dy
        
```
more info contact the admin tg
