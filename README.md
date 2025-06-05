# Awesome Python Web Frameworks


> A curated list of awesome Python Web Frameworks (micro, full-stack, REST, etc.)


[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

---

## Full-stack frameworks, including data layer (ORM)


- [Django](https://github.com/django/django) ★83813 - a high-level Python Web framework that encourages rapid development and clean, pragmatic design. Includes ORM, templatting engine, etc.
  - [Awesome Django](https://github.com/wsvincent/awesome-django) ★10324
- [Emmett](https://github.com/emmett-framework/emmett) ★1134 - a full-stack Python web framework designed with simplicity in mind.

## Full-stack frameworks, but data-layer agnostic

- [Flask](https://github.com/pallets/flask) ★69679 - a lightweight WSGI web application framework. It is designed to make getting started quick and easy, with the ability to scale up to complex applications.
  - [Awesome Flask](https://github.com/mjhea0/awesome-flask) ★1600
- [Pyramid](https://github.com/Pylons/pyramid) ★4031 - a small, fast, down-to-earth, open source Python web framework. It makes real-world web application development and deployment more fun, more predictable, and more productive.
  - [Awesome Pyramid](https://github.com/uralbash/awesome-pyramid) ★559
- [Quart](https://github.com/pallets/quart) ★3311 - Quart is an asyncio reimplementation of the popular Flask microframework API. This means that if you understand Flask you understand Quart.

## Micro-frameworks

### Sync

- [Falcon](https://github.com/falconry/falcon) ★9660 - a reliable, high-performance Python web framework for building large-scale app backends and microservices. It encourages the REST architectural style, and tries to do as little as possible while remaining highly effective. Also async.
- [Bottle](https://github.com/bottlepy/bottle) ★8609 - a fast, simple and lightweight WSGI micro web-framework for Python. It is distributed as a single file module and has no dependencies other than the Python Standard Library.
- [Molten](https://github.com/Bogdanp/molten) ★974 - A minimal, extensible, fast and productive framework for building HTTP APIs with Python 3.6 and later.

### Async

- [FastAPI](https://github.com/tiangolo/fastapi) ★85925 - a modern, fast (high-performance), web framework for building APIs with Python 3.6+ based on standard Python type hints. Based on Starlette (see below).
  - [Awesome FastAPI](https://github.com/mjhea0/awesome-fastapi) ★9792
- [Sanic](https://github.com/sanic-org/sanic) ★18393 - a Python 3.7+ web server and web framework that's written to go fast. It allows the usage of the async/await syntax added in Python 3.5, which makes your code non-blocking and speedy.
  - [Awesome Sanic](https://github.com/mekicha/awesome-sanic) ★760
- [Aiohttp](https://github.com/aio-libs/aiohttp) ★15721 - Asynchronous HTTP client/server framework for asyncio and Python.
- [Starlette](https://github.com/encode/starlette) ★11070 - a lightweight ASGI framework/toolkit, which is ideal for building high performance asyncio services.
  - [Awesome Starlette](https://github.com/sfermigier/awesome-starlette) ★1
- [Litestar](https://github.com/litestar-org/litestar) ★6735 - Production-ready, Light, Flexible and Extensible ASGI API framework | Effortlessly Build Performant APIs.
  - [Awesome Litestar](https://github.com/litestar-org/awesome-litestar) ★116
- [Fasthtml](https://github.com/AnswerDotAI/fasthtml) ★6392 - "The fastest way to create an HTML app". (Based on Starlette).
- [Robyn](https://github.com/sansyrox/robyn) ★5969 - a fast and extensible async python web server with a rust runtime.
- [BlackSheep](https://github.com/Neoteroi/BlackSheep) ★2172 - BlackSheep is an asynchronous web framework to build event based web applications with Python.
- [Esmerald](https://github.com/dymmond/esmerald) ★344 - Highly scalable, performant, easy to learn, easy to code and for every sizeable and complex application.
- [MicroPie](https://github.com/patx/micropie) ★195 - MicroPie is an ultra-micro ASGI Python web framework that gets out of your way.
- [nanoasgi](https://github.com/qweeze/nanoasgi) ★23 - A toy ASGI web framework (170 lines) (Dead, but useful for educational puposes.)


### More

- [uapi](https://github.com/Tinche/uapi) ★92 - a high-level, extremely fast Python microframework for writing HTTP APIs, either synchronously or asynchronously. Uses a lower-level HTTP framework to run. Currently supported frameworks are aiohttp, Flask, Quart, and Starlette.


## REST frameworks

- [Django Rest Framework](https://github.com/encode/django-rest-framework) ★29183 - a powerful and flexible toolkit for building Web APIs.
- [Eve](https://github.com/pyeve/eve) ★6728 - an open source Python REST API framework based on Flask. It allows to effortlessly build and deploy highly customizable, fully featured RESTful Web Services. Eve offers native support for MongoDB, and SQL backends via community extensions.
- [Connexion](https://github.com/zalando/connexion) ★4550 - Swagger/OpenAPI First framework for Python on top of Flask with automatic endpoint validation & OAuth2 support.
- [Flask-Restx](https://github.com/python-restx/flask-restx) ★2212 - Fully featured framework for fast, easy and documented API development with Flask.
- [Flask Smorest](https://github.com/marshmallow-code/flask-smorest) ★691 - a REST API framework built upon Flask and marshmallow.
- [Djapy](https://github.com/Bishwas-py/djapy) ★108 - Django coupled with Pydantic, RestAPI framework


## Front-end frameworks

- [Reflex](https://github.com/reflex-dev/reflex) ★23278 - Reflex is a library to build full-stack web apps in pure Python.
- [Flet](https://github.com/flet-dev/flet) ★13358 - Flet enables developers to easily build realtime web, mobile and desktop apps in Python. No frontend experience required.
- [Nicegui](https://github.com/zauberzeug/nicegui) ★12490 - Create web-based user interfaces with Python. The nice way.
- [ReactPy](https://github.com/reactive-python/reactpy) ★8022 - User interfaces in Python without Javascript
- [Mesop](https://github.com/google/mesop) ★6294 - a Python-based UI framework that allows you to rapidly build web apps like demos and internal apps.
- [Panel](https://github.com/holoviz/panel) ★5250 - The Powerful Data Exploration & Web App Framework for Python.
  - [Awesome Panel](https://awesome-panel.org/) ★342.
- [Flexx](https://github.com/flexxui/flexx) ★3332 -  Write desktop and web apps in pure Python
- [Django-Unicorn](https://github.com/adamghill/django-unicorn) ★2521
- [Reactor](https://github.com/edelvalle/reactor) ★638 -  Phoenix LiveView but for Django
- [Tetra](https://github.com/tetra-framework/tetra) ★598 - a full stack component framework for Django using Alpine.js
- [Starfyre](https://github.com/sansyrox/starfyre) ★566 - A Python Framework for writing Reactive Front-End Applications.
- [Django-Suckpuppet](https://github.com/jonathan-s/django-sockpuppet) ★452 - Build reactive applications with the django tooling you already know and love.
- [Flask-Meld](https://github.com/mikeabrahamsen/Flask-Meld) ★315 - a library to provide server rendered templates over websockets for Flask applications to build reactive components without Javascript.
- [Reacton](https://github.com/widgetti/reacton) ★309 - A pure Python port of React for ipywidgets.
- [enaml-web](https://github.com/codelv/enaml-web) ★104 - Build interactive websites with [enaml](https://github.com/nucleic/enaml)

## Frameworks for Micropython

- [microdot](https://github.com/miguelgrinberg/microdot) ★1666 - The impossibly small web framework for Python and MicroPython.
- [MicroWebSrv2](https://github.com/jczic/MicroWebSrv2) ★683 - The last micro web server for IoTs (MicroPython) or large servers (CPython), that supports WebSocket, routes, template engine and with really optimized architecture (mem allocations, async I/Os).
- [MicroWebSrv](https://github.com/jczic/MicroWebSrv) ★656 - A micro HTTP web server that supports WebSockets, HTML/Python language templating and routing handlers, for MicroPython (used on Pycom modules & ESP32).
- [tinyweb](https://github.com/belyalov/tinyweb) ★263 - Simple and lightweight HTTP async server for MicroPython.
- [micropyserver](https://github.com/troublegum/micropyserver) ★143 - MicroPyServer is a simple HTTP server for MicroPython projects.
- [micropython-nanoweb](https://github.com/hugokernel/micropython-nanoweb) ★113 - Full async MicroPython web server with small memory footprint.
- [micropython-urouter](https://github.com/whales-chen/micropython-urouter) ★51 - A lightweight HTTP request routing processing support library based on MicroPython. The previous name was micro-route.

## Http servers

- [gunicorn](https://github.com/benoitc/gunicorn) ★10134 - 'Green Unicorn' is a WSGI HTTP Server for UNIX, fast clients and sleepy applications.
- [uvicorn](https://github.com/encode/uvicorn) ★9308 - Uvicorn is an ASGI web server implementation for Python.
- [uwsgi](https://github.com/unbit/uwsgi) ★3501 - application server container, implement application server interfaces for various languages and platforms: WSGI, PSGI, Rack, Lua WSAPI, CGI, PHP, Go.
- [Granian](https://github.com/emmett-framework/granian) ★3562 - A Rust HTTP server for Python applications.
- [bjoern](https://github.com/jonashaag/bjoern) ★3021 - A screamingly fast Python 2/3 WSGI server written in C.
- [daphne](https://github.com/django/daphne) ★2521 - A HTTP, HTTP2 and WebSocket protocol server for ASGI and ASGI-HTTP, developed to power Django Channels.
- [Waitress](https://github.com/Pylons/waitress) ★1510 - A pure-Python WSGI server, it's simple, lightweight, and production-ready. It's often used with Pyramid and other WSGI applications.
- [hypercorn](https://github.com/pgjones/hypercorn) ★1315 - ASGI server based on the sans-io hyper, h11, h2, and wsproto libraries.

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
