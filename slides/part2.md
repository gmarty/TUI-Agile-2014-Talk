# Working with CI

---

# No merge hells

* Atomic commits are easier to merge
* Code refactoring won't introduce bugs

---

# Better testing

* Less time is spent on manual testing
* More environments can be tested
* Bugs are caught earlier

---

# Types of metrics

* Compliance to coding standards / coding styles / best practices
* Code complexity
* Estimated number of delivered bugs
* Code coverage
* Web performance

---

## Metrics are used for

* Tracking evolution of quality
* Finding what/when refactoring is needed
* Find poorly tested code
* Estimate the technical debt
* Track performance regressions

---

# Overall advantages

Tell me about what CI changed in your job?

---

# Developers

> * « We push continually to trunk. »
> * « I get a quick feedback on my code and can fix bugs even before the testers notice! »

<img src="img/developer.svg" height="800" style="vertical-align:middle;border:none;box-shadow:none;background:transparent; -webkit-transform:scaleX(-1);transform:scaleX(-1);float:left" alt="Developer" title="Developer">

---

# Testers

> * « We can focus on testing new features. »
> * « All the environments are tested according to our NFR. »

<img src="img/tester.svg" height="800" style="vertical-align:middle;border:none;box-shadow:none;background:transparent; -webkit-transform:scaleX(-1);transform:scaleX(-1);float:left" alt="Tester" title="Tester">

---

# Product owner

> * « The metrics are valuable to take good decisions. »
> * « We can work more efficiently on new features. »

<img src="img/product-owner.svg" height="800" style="vertical-align:middle;border:none;box-shadow:none;background:transparent; -webkit-transform:scaleX(-1);transform:scaleX(-1);float:left" alt="Product owner" title="Product owner">

---

# Scrum master

> * « The happiness level in the team increased. »
> * « We iterate faster. »

<img src="img/scrum-master.svg" height="800" style="vertical-align:middle;border:none;box-shadow:none;background:transparent; -webkit-transform:scaleX(-1);transform:scaleX(-1);float:left" alt="Scrum master" title="Scrum master">

---

# Development using CI

<img src="img/happy.svg" height="200" style="border:none;box-shadow:none;background:transparent" alt="Happy" title="Happy">

---

# DIY or use a service

* Install on your own servers
* Or, use a service provider

Note:
Ideal to integrate into an existing backend CI.

---

# Things you'll need

* Git to use (and abuse) branching
* Node.js on your server for builds and tests
* New way of working:
    * Create a culture for test
    * Modularise development

Note:
If possible, find a better bullet 3.

---

# Some services

* VCS as a service ([Github](https://www.github.com/))
* CI as a service ([Travis CI](https://travis-ci.org/))
* Static analysis as a service ([CodeClimate](https://codeclimate.com/))
* Browser testing as a service ([SauceLabs](https://saucelabs.com/))

---

# Some tools

* Testing framework ([Karma](http://karma-runner.github.io/))
* Source linter ([JSHint](http://www.jshint.com/), [ESLint](https://github.com/eslint/eslint))
* Code coverage ([Istanbul](http://gotwarlost.github.io/istanbul/))
* Static analysis & complexity ([Plato](https://github.com/es-analysis/plato))
