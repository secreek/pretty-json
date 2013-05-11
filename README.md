pretty-json
===========

JSON formatter &amp;&amp; highlighter in one line!

## Installation

Tested only on OS X.

```
$ sudo curl -s https://raw.github.com/secreek/pretty-json/master/pj \
	>> /usr/local/bin/pj \
	&& sudo chmod +x /usr/local/bin/pj
```

## Usage

```
$ curl <url> | pj
```
or

```
$ cat <file.json> | pj
```

## Try it now

An original JSON:

```
$ curl -s http://www.seismi.org/api/eqs?limit=20
```

Now with formatter and hilighter:

```
$ curl -s http://www.seismi.org/api/eqs?limit=20 | 
```

An even complex sample:

```
curl -s https://api.github.com/events | pj
```
