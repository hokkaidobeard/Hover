Hover
=====

[![Build Status](https://travis-ci.org/shurcooL/Hover.svg?branch=master)](https://travis-ci.org/shurcooL/Hover) [![GoDoc](https://godoc.org/github.com/shurcooL/Hover?status.svg)](https://godoc.org/github.com/shurcooL/Hover)

Hover is a work-in-progress port of Hover, a game originally created by Eric Undersander in 2000.

![](https://cloud.githubusercontent.com/assets/1924134/3011306/252b3942-df29-11e3-9068-8594e351dc69.png)

The goal of the port is to run on multiple platforms (macOS, Linux, Windows, browser,
iOS, Android) and improve technical aspects (e.g., support for higher resolutions),
while preserving the original gameplay.

Installation
------------

You'll need to have OpenGL headers (see [here](https://github.com/go-gl/glfw#installation)).

```bash
go get -u github.com/shurcooL/Hover
GOARCH=js go get -u -d github.com/shurcooL/Hover
```

Screenshot
----------

The port is incomplete; this screenshot represents the current state.

![](Screenshot.png)

Directories
-----------

| Path                                                       | Synopsis                                                                             |
|------------------------------------------------------------|--------------------------------------------------------------------------------------|
| [track](https://godoc.org/github.com/shurcooL/Hover/track) | Package track defines Hover track data structure and provides loading functionality. |

License
-------

-	[MIT License](https://opensource.org/licenses/mit-license.php)
