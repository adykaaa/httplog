httplog
=======

Small but powerful structured logging package for HTTP request logging in Go.

I modified it so that it takes the logger as a pointer and won't have to create any copies of it, since this library already uses Zerolog (but it expects you to create a new global logger)