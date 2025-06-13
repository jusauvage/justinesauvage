---
title: 'Foundations for Cryptographic Reductions in CCSA Logics'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - David Baelde
  - Adrien Koutsos
  - admin

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

date: '2024-01-01T00:00:00Z'
doi: '10.1145/3658644.3690193'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Conference on Computer and Communications Security*
publication_short: In *CCS*

abstract: The Computationally Complete Symbolic Attacker (CCSA) approach to security protocol verification relies on probabilistic logics to reason about the interaction traces between a protocol and an arbitrary adversary. The proof assistant Squirrel implements one such logic. CCSA logics come with cryptographic axioms whose soundness derives from the security of standard cryptographic games, e.g. PRF, EUF, IND-CCA. Unfortunately, these axioms are complex to design and implement; so far, these tasks are manual, ad-hoc and error-prone. We solve these issues by providing a formal and systematic method for deriving axioms from cryptographic games. Our method relies on synthesizing an adversary against some cryptographic game, through the notion of bi-deduction. Concretely, we define a rich notion of bi-deduction, justify how to use it to derive cryptographic axioms, provide a proof system for bi-deduction, and an automatic proof-search method which we implemented in Squirrel.


tags:
  - Formal methods
  - Protocols
  - Computational model

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://hal.science/hal-04511718'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''




---

