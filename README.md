# Awesome Python Web Frameworks


> A curated list of awesome Python Web Frameworks (micro, full-stack, REST, etc.)


[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

---

## Full-stack frameworks, including data layer (ORM)


- [Django ★79447](https://github.com/django/django) - a high-level Python Web framework that encourages rapid development and clean, pragmatic design. Includes ORM, templatting engine, etc.
  - [Awesome Django ★9307](https://github.com/wsvincent/awesome-django)
- [Emmett ★1053](https://github.com/emmett-framework/emmett) - a full-stack Python web framework designed with simplicity in mind.

## Full-stack frameworks, but data-layer agnostic

- [Flask ★67720](https://github.com/pallets/flask) - a lightweight WSGI web application framework. It is designed to make getting started quick and easy, with the ability to scale up to complex applications.
  - [Awesome Flask ★1461](https://github.com/mjhea0/awesome-flask)
- [Pyramid ★3944](https://github.com/Pylons/pyramid) - a small, fast, down-to-earth, open source Python web framework. It makes real-world web application development and deployment more fun, more predictable, and more productive.
  - [Awesome Pyramid ★550](https://github.com/uralbash/awesome-pyramid)
- [Quart ★2922](https://github.com/pallets/quart) - Quart is an asyncio reimplementation of the popular Flask microframework API. This means that if you understand Flask you understand Quart.


## Micro-frameworks

### Sync

- [Falcon ★9509](https://github.com/falconry/falcon) - a reliable, high-performance Python web framework for building large-scale app backends and microservices. It encourages the REST architectural style, and tries to do as little as possible while remaining highly effective. Also async.
- [Bottle ★8394](https://github.com/bottlepy/bottle) - a fast, simple and lightweight WSGI micro web-framework for Python. It is distributed as a single file module and has no dependencies other than the Python Standard Library.
- [Hug ★6860](https://github.com/hugapi/hug) - aims to make developing Python driven APIs as simple as possible, but no simpler. As a result, it drastically simplifies Python API development.
- [Molten ★978](https://github.com/Bogdanp/molten) - A minimal, extensible, fast and productive framework for building HTTP APIs with Python 3.6 and later.
- [Morepath ★395](https://github.com/morepath/morepath) - "web microframework with super powers". An application consists of models. Each type of model is published on a URL path. Content is exposed to the web using views.

### Async

- [FastAPI ★76235](https://github.com/tiangolo/fastapi) - a modern, fast (high-performance), web framework for building APIs with Python 3.6+ based on standard Python type hints. Based on Starlette (see below).
  - [Awesome FastAPI ★8440](https://github.com/mjhea0/awesome-fastapi)
- [Sanic ★18030](https://github.com/sanic-org/sanic) - a Python 3.7+ web server and web framework that's written to go fast. It allows the usage of the async/await syntax added in Python 3.5, which makes your code non-blocking and speedy. Based on Starlette.
  - [Awesome Sanic ★753](https://github.com/mekicha/awesome-sanic)
- [Aiohttp ★15035](https://github.com/aio-libs/aiohttp) - Asynchronous HTTP client/server framework for asyncio and Python.
- [Starlette ★10120](https://github.com/encode/starlette) - a lightweight ASGI framework/toolkit, which is ideal for building high performance asyncio services.
- [Litestar ★5408](https://github.com/litestar-org/litestar) - Production-ready, Light, Flexible and Extensible ASGI API framework | Effortlessly Build Performant APIs.
- [Fasthtml ★5216](https://github.com/AnswerDotAI/fasthtml) - "The fastest way to create an HTML app". (Based on Starlette).
- [Robyn ★4291](https://github.com/sansyrox/robyn) - a fast and extensible async python web server with a rust runtime.
- [BlackSheep ★1858](https://github.com/Neoteroi/BlackSheep) - BlackSheep is an asynchronous web framework to build event based web applications with Python.
- [Esmerald ★300](https://github.com/dymmond/esmerald) - Highly scalable, performant, easy to learn, easy to code and for every sizeable and complex application.


### More

- [uapi ★88](https://github.com/Tinche/uapi) - a high-level, extremely fast Python microframework for writing HTTP APIs, either synchronously or asynchronously. Uses a lower-level HTTP framework to run. Currently supported frameworks are aiohttp, Flask, Quart, and Starlette.


## REST frameworks

- [Django Rest Framework ★28224](https://github.com/encode/django-rest-framework) - a powerful and flexible toolkit for building Web APIs.
- [Flask-Restful ★6826](https://github.com/flask-restful/flask-restful) - Simple framework for creating REST APIs.
- [Eve ★6700](https://github.com/pyeve/eve) - an open source Python REST API framework based on Flask. It allows to effortlessly build and deploy highly customizable, fully featured RESTful Web Services. Eve offers native support for MongoDB, and SQL backends via community extensions.
- [API star ★5573](https://github.com/encode/apistar) - a framework-agnostic toolkit for working with OpenAPI or Swagger schemas.
- [Connexion ★4475](https://github.com/zalando/connexion) - Swagger/OpenAPI First framework for Python on top of Flask with automatic endpoint validation & OAuth2 support.
- [Flask-Restx ★2150](https://github.com/python-restx/flask-restx) - Fully featured framework for fast, easy and documented API development with Flask.
- [Flask Smorest ★656](https://github.com/marshmallow-code/flask-smorest) - a REST API framework built upon Flask and marshmallow.
- [Ripozo ★201](https://github.com/vertical-knowledge/ripozo) -  A tool for quickly creating REST/HATEOAS/Hypermedia APIs in python. [Dead]


## Front-end frameworks

- [Flet ★11052](https://github.com/flet-dev/flet) - Flet enables developers to easily build realtime web, mobile and desktop apps in Python. No frontend experience required.
- [Nicegui ★8957](https://github.com/zauberzeug/nicegui) - Create web-based user interfaces with Python. The nice way.
- [ReactPy ★7852](https://github.com/reactive-python/reactpy) - User interfaces in Python without Javascript
- [Mesop ★5365](https://github.com/google/mesop) - a Python-based UI framework that allows you to rapidly build web apps like demos and internal apps.
- [Flexx ★3252](https://github.com/flexxui/flexx) -  Write desktop and web apps in pure Python
- [Reactor ★633](https://github.com/edelvalle/reactor) -  Phoenix LiveView but for Django
- [Tetra ★555](https://github.com/samwillis/tetra) - a full stack component framework for Django using Alpine.js
- [Starfyre ★496](https://github.com/sansyrox/starfyre) - A Python Framework for writing Reactive Front-End Applications.
- [Django-Suckpuppet ★449](https://github.com/jonathan-s/django-sockpuppet) - Build reactive applications with the django tooling you already know and love.
- [Flask-Meld ★314](https://github.com/mikeabrahamsen/Flask-Meld) - a library to provide server rendered templates over websockets for Flask applications to build reactive components without Javascript.
- [Reacton ★291](https://github.com/widgetti/reacton) - A pure Python port of React for ipywidgets.
- [enaml-web ★99](https://github.com/codelv/enaml-web) - Build interactive websites with [enaml](https://github.com/nucleic/enaml)

## Frameworks for Micropython

- [microdot ★1487](https://github.com/miguelgrinberg/microdot) - The impossibly small web framework for Python and MicroPython.
- [MicroWebSrv2 ★659](https://github.com/jczic/MicroWebSrv2) - The last micro web server for IoTs (MicroPython) or large servers (CPython), that supports WebSocket, routes, template engine and with really optimized architecture (mem allocations, async I/Os).
- [MicroWebSrv ★645](https://github.com/jczic/MicroWebSrv) - A micro HTTP web server that supports WebSockets, HTML/Python language templating and routing handlers, for MicroPython (used on Pycom modules & ESP32).
- [tinyweb ★247](https://github.com/belyalov/tinyweb) - Simple and lightweight HTTP async server for MicroPython.
- [micropyserver ★120](https://github.com/troublegum/micropyserver) - MicroPyServer is a simple HTTP server for MicroPython projects.
- [micropython-nanoweb ★103](https://github.com/hugokernel/micropython-nanoweb) - Full async MicroPython web server with small memory footprint.
- [micropython-urouter ★50](https://github.com/whales-chen/micropython-urouter) - A lightweight HTTP request routing processing support library based on MicroPython. The previous name was micro-route.

## Http servers

- [gunicorn ★9772](https://github.com/benoitc/gunicorn) - gunicorn 'Green Unicorn' is a WSGI HTTP Server for UNIX, fast clients and sleepy applications. .
- [uvicorn ★8421](https://github.com/encode/uvicorn) - Uvicorn is an ASGI web server implementation for Python.
- [Granian ★2685](https://github.com/emmett-framework/granian) - A Rust HTTP server for Python applications.
- [daphne ★2370](https://github.com/django/daphne) - A HTTP, HTTP2 and WebSocket protocol server for ASGI and ASGI-HTTP, developed to power Django Channels.
- [Waitress ★1438](https://github.com/Pylons/waitress) - A pure-Python WSGI server, it's simple, lightweight, and production-ready. It's often used with Pyramid and other WSGI applications.
- [hypercorn ★1127](https://github.com/pgjones/hypercorn) - ASGI server based on the sans-io hyper, h11, h2, and wsproto libraries.

## Usage stats

See the "Frameworks and Libraries" section in the [Python Developers Survey 2020](https://www.jetbrains.com/lp/python-developers-survey-2020/).

![Stats](https://raw.githubusercontent.com/sfermigier/awesome-python-web-frameworks/main/python-web-frameworks-usage.png)

- Update 2021: <https://lp.jetbrains.com/python-developers-survey-2021/#FrameworksLibraries>
- Update 2022: <https://lp.jetbrains.com/python-developers-survey-2022/#FrameworksLibraries>
- Update 2023: <https://lp.jetbrains.com/python-developers-survey-2023/#FrameworksLibraries>


## Comparisons

- [Hello to the World in 8 Web Frameworks (Micro, Batteries Included & Async)](https://noti.st/aaronbassett/lK9Ah7/hello-to-the-world-in-8-web-frameworks-micro-batteries-included-async) - presentation by Aaron Bassett at PyCon AU (2018)


## Additional resources

- Awesome Python has some web frameworks, in two sections: [Web Frameworks](https://github.com/vinta/awesome-python#web-frameworks) and [RESTful API](https://github.com/vinta/awesome-python#restful-api) but it's not very thorough.
