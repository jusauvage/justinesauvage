---
title: Games and Logic for the Verification of Cryptographic Protocols

event: Phd defence
event_url: 

location: Inria Paris
address: 
  street: 48 Rue Barrault
  city: Paris
  region: 
  postcode: 75013
  country: France

summary: PhD defence 

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2026-01-21T14:00:00Z'
#date_end: '2026-01-21'
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2024-01-10'

authors:
  - admin

tags: []

# Is this a featured talk? (true/false)
featured: true

#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#  focal_point: Right

#links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
#url_code: 'https://github.com'
#url_pdf: ''
#url_slides: 'https://slideshare.net'
#url_video: 'https://youtube.com'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects:
#  - example
---

{{% callout note %}}
The **Slides** will be available afterward
{{% /callout %}}


## Manuscript

The manuscript dan be downloaded here:
<a href="./these.pdf" download>Thesis manuscript</a>

## Video conference link

[Visio](https://rendez-vous.renater.fr/sf13c-ssows-zsx3g)

## Jury

- Ioana Boureanu *Professor, University of Surrey* (Rapportrice)
- Steve Kremer *Directeur de recherche, INRIA* (Rapporteur)
- Gilles Barthe *Scientific director, MPI SP* (Examinateur)
- David Monniaux *Directeur de recherche, CNRS* (Examinateur)
- Sabine Oechsner *Assistant Professor, Vrije Universiteit Amsterdam* (Examinatrice)
- François Pottier *Directeur de recherche, INRIA* (Examinateur)
- Bruno Blanchet *Directeur de recherche, INRIA* (Directeur de thèse)
- Adrien Koutsos *Chargé de recherche, INRIA* (Co-Directeur de thèse)
- David Baelde *Professeur, ENS Rennes* (Invité)


## Abstract

This thesis investigates cryptographic protocol verification in the CCSA framework, a
formal verification approach based on a probabilistic logic for proving security properties in
the computational model. This framework is implemented in the Squirrel proof assistant.
The main focus of the thesis is the mechanization of cryptographic reductions — a core
proof technique in cryptography in which the security of a protocol is reduced to a
cryptographic hardness assumption via the construction of a simulator.
Prior to this thesis, the CCSA framework provided logical axioms whose soundness was
established through manual, error-prone reductions to a fixed set of cryptographic hardness
assumption (e.g., CCA, PRF, EUF-MAC). Each axiom also necessitated implementation
efforts, which were prone to errors. Unfortunately, these tasks (designing, proving, and
implementing the axioms) were inaccessible to typical users, thus limiting the scalability
of the CCSA approach.
The main contribution of this thesis is a framework that captures reductions to
arbitrary cryptographic games for the CCSA framework. We introduce a logic with a core
predicate, the bideduction predicate, which express the existence of a simulator justifying
a cryptographic reduction. We then provide a proof system to derive such predicates,
implicitly inferring simulators. We further implement in Squirrel a proof search procedure
that synthesize memoizing simulators and generates time-sensitive invariants to justify the
inferred simulator’s correctness. Our implementation significantly extends Squirrel’s
scope as it extends the set of supported cryptographic hardness assumptions. To validate
our approach, we apply it to case studies, reproving existing Squirrel case studies and
analysing new ones which were not provable in Squirrel before. This work culminates
with the first mechanized proof of ballot privacy for the FOO e-voting protocol — the
largest proof conducted in Squirrel to date.

## Résumé
Cette thèse étudie la vérification des protocoles cryptographiques dans le cadre CCSA,
une approche de vérification formelle basée sur une logique probabiliste pour prouver les
propriétés de sécurité dans le modèle computationnel. Cette approche est implémentée dans
l’assistant de preuve Squirrel. Cette thèse s’intéresse à la mécanisation des réductions
cryptographiques, une technique de preuve centrale en cryptographie où la sécurité d’un
protocole est réduite à une hypothèse calculatoire cryptographique par la construction
d’un simulateur.
Avant cette thèse, le cadre CCSA fournissait des axiomes logiques dont la validité était
établie manuellement par des réductions. Ces réductions sont une source possible d’erreurs
et les axiomes logiques n’avait été conçus seulement pour un nombre restreint d’hypothèses
calculatoires (par exemple, CCA, PRF, EUF-MAC). Chaque axiome nécessitait également
un effort d’implémentation, lui aussi source d’erreurs. Malheureusement, ces tâches
(conception, preuve et implémentation des axiomes) étaient inaccessibles aux utilisateurs
typiques, limitant ainsi la capacité de l’approche CCSA à passer à l’échelle.
La contribution majeure de cette thèse est une approche permettant de capturer des
réductions vers des jeux cryptographiques arbitraires dans le cadre de la logique CCSA.
Nous introduisons une logique dont le prédicat central, le prédicat de bidéduction, formalise
l’existence d’un simulateur justifiant une réduction cryptographique. Nous proposons
ensuite un système de preuve pour dériver ces prédicats, qui infère implicitement les
simulateurs. Nous avons en outre implémenté dans Squirrel une procédure de recherche
de preuve qui synthétise des simulateurs qui mémoïsent et génèrent des invariants sensibles
au temps pour justifier la correction des simulateurs inférés. Notre implémentation
élargit significativement la portée des preuves dans Squirrel, en étendant l’ensemble
des hypothèses calculatoires cryptographiques supportées. Pour valider notre approche,
nous l’avons appliquée à des études de cas, en reproduisant des preuves existantes dans
Squirrel et en traitant de nouveaux cas qui n’étaient pas prouvables auparavant. Ce
travail culmine avec la première preuve mécanisée de la confidentialité des votes pour
le protocole de vote électronique FOO — la plus grande preuve réalisée à ce jour dans
Squirrel.



