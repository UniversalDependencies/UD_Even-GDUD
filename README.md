# Summary

UD_Even-GDUD is a treebank of Even (also called Lamut), a Northern Tungusic language spoken in northeastern Siberia, based on grammatical example sentences derived from a reference grammar.

# Introduction

The Even GDUD (Grammar-Derived Universal Dependencies) treebank contains 39 sentences of Even (ISO 639-3: eve), a Northern Tungusic language spoken by the Even people in eastern Siberia (Russia). The data consist of grammatical example sentences drawn from a reference grammar of Even, presented with a phonemic Latin-based transcription and accompanied by English translations and interlinear glosses.

All sentences are manually annotated with lemmas, universal part-of-speech tags (UPOS), morphological features, and dependency relations, following the Universal Dependencies (UD) guidelines. The annotation prioritizes UD core morphological features and dependency relations. Even-specific morphological information that does not correspond to any value in the universal feature inventory (such as certain derivational categories, particle types, and specialized converb, voice, and mood distinctions) is encoded in the MISC column, in accordance with UD conventions.

## Data split

Because the treebank is small (well below the 20K-word threshold), all sentences are provided as test data.

## Morphological annotation

All UD core features used in the treebank take standard universal values. The following Even-specific morphological information is encoded in the MISC column rather than FEATS: `AdvType`, `Attr`, `Aspect=Ant/Purp/Res`, `Case=Priv`, `ConvType`, `Degree=Int/Tot`, `Derivation`, `Discourse`, `Focus`, `PartType=Disc/Foc/Onom/Prt`, `Tense=NonPast`, `VerbForm=Excl`, and `Voice=Detrans/Mult/Res`.

The copula `bi` (existential 'to be') is analyzed as an auxiliary (AUX).

## Dependency annotation

UD core relations are used throughout the treebank. The `nsubj:outer` subtype is used where a clause acts as the predicate of another clause.

# Acknowledgments

The Even GDUD treebank was created by Wenchao Li and Haitao Liu, based on grammatical example sentences from a reference grammar of Even. The annotation of lemmas, part-of-speech tags, morphological features, and dependency relations was carried out manually following the Universal Dependencies guidelines.

We thank Daniel Zeman for his guidance in setting up the treebank repository and for his help with the Universal Dependencies workflow, and the Universal Dependencies community for their support.

# Changelog

* 2026-08-23 v2.19
  * Initial release in Universal Dependencies.

<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.19
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: grammar-examples
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Li, Wenchao; Liu, Haitao
Contributing: here
Contact: widelia@zju.edu.cn
===============================================================================
</pre>
