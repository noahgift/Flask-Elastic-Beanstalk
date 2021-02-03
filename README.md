# Flask-Elastic-Beanstalk


1.  Install `eb` tool:  https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3-install.html

*Will take a few minutes*

2.  Deploy via cloud9.

*You can refer to tutorial [here as well for Flask EB](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/create-deploy-python-flask.html)*

A.  check out this repo and cd into it
`make all`

B.  create a python virtualenv and source it and run `make all`

`python3 -m venv ~/.eb`
`source ~/.eb/bin/activate`
`make all`

C. initial new eb app

`eb init -p python-3.7 flask-continuous-delivery --region us-east-1`

D. Create remote eb instance

`eb create flask-continuous-delivery-env`


[YouTube Walkthrough](https://youtu.be/iSv-i1tWpQc)
