# Continuous
# Integration
## for Frontend code
### TUI Agile 2014

[Guillaume Marty](http://gu.illau.me)

<img src="img/tui-uk-ireland.svg" height="100" style="border:none;box-shadow:none;background:transparent" alt="TUI UK & Ireland" title="TUI UK & Ireland">

Note:
28 January 2014

---

# About me

* In the web for +10 years
* Working at TUI since late 2012
* Excuse my <img src="img/French.svg" height="20" style="vertical-align:middle" alt="French" title="French">!

---

# This talk

* Frontend only
* <img src="img/JavaScript.svg" height="30" style="vertical-align:middle" alt="JavaScript" title="JavaScript"> JavaScript focused
* For non technical audience

---

# The team

* <img src="img/product-owner.svg" height="70" style="vertical-align:middle;border:none;box-shadow:none;background:transparent" alt="Product owner" title="Product owner"> Product owner
* <img src="img/developer.svg" height="70" style="vertical-align:middle;border:none;box-shadow:none;background:transparent" alt="Developers" title="Developers"> Developers
* <img src="img/tester.svg" height="70" style="vertical-align:middle;border:none;box-shadow:none;background:transparent" alt="Testers" title="Testers"> Testers
* <img src="img/scrum-master.svg" height="70" style="vertical-align:middle;border:none;box-shadow:none;background:transparent" alt="Scrum master" title="Scrum master"> Scrum master

Note:
Introduction
Description of the problem

---

# A sprint without CI

1. Development
2. Merge, build & deploy
3. Test
4. Go live

---

Looks good, no?

---

No

---

# Issues

What issues do you face in your job?

---

# Developers

> * « Merging takes too much time. »
> * « Merges introduce new bugs. »

<img src="img/developer.svg" height="800" style="vertical-align:middle;border:none;box-shadow:none;background:transparent; -webkit-transform:scaleX(-1);transform:scaleX(-1);float:left" alt="Developer" title="Developer">

Note:
Complex development then merged into the trunk.

---

# Testers

> * « Regressions can occur so we must retest everything all the time. »
> * « We can't test on all the environments. »

<img src="img/tester.svg" height="800" style="vertical-align:middle;border:none;box-shadow:none;background:transparent; -webkit-transform:scaleX(-1);transform:scaleX(-1);float:left" alt="Tester" title="Tester">

Note:
Testing is sampled according the devices marketshare.

---

# Product owner

> * « I have no idea of the quality of the code we ship. »
> * « Are we creating a technical debt? »

<img src="img/product-owner.svg" height="800" style="vertical-align:middle;border:none;box-shadow:none;background:transparent; -webkit-transform:scaleX(-1);transform:scaleX(-1);float:left" alt="Product owner" title="Product owner">

Note:
« The only metric I have is the number of defects opened. »
Technical debt must be repaid at some point via refactoring, partial rewriting to avoid causing
instabilities.

---

# Scrum master

> * « These issues cause unhappiness and frustration. »
> * « The velocity could be increased. »

<img src="img/scrum-master.svg" height="800" style="vertical-align:middle;border:none;box-shadow:none;background:transparent; -webkit-transform:scaleX(-1);transform:scaleX(-1);float:left" alt="Scrum master" title="Scrum master">

---

# Technical debt

* Work to be done at some point
* Increases over time
* May delay new development

<img src="img/technical-debt.svg" height="280" style="border:none;box-shadow:none;background:transparent" alt="Technical debt" title="Technical debt">

Note:

* Similar to a financial debt or a credit.
* Software gets more and more fragile.

---

# Traditional development model

<img src="img/angry.svg" height="200" style="border:none;box-shadow:none;background:transparent" alt="Angry" title="Angry">
