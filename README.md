<p align="center">
	<img src="https://googledrive.com/host/0B2Crq763J1N4QkNHcHdxcTdxYjg/vecty_logo.png" />
</p>

Vecty is a [React](https://facebook.github.io/react/)-like library for [GopherJS](https://github.com/gopherjs/gopherjs) so that you can do frontend development in Go instead of writing JavaScript/HTML/CSS.

⚠ Experimental!
=================

Beware, this is a fork of [gopherjs/vecty](https://github.com/gopherjs/vecty) while I figure out how to improve a few key elements:

- [x] Simplify the component architecture from a user (not implementor's) perspective.
- [x] Provide better code documentation.
- [x] Provide `Mount` and `Unmount` component events.
- [x] Add a simple clock example.
- [x] Fix [document how to skip/short-circuit reconciliation](https://github.com/gopherjs/vecty/issues/27)
- [ ] Fix [Cursor moves when textbox value is updated](https://github.com/gopherjs/vecty/issues/50)
- [ ] Fix [Better list element reuse / "keys"](https://github.com/gopherjs/vecty/issues/25)
- [ ] Fix [Unsafe HTML injection](https://github.com/gopherjs/vecty/issues/20)
- [ ] Fix [CSS styling](https://github.com/gopherjs/vecty/issues/22)
- [ ] maybe conclude? [Server-side rendering](https://github.com/gopherjs/vecty/issues/23)
- [ ] maybe fix? [determine how best to perform testing](https://github.com/gopherjs/vecty/issues/29)
- [ ] Add a tutorial / walkthrough.
- [ ] Extensive documentation.

Eventually, I hope to upstream most of these changes with several long-winded PRs.

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

Community
=========

- Join us in the [#gopherjs channel](https://gophers.slack.com/messages/gopherjs/) on the [Gophers Slack](https://gophersinvite.herokuapp.com/)!
