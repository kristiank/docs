---
layout: relation
title: 'aux'
shortdef: 'auxiliary'
# The filename "aux" is not allowed on Windows, so we redirect instead
# (see https://github.com/UniversalDependencies/docs/issues/20)
redirect_from: "hy/dep/aux.html"
udver: '2'
---

An auxiliary of a clause is a form of the [auxiliary verbs](AUX) _եմ_ “be”, and its variants (with separate lemma) _լինեմ (լինել)_ “be repeatedly / habitually” used to construct the periphrastic or the “secondary extended” tenses (in any mood).

Note that in Armenian auxiliary verb _տալ_ used to construct the causative [voice](Voice) is labeled [aux:cau]().

Note that besides `aux`, the verbs _եմ_ and _լինեմ (լինել)_ may also act as a [copula](cop)
and as the main verb.

~~~ sdparse
Երեկ եմ հասել ։ \n Yesterday I-have arrived .
aux(հասել, եմ)
aux(arrived, I-have)
~~~

~~~ sdparse
Կարծում ես նա գնացած կլինի ՞ , երբ տեղ հասնենք ։ \n You-are think he will-have gone , when we-arrive ?
aux(Կարծում, ես)
aux(think, You-are)
aux(գնացած, կլինի)
aux(gone, will-have)
~~~
