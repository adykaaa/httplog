httplog
=======

Small but powerful structured logging package for HTTP request logging in Go.

Did a quick and dirty modification of this package. Now it uses a passed in configured Logger, instead of returning a new one, and taking it in as a value.
I'm mostly using Zerolog anyways in my projects, and I'm going to configure it elsewhere, and want the logging middleware to adapt. Now it does