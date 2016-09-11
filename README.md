# Go gin app

This is the code from the article [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin).


deployment [golang app into heroku](https://habrahabr.ru/post/229799/):

- commit all changes into you repo locally
- double check that "Procfile" and [godep](https://devcenter.heroku.com/articles/go-dependencies-via-godep) exist if not - add it and commit all changes.
- execute: <br />
`$heroku create -b https://github.com/kr/heroku-buildpack-go.git`
and<br />
`$git push heroku master`
and<br />
`$heroku open`
- for debbuid process of deployment/starting app at heroku need to run:<br />
`$heroku log`
