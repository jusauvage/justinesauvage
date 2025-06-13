---
title: "Termination of Ethereum's Smart Contracts"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Thomas Genet
  - Thomas P. Jensen
  - admin


date: '2020'
doi: '10.5220/0009564100390051'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *ScitePress*
publication_short: In *ScitePress*

abstract:  Ethereum is a decentralized blockchain technology equipped with so-called Smart Contracts. A contract is a program whose code is public, which can be triggered by any user, and whose actual execution is performed by miners participating in Ethereum. Miners execute the contract on the Ethereum Virtual Machine (EVM) and apply its effect by adding new blocks to the blockchain. A contract that takes too much time to be processed by the miners of the network may result into delays or a denial of service in the Ethereum system. To prevent this scenario, termination of Ethereum’s Smart Contracts is ensured using a gas mechanism. Roughly, the EVM consumes gas to process each instruction of a contract and the gas provided to run a contract is limited. This technique could make termination of contracts easy to prove but the way the official definition of the EVM specifies gas usage makes the proof of this property non-trivial. EVM implementations and formal analysis techniques of EVM’s Smart C ontracts use termination of contracts as an assumption, so having a formal proof of termination of contracts is crucial. This paper presents a mechanized, formal, and general proof of termination of Smart Contracts based on a measure of EVM call stacks.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Formal Methods for Security
  - Ethereum
  - Smart Contrats
  - Security in Distributed Systems

# Display this page in the Featured widget?
featured: false



url_pdf: 'https://hal.science/hal-02555738v3'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ''
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#xsslides: example
---


