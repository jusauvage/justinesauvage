---
title: 'Leveraging Cryptographic Simulator Synthesis for Formally Verifying the FOO E-Voting Protocol'

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

date: '2026-08-01T00:00:00Z'
#doi: '10.1145/3658644.3690193'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-03-26T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *Usenix 2026 - 35th Usenix security symposium*
publication_short: In *Usenix'26*

abstract: Cryptographic proofs proceed in large part by reductions to cryptographic assumptions expressed as games. These reductions rely on simulators which are often tedious to write and involve a significant amount of trivial code. Thus, simulators are only sketched in pen-and-paper proofs, which is error-prone. Mechanized cryptographic proofs remove the risk of errors, but requiring users to explicitly write simulators is an unreasonable burden. In this paper, we consider the problem of simulator synthesis in Squirrel, where cryptographic simulation is expressed as bi-deduction. Although the seminal work on bi-deduction provides a proof system and a simple proof-search procedure for it, we show that it suffers from systematic failures when working with games such as IND-CCA2. We provide a significantly improved procedure, that can re-use oracle calls across recursive iterations, and generates precise invariants to justify it. We implement this procedure in Squirrel and validate it in a proof of ballot privacy for the FOO e-voting protocol, which is the first computational mechanized proof for FOO, and the most complex Squirrel proof to date. 


tags:
  - Formal methods
  - Protocols
  - Proof mechanization
  - Computational model

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://inria.hal.science/hal-05453231'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''




---

