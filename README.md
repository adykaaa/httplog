httplog
=======

Small but powerful structured logging package for HTTP request logging in Go.

I modified it so that it takes the logger as a pointer and won't have to create a new copy of it, and also set sane defaults that I'm gonna use for my project.