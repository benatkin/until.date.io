# until.date.io

This is an [express](http://expressjs.com/) web application that shows
the number of days until a given date. The date is provided as the URL
path. For example, to see the number of days until New Years Eve, go
to
[https://until.date.io/2012/12/31/](https://until.date.io/2012/12/31/). If
a date given is before this resource was deployed, a 404 will be
returned. If a date given is between when this resource was deployed
and the current date, a 410 will be returned.

# status

Running on Heroku at [until.date.io](http://until.date.io/) and
[until-date.herokuapp.com](http://until-date.herokuapp.com/).

# license

[MIT](http://benatkin.mit-license.org/).
