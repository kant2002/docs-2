---
layout: base
title:  'Statistics of Emph in UD_French-GSD'
udver: '2'
---

## Treebank Statistics: UD_French-GSD: Features: `Emph`

This feature is language-specific.
It occurs with 2 different values: `No`, `Yes`.

10206 tokens (3%) have a non-empty value of `Emph`.
77 types (0%) occur at least once with a non-empty value of `Emph`.
15 lemmas (0%) occur at least once with a non-empty value of `Emph`.
The feature is used with 1 part-of-speech tags: <tt><a href="fr_gsd-pos-PRON.html">PRON</a></tt> (10206; 3% instances).

### `PRON`

10206 <tt><a href="fr_gsd-pos-PRON.html">PRON</a></tt> tokens (56% of all `PRON` tokens) have a non-empty value of `Emph`.

The most frequent other feature values with which `PRON` and `Emph` co-occurred: <tt><a href="fr_gsd-feat-PronType.html">PronType</a></tt><tt>=Prs</tt> (9667; 95%), <tt><a href="fr_gsd-feat-Reflex.html">Reflex</a></tt><tt>=EMPTY</tt> (9427; 92%), <tt><a href="fr_gsd-feat-Person.html">Person</a></tt><tt>=3</tt> (8764; 86%), <tt><a href="fr_gsd-feat-Number.html">Number</a></tt><tt>=Sing</tt> (7134; 70%), <tt><a href="fr_gsd-feat-Gender.html">Gender</a></tt><tt>=Masc</tt> (5632; 55%).

`PRON` tokens may have the following values of `Emph`:

* `No` (9773; 96% of non-empty `Emph`): <em>il, elle, on, y, ils, se, nous, je, le, en</em>
* `Yes` (433; 4% of non-empty `Emph`): <em>lui, eux, lui-même, elle, moi, elle-même, elles, eux-mêmes, soi, toi</em>

<table>
  <tr><th>Paradigm <i>lui</i></th><th><tt>No</tt></th><th><tt>Yes</tt></th></tr>
  <tr><td><tt><tt><a href="fr_gsd-feat-Gender.html">Gender</a></tt><tt>=Masc</tt></tt></td><td><em>il, le, lui, -t-il, -il</em></td><td><em>lui</em></td></tr>
  <tr><td><tt><tt><a href="fr_gsd-feat-Gender.html">Gender</a></tt><tt>=Masc</tt>|<tt><a href="fr_gsd-feat-Typo.html">Typo</a></tt><tt>=Yes</tt></tt></td><td><em>il, t-il, -il, -le, t'il</em></td><td></td></tr>
  <tr><td><tt><tt><a href="fr_gsd-feat-Gender.html">Gender</a></tt><tt>=Fem</tt></tt></td><td><em>elle, la, -elle, -t-elle</em></td><td><em>elle</em></td></tr>
  <tr><td><tt><tt><a href="fr_gsd-feat-Gender.html">Gender</a></tt><tt>=Fem</tt>|<tt><a href="fr_gsd-feat-Typo.html">Typo</a></tt><tt>=Yes</tt></tt></td><td><em>elle</em></td><td></td></tr>
  <tr><td><tt></tt></td><td><em>l'</em></td><td></td></tr>
</table>

## Relations with Agreement in `Emph`

The 10 most frequent relations where parent and child node agree in `Emph`:
<tt>PRON --[<tt><a href="fr_gsd-dep-fixed.html">fixed</a></tt>]--> PRON</tt> (19; 95%),
<tt>PRON --[<tt><a href="fr_gsd-dep-conj.html">conj</a></tt>]--> PRON</tt> (2; 67%),
<tt>PRON --[<tt><a href="fr_gsd-dep-reparandum.html">reparandum</a></tt>]--> PRON</tt> (2; 100%).

