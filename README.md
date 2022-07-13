# PyRVAscript

We are going to talk about why pyscript is a big deal, and how to get started!

First, Let do an [intro](https://github.com/aqemery/PyRVAscript/blob/main/Intro.md) to set the stage.


# PyScript - programming for the 99%

Introduced at pycon 2022, PyScript utilized [Pyodide](https://pyodide.org/en/stable/) to run python in the browser to create dynamic web applications.

A warning from https://pyscript.net

> Please be advised that PyScript is very alpha and under heavy development. There are many known issues, from usability to loading times, and you should expect things to change often. We encourage people to play and explore with PyScript, but at this time we do not recommend using it for production.

Check out the [issue backlog](https://github.com/pyscript/pyscript/issues)



From [real python intro](https://realpython.com/pyscript-python-in-browser/)

> One of the goals of PyScript is to make the Web a friendly place for anyone wanting to learn to code, including kids. The framework achieves that goal by not requiring any installation or configuration process beyond your existing text editor and a browser. A side effect is that PyScript simplifies sharing your work with others.


From [PyScript README](https://github.com/pyscript/pyscript)

> PyScript is a Pythonic alternative to [Scratch](https://scratch.mit.edu), JSFiddle, and other "easy to use" programming frameworks, with the goal of making the web a friendly, hackable place where anyone can author interesting and interactive applications.

> PyScript is a meta project that aims to combine multiple open technologies into a framework that allows users to create sophisticated browser applications with Python. It integrates seamlessly with the way the DOM works in the browser and allows users to add Python logic in a way that feels natural both to web and Python developers.

## Install
![Screen Shot 2022-07-13 at 4 44 20 PM](https://user-images.githubusercontent.com/2616927/178830938-297415a5-bbae-4f0f-bca2-d101871f3c74.png)


## Examples

You can [download](https://github.com/pyscript/pyscript/archive/refs/heads/main.zip) PyScrip and play with some of the examples. There is a exception that a number of them do not work if directly run from opening the files. You can get arround this by initilizing a webserver on the examples folder.
`python -m http.server 8000`

Or you can just see some examples here: https://pyscript.net/examples/

Lets look at some of the example and the code

* Hello World - [demo](https://pyscript.net/examples/hello_world.html) - [code](https://github.com/pyscript/pyscript/blob/main/examples/hello_world.html)
* Simple CLock - [demo](https://pyscript.net/examples/simple_clock.html) - [code](https://github.com/pyscript/pyscript/blob/main/examples/simple_clock.html) [utils file](https://github.com/pyscript/pyscript/blob/main/examples/utils.py)

* REPL - [demo](https://pyscript.net/examples/repl.html) - [code](https://github.com/pyscript/pyscript/blob/main/examples/repl.html) run `import antigravity` than `antigravity.fly()`

## Other Random fun examples

* [rolling dice](http://www.ptmcg.com/dev/pyscript/random_nums_with_score.html)
* [ray cast](https://pyscript.net/examples/webgl/raycaster/index.html) - [code](https://github.com/pyscript/pyscript/blob/main/examples/webgl/raycaster/index.html)
* [world map](https://pyscript.net/examples/folium.html) - [code](https://github.com/pyscript/pyscript/blob/main/examples/folium.html)

* [streaming graph](https://pyscript.net/examples/panel_stream.html) - [code](https://github.com/pyscript/pyscript/blob/main/examples/panel_stream.html)


* [taxi](https://pyscript.net/examples/panel_deckgl.html) - [code](https://github.com/pyscript/pyscript/blob/main/examples/panel_deckgl.html)



How imports work? 
What about custom imports?
Built in visual components?
Interacting with javascript?
Using pyscript in an existing js app?



Pyscript styling?
Pyscript gaming?
Prscript environment

Cookies
SSO GitHub/ aws


Phone sensors

Publish to GitHub pages

Local file system
Running linux commands in subprocess




Ipyhon
Retirement calc 



* https://www.gatsbyjs.com
* https://anaconda.cloud/announcing-pyscript-versioning
* https://realpython.com/pyscript-python-in-browser/
* https://github.com/pyscript/pyscript/issues
* https://discourse.holoviz.org/t/panel-in-pyscript-example/3746
* https://www.jhanley.com/pyscript-graphics/
* https://gitlab.com/imbev/pywebcanvas/-/tree/master/
