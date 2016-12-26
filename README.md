Doorsale

Doorsale is open source e-commerce solution, simplicity in designed is to thrive sales and reduce development effort.

## Setting up Doorsale e-commerce
Installation
Before you can start with your e-commerce project, lets install Doorsale.

Virtual environment
Create a new virtual environment for Doorsale, its isolated Python environment which are more practical than installing Doorsale systemwide. They also allow installing packages without root privileges, you may create separate virtualenv for each of your e-commerce site.

$ virtualenv doorsale_env && source doorsale_env/bin/activate
Install Doorsale
Recommend way to install Doorsale is via pip, it will be easy to upgrade to latest version. Alternatively you can download repository and install with via setuptools python setup.py install

$ pip install --upgrade git+https://github.com/JoyNas/doorsale.git#egg=Doorsale
Install LESS & Yuglify
Install LESS & Yuglify nodejs packages, which will be used by django-pipeline for javascript and CSS processing, nodejs setup also include npm package manager.

$ npm install -g less yuglify

## Built With

- [Django](https://github.com/django/django) &mdash; Web development framework for python, we utilizes full stack.
- [LESS](https://github.com/less/less.js) &mdash; Our styling totally done in LESS, a preprocessor for CSS.
- [Django-Pipeline](https://github.com/cyberdelia/django-pipeline) &mdash; We use django-pipeline to compile & compress LESS and also Javascript before deployment.
- [PostgreSQL](http://www.postgresql.org/) &mdash; Our primary database is PostgreSQL, although project intended to support all databases that Django supports.


## Contributing

Doorsale is free and open-source, I support and encourage an active healthy community that accepts contributions from the public – **including you!**

We look forward to seeing your pull requests!


## Screenshot

![Doorsale Demo Screenshot](https://raw.github.com/mysteryjeans/doorsale-demo/master/media/images/demo-screenshot.png)
