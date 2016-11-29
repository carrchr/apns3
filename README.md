# APNS3

[![Build Status](https://travis-ci.org/joshfriend/apns3.svg?branch=master)](https://travis-ci.org/joshfriend/apns3)
[![Coverage Status](https://coveralls.io/repos/github/joshfriend/apns3/badge.svg?branch=develop)](https://coveralls.io/github/joshfriend/apns3?branch=develop)

A client library for Apple's APNS v3 HTTP/2 push notification service

## Requirements
A Python distribution which supports ALPN and TLSv1.2 is required. This means
that only Python 2 version 2.7.10 and higher and Python 3 version 3.5.0 and
higher are supported unless you use pyOpenSSL. Other Python implementations,
such as PyPy, may also be used as long as they provide an equivalent stdlib

# Alpha Warning
I have tested that it is possible to send pushes to Apple devices, however I
have not tested this at any significant scale and there are [many things left
to do][enhancement_issues].

[enhancement_issues]: https://github.com/joshfriend/apns3/issues?q=is%3Aissue+is%3Aopen+label%3Aenhancement
