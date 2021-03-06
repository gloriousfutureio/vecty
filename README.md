<p align="center">
	<img src="https://drive.google.com/uc?id=0B2Crq763J1N4SnpwalZTeVE5RmM" />
</p>

Vecty is a [React](https://facebook.github.io/react/)-like library for [GopherJS](https://github.com/gopherjs/gopherjs) so that you can do frontend development in Go instead of writing JavaScript/HTML/CSS.

[![Build Status](https://travis-ci.org/gopherjs/vecty.svg?branch=master)](https://travis-ci.org/gopherjs/vecty) [![GoDoc](https://godoc.org/github.com/gopherjs/vecty?status.svg)](https://godoc.org/github.com/gopherjs/vecty)

Features
========

-	Share frontend and backend code.
-	Write everything in Go -- not JS/HTML/CSS!
-	XSS protection: unsafe HTML must be explicitly denoted as such.
-	Reusability: share components by making Go packages that others can import!

Goals
=====

-	Simplicity
	-	Keep things as simple as possible to understand *for newcomers*.
	-	Designed from the ground up to be easily mastered (like Go)!
-	Performance
	-	As efficient as possible, make it clear what each operation in your webpage will do.
	-	Same performance as just using plain JS/HTML/CSS.
-	Composability
	-	Nest components to form your entire user interface, seperate them logically as you would any normal Go package.

Current Status
==============

**Vecty is currently considered to be an experimental work-in-progress.**

-	APIs will change.
-	The scope of Vecty is only ~80% defined currently.
-	There are a number of important [open issues](https://github.com/gopherjs/vecty/issues).

Community
=========

- Join us in the [#gopherjs](https://gophers.slack.com/messages/gopherjs/) and [#vecty](https://gophers.slack.com/messages/vecty/) channels on the [Gophers Slack](https://gophersinvite.herokuapp.com/)!
