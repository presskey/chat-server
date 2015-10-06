# Simple Chat Server

Minimal Rails application with [Faye](http://faye.jcoglan.com) middleware and [Thin](http://code.macournoyer.com/thin/) as a default web server.

## Installation
```
$ git clone git@github.com:presskey/chat-server.git
$ cd chat-server/
$ bundle install
```

## Usage
```
$ rails s
```

Faye service is mounted at root path, clients should connect to [http://localhost:3000](http://localhost:3000)

## License
Simple Chat Server is released under the [MIT License](http://www.opensource.org/licenses/MIT).
