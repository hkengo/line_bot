# Heroku
```
#login
heroku login
# deploy
git push heroku master
# get deploy url
heroku info
# confirm environment
heroku config
# set environment (can set environment by gui)
heroku config:set LINE_CHANNEL_SECRET=xxxx
heroku config:set LINE_CHANNEL_TOKEN=xxxx
# push to heroku by except of master
git push [app_name] [branch_name]:master
# Sea lial time logs.
heroku logs --tail
```
