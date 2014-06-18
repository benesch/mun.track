We love pull requests. Here's a quick guide.

## Getting started

### Node.js

First, install [Node.js][node], which we use as our webserver.

On OS X, if you have [Homebrew][brew] installed, run

```
brew install node
```

Otherwise, follow the instructions for your platform.

### Clone

Fork, then clone the repo:

```
git clone git@github.com:<username>/mun.track.git
```

Install the required packages:

```
cd mun.track
npm install
```

Then launch the development server:

```
npm start
```

You should have a local copy of mun.track running at <http://localhost:3000>.


## Developing

Create a topic branch:

```
git checkout -b super-cool-feature
```

Hack away! Then commit your changes:

```
git commit
```

## Submission

Push to your fork

```
git push
```

then [submit a pull request][pr].

## Your code #@$%*@$ sucks!

I wrote this in high school! Cut me some slack.


[brew]: http://brew.sh
[node]: http://nodejs.org
[pr]: https://github.com/benesch/mun.track/compare/
