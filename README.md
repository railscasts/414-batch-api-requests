# RailsCasts Episode #414: Batch API Requests

http://railscasts.com/episodes/414-batch-api-requests

Requires Ruby 1.9.2 or higher.


### Commands used in this episode

```
rake middleware
curl -d 'requests=[{"method":"GET","url":"/tasks/1.json"},{"method":"GET","url":"/tasks/2.json"}]' localhost:3000/batch
```
