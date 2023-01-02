# Awesome Python Web Frameworks


> A curated list of awesome Python Web Frameworks (micro, full-stack, REST, etc.)


[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

---

## Full-stack frameworks, including data layer (ORM)


- [Django](https://github.com/django/django) ★67935 - a high-level Python Web framework that encourages rapid development and clean, pragmatic design. Includes ORM, templatting engine, etc.
  - [Awesome Django ★6413](https://github.com/wsvincent/awesome-django)


## Full-stack frameworks, but data-layer agnostic

- [Flask](https://github.com/pallets/flask) ★61442 - a lightweight WSGI web application framework. It is designed to make getting started quick and easy, with the ability to scale up to complex applications.
  - [Awesome Flask ★1050](https://github.com/mjhea0/awesome-flask)
- [Pyramid](https://github.com/Pylons/pyramid) ★3741 - a small, fast, down-to-earth, open source Python web framework. It makes real-world web application development and deployment more fun, more predictable, and more productive.
  - [Awesome Pyramid ★531](https://github.com/uralbash/awesome-pyramid)


## Micro-frameworks

### Sync

- [Falcon](https://github.com/falconry/falcon) ★8984 - a reliable, high-performance Python web framework for building large-scale app backends and microservices. It encourages the REST architectural style, and tries to do as little as possible while remaining highly effective.
- [Bottle](https://github.com/bottlepy/bottle) ★7843 - a fast, simple and lightweight WSGI micro web-framework for Python. It is distributed as a single file module and has no dependencies other than the Python Standard Library.
- [Hug](https://github.com/hugapi/hug) ★6682 - aims to make developing Python driven APIs as simple as possible, but no simpler. As a result, it drastically simplifies Python API development.
- [Molten](https://github.com/Bogdanp/molten) ★980 - A minimal, extensible, fast and productive framework for building HTTP APIs with Python 3.6 and later.
- [Morepath](https://github.com/morepath/morepath) ★396 - "web microframework with super powers". An application consists of models. Each type of model is published on a URL path. Content is exposed to the web using views.


### Async

- [FastAPI](https://github.com/tiangolo/fastapi) ★52969 - a modern, fast (high-performance), web framework for building APIs with Python 3.6+ based on standard Python type hints. Based on Starlette (see below).
  - [Awesome FastAPI ★4948](https://github.com/mjhea0/awesome-fastapi)
- [Sanic](https://github.com/sanic-org/sanic) ★16731 - a Python 3.7+ web server and web framework that's written to go fast. It allows the usage of the async/await syntax added in Python 3.5, which makes your code non-blocking and speedy. Based on Starlette.
  - [Awesome Sanic ★619](https://github.com/mekicha/awesome-sanic)
- [Aiohttp](https://github.com/aio-libs/aiohttp) ★13144 - Asynchronous HTTP client/server framework for asyncio and Python.
- [Starlette](https://github.com/encode/starlette) ★7733 - a lightweight ASGI framework/toolkit, which is ideal for building high performance asyncio services.
- [Robyn](https://github.com/sansyrox/robyn) ★1773 - a fast and extensible async python web server with a rust runtime.
- [Starlite](https://github.com/starlite-api/starlite) ★1540 -  Light, Flexible and Extensible ASGI API framework,  offering first class typing support and a full Pydantic integration.
- [BlackSheep](https://github.com/Neoteroi/BlackSheep) ★1111 - BlackSheep is an asynchronous web framework to build event based web applications with Python.


## REST frameworks

- [Django Rest Framework](https://github.com/encode/django-rest-framework) ★24708 - a powerful and flexible toolkit for building Web APIs.
- [Eve](https://github.com/pyeve/eve) ★6569 - an open source Python REST API framework based on Flask. It allows to effortlessly build and deploy highly customizable, fully featured RESTful Web Services. Eve offers native support for MongoDB, and SQL backends via community extensions.
- [Flask-Restful](https://github.com/flask-restful/flask-restful) ★6514 - Simple framework for creating REST APIs.
- [API star](https://github.com/encode/apistar) ★5587 - a framework-agnostic toolkit for working with OpenAPI or Swagger schemas.
- [Connexion](https://github.com/zalando/connexion) ★4175 - Swagger/OpenAPI First framework for Python on top of Flask with automatic endpoint validation & OAuth2 support.
- [Flask-Restx](https://github.com/python-restx/flask-restx) ★1698 - Fully featured framework for fast, easy and documented API development with Flask.
- [Flask Smorest](https://github.com/marshmallow-code/flask-smorest) ★506 - a REST API framework built upon Flask and marshmallow.

- [Ripozo](https://github.com/vertical-knowledge/ripozo) ★197 -  A tool for quickly creating REST/HATEOAS/Hypermedia APIs in python. [Dead]

## Front-end frameworks

- [Flet](https://github.com/flet-dev/flet) ★3161 - Flet enables developers to easily build realtime web, mobile and desktop apps in Python. No frontend experience required.
- [IDOM](https://github.com/idom-team/idom) ★700 - Create highly interactive web pages purely in Python
- [Tetra](https://github.com/samwillis/tetra) ★464 - a full stack component framework for Django using Alpine.js
- [Flask-Meld](https://github.com/mikeabrahamsen/Flask-Meld) ★286 - a library to provide server rendered templates over websockets for Flask applications to build reactive components without Javascript.
- [Reacton](https://github.com/widgetti/reacton) - A pure Python port of React for ipywidgets.
- [Starfyre](https://github.com/sansyrox/starfyre) - A Python Framework for writing Reactive Front-End Applications.


## Usage stats

See the "Frameworks and Libraries" section in the [Python Developers Survey 2020](https://www.jetbrains.com/lp/python-developers-survey-2020/).


![Stats](https://raw.githubusercontent.com/sfermigier/awesome-python-web-frameworks/main/python-web-frameworks-usage.png)


## Comparisons

- [Hello to the World in 8 Web Frameworks (Micro, Batteries Included & Async)](https://noti.st/aaronbassett/lK9Ah7/hello-to-the-world-in-8-web-frameworks-micro-batteries-included-async) - presentation by Aaron Bassett at PyCon AU (2018)


## Additional resources

- Awesome Python has some web frameworks, in two sections: [Web Frameworks](https://github.com/vinta/awesome-python#web-frameworks) and [RESTful API](https://github.com/vinta/awesome-python#restful-api) but it's not very thorough.
