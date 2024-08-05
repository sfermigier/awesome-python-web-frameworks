# Awesome Python Web Frameworks


> A curated list of awesome Python Web Frameworks (micro, full-stack, REST, etc.)


[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

---

## Full-stack frameworks, including data layer (ORM)


- [Django](https://github.com/django/django) ★78361 - a high-level Python Web framework that encourages rapid development and clean, pragmatic design. Includes ORM, templatting engine, etc.
  - [Awesome Django ★6413](https://github.com/wsvincent/awesome-django)
- [Emmett](https://github.com/emmett-framework/emmett) ★1035 - a full-stack Python web framework designed with simplicity in mind.

## Full-stack frameworks, but data-layer agnostic

- [Flask](https://github.com/pallets/flask) ★67234 - a lightweight WSGI web application framework. It is designed to make getting started quick and easy, with the ability to scale up to complex applications.
  - [Awesome Flask ★1050](https://github.com/mjhea0/awesome-flask)
- [Pyramid](https://github.com/Pylons/pyramid) ★3928 - a small, fast, down-to-earth, open source Python web framework. It makes real-world web application development and deployment more fun, more predictable, and more productive.
  - [Awesome Pyramid ★531](https://github.com/uralbash/awesome-pyramid)
- [Quart](https://github.com/pallets/quart) ★2820 - Quart is an asyncio reimplementation of the popular Flask microframework API. This means that if you understand Flask you understand Quart.


## Micro-frameworks

### Sync

- [Falcon](https://github.com/falconry/falcon) ★9466 - a reliable, high-performance Python web framework for building large-scale app backends and microservices. It encourages the REST architectural style, and tries to do as little as possible while remaining highly effective. Also async.
- [Bottle](https://github.com/bottlepy/bottle) ★8350 - a fast, simple and lightweight WSGI micro web-framework for Python. It is distributed as a single file module and has no dependencies other than the Python Standard Library.
- [Hug](https://github.com/hugapi/hug) ★6856 - aims to make developing Python driven APIs as simple as possible, but no simpler. As a result, it drastically simplifies Python API development.
- [Molten](https://github.com/Bogdanp/molten) ★979 - A minimal, extensible, fast and productive framework for building HTTP APIs with Python 3.6 and later.
- [Morepath](https://github.com/morepath/morepath) ★395 - "web microframework with super powers". An application consists of models. Each type of model is published on a URL path. Content is exposed to the web using views.

### Async

- [FastAPI](https://github.com/tiangolo/fastapi) ★74319 - a modern, fast (high-performance), web framework for building APIs with Python 3.6+ based on standard Python type hints. Based on Starlette (see below).
  - [Awesome FastAPI ★4948](https://github.com/mjhea0/awesome-fastapi)
- [Sanic](https://github.com/sanic-org/sanic) ★17934 - a Python 3.7+ web server and web framework that's written to go fast. It allows the usage of the async/await syntax added in Python 3.5, which makes your code non-blocking and speedy. Based on Starlette.
  - [Awesome Sanic ★619](https://github.com/mekicha/awesome-sanic)
- [Aiohttp](https://github.com/aio-libs/aiohttp) ★14843 - Asynchronous HTTP client/server framework for asyncio and Python.
- [Starlette](https://github.com/encode/starlette) ★9870 - a lightweight ASGI framework/toolkit, which is ideal for building high performance asyncio services.
- [Litestar](https://github.com/litestar-org/litestar) ★5228 - Production-ready, Light, Flexible and Extensible ASGI API framework | Effortlessly Build Performant APIs.
- [Robyn](https://github.com/sansyrox/robyn) ★4069 - a fast and extensible async python web server with a rust runtime.
- [Fasthtml](https://github.com/AnswerDotAI/fasthtml) ★3151 - "The fastest way to create an HTML app". (Based on Starlette).
- [BlackSheep](https://github.com/Neoteroi/BlackSheep) ★1816 - BlackSheep is an asynchronous web framework to build event based web applications with Python.
- [Esmerald](https://github.com/dymmond/esmerald) ★275 - Highly scalable, performant, easy to learn, easy to code and for every sizeable and complex application.


### More

- [uapi](https://github.com/Tinche/uapi) ★86 - a high-level, extremely fast Python microframework for writing HTTP APIs, either synchronously or asynchronously. Uses a lower-level HTTP framework to run. Currently supported frameworks are aiohttp, Flask, Quart, and Starlette.


## REST frameworks

- [Django Rest Framework](https://github.com/encode/django-rest-framework) ★27962 - a powerful and flexible toolkit for building Web APIs.
- [Flask-Restful](https://github.com/flask-restful/flask-restful) ★6812 - Simple framework for creating REST APIs.
- [Eve](https://github.com/pyeve/eve) ★6680 - an open source Python REST API framework based on Flask. It allows to effortlessly build and deploy highly customizable, fully featured RESTful Web Services. Eve offers native support for MongoDB, and SQL backends via community extensions.
- [API star](https://github.com/encode/apistar) ★5575 - a framework-agnostic toolkit for working with OpenAPI or Swagger schemas.
- [Connexion](https://github.com/zalando/connexion) ★4461 - Swagger/OpenAPI First framework for Python on top of Flask with automatic endpoint validation & OAuth2 support.
- [Flask-Restx](https://github.com/python-restx/flask-restx) ★2122 - Fully featured framework for fast, easy and documented API development with Flask.
- [Flask Smorest](https://github.com/marshmallow-code/flask-smorest) ★639 - a REST API framework built upon Flask and marshmallow.
- [Ripozo](https://github.com/vertical-knowledge/ripozo) ★201 -  A tool for quickly creating REST/HATEOAS/Hypermedia APIs in python. [Dead]


## Front-end frameworks

- [Flet](https://github.com/flet-dev/flet) ★10494 - Flet enables developers to easily build realtime web, mobile and desktop apps in Python. No frontend experience required.
- [Nicegui](https://github.com/zauberzeug/nicegui) ★8467 - Create web-based user interfaces with Python. The nice way.
- [ReactPy](https://github.com/reactive-python/reactpy) ★7785 - User interfaces in Python without Javascript
- [Flexx](https://github.com/flexxui/flexx) ★3239 -  Write desktop and web apps in pure Python
- [Reactor](https://github.com/edelvalle/reactor) ★629 -  Phoenix LiveView but for Django
- [Tetra](https://github.com/samwillis/tetra) ★544 - a full stack component framework for Django using Alpine.js
- [Starfyre](https://github.com/sansyrox/starfyre) ★464 - A Python Framework for writing Reactive Front-End Applications.
- [Django-Suckpuppet](https://github.com/jonathan-s/django-sockpuppet) ★448 - Build reactive applications with the django tooling you already know and love.
- [Flask-Meld](https://github.com/mikeabrahamsen/Flask-Meld) ★311 - a library to provide server rendered templates over websockets for Flask applications to build reactive components without Javascript.
- [Reacton](https://github.com/widgetti/reacton) ★281 - A pure Python port of React for ipywidgets.
- [enaml-web](https://github.com/codelv/enaml-web) ★99 - Build interactive websites with [enaml](https://github.com/nucleic/enaml)

## Frameworks for Micropython

- [microdot](https://github.com/miguelgrinberg/microdot) ★1446 - The impossibly small web framework for Python and MicroPython.
- [MicroWebSrv](https://github.com/jczic/MicroWebSrv) ★640 - A micro HTTP web server that supports WebSockets, HTML/Python language templating and routing handlers, for MicroPython (used on Pycom modules & ESP32).
- [MicroWebSrv2](https://github.com/jczic/MicroWebSrv2) ★644 - The last micro web server for IoTs (MicroPython) or large servers (CPython), that supports WebSocket, routes, template engine and with really optimized architecture (mem allocations, async I/Os).
- [tinyweb](https://github.com/belyalov/tinyweb) ★241 - Simple and lightweight HTTP async server for MicroPython.
- [micropython-nanoweb](https://github.com/hugokernel/micropython-nanoweb) ★104 - Full async MicroPython web server with small memory footprint.
- [micropyserver](https://github.com/troublegum/micropyserver) ★113 - MicroPyServer is a simple HTTP server for MicroPython projects.
- [micropython-urouter](https://github.com/whales-chen/micropython-urouter) ★50 - A lightweight HTTP request routing processing support library based on MicroPython. The previous name was micro-route.


## Usage stats

See the "Frameworks and Libraries" section in the [Python Developers Survey 2020](https://www.jetbrains.com/lp/python-developers-survey-2020/).


![Stats](https://raw.githubusercontent.com/sfermigier/awesome-python-web-frameworks/main/python-web-frameworks-usage.png)

Update 2021: <https://lp.jetbrains.com/python-developers-survey-2021/#FrameworksLibraries>
Update 2022: <https://lp.jetbrains.com/python-developers-survey-2022/#FrameworksLibraries>


## Comparisons

- [Hello to the World in 8 Web Frameworks (Micro, Batteries Included & Async)](https://noti.st/aaronbassett/lK9Ah7/hello-to-the-world-in-8-web-frameworks-micro-batteries-included-async) - presentation by Aaron Bassett at PyCon AU (2018)


## Additional resources

- Awesome Python has some web frameworks, in two sections: [Web Frameworks](https://github.com/vinta/awesome-python#web-frameworks) and [RESTful API](https://github.com/vinta/awesome-python#restful-api) but it's not very thorough.
