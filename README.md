# Http4s [![Build Status](https://travis-ci.org/http4s/http4s.svg?branch=master)](https://travis-ci.org/http4s/http4s) [![Gitter chat](https://badges.gitter.im/http4s/http4s.png)](https://gitter.im/http4s/http4s)

[![Join the chat at https://gitter.im/balatbn/http4s](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/balatbn/http4s?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

Http4s is a minimal, idiomatic Scala interface for HTTP services.  Http4s is
Scala's answer to Ruby's Rack, Python's WSGI, Haskell's WAI, and Java's
Servlets.

```scala
val service = HttpService {
    case GET -> Root / "hello" =>
      Ok("Hello, better world.")
  }
```

Learn more at [http4s.org](http://http4s.org/).

Quick start from [giter8 template](http://github.com/http4s/http4s.g8).
