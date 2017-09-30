---
title: Contributing
layout: default
---

### The Technical Basis

of the Theorem Prover Museum is provided by [GitHub](http://github.com) the premier web-based GIT repository hosting service. 
The free-for-public hosting service of GitHub allows to provide separate repositories for the respective systems and give the respective authors and maintainers control over them, while promising long-term availability. 
The [Museum web site](http://theoremprover-museum.github.io) is conveniently organized as a [public repository](https://github.com/ via <a href="https://pages.github.com/">GitHub
pages</a>, with all data about systems centralized in a [provers database file ](https://github.com/theoremprover-museum/theoremprover-museum.github.io/blob/master/_data/provers.yml) in [YAML format](https://en.wikipedia.org/wiki/YAML)

We are grateful to [GitHub.com](http://github.com) for their service to the open source community.

### How can you contribute?

* If you want to help with the site admin, the presentation of theorem provers, ... We collect suggestions and plans on the [the issue tracker of the web site repository](https://github.com/theoremprover-museum/theoremprover-museum.github.io/issues). 
* If you have access (and rights) to (the sources of) a system, you can "donate" them to the museum
  1. you give [us](mailto:michael.kohlhase@fau.de) a list of repository names, then I will make them for you unter http://github.com/theoremprover-museum
  1. you give [us](mailto:michael.kohlhase@fau.de) your GitHub account name, and [we](mailto:michael.kohlhase@fau.de) will make you admin to these repositories.
  1. you  fill out the metadata of your provers in the form of [our provers database](https://github.com/theoremprover-museum/theoremprover-museum.github.io/blob/master/_data)
  1. done; that was all.
* If you know about the history of theorem proving just add metadata to [our provers database](https://github.com/theoremprover-museum/theoremprover-museum.github.io/blob/master/_data); make a pull request of send an updated version [via e-mail](mailto:michael.kohlhase@fau.de).
* to request a system, just fill out the following form:

```YAML
- name: <system name>
  authors: <comma-separated list of person names>
  dev-years: <a range of years in the form YYYY-YYYY where it was developed>
  uri: <space-separated list of URIs with information about the system>
  note: <where can I find it, has something happened?>
```	
* if all else fails, please contact [Michael Kohlhase](http://kwarc.info/kohlhase).

### Individual Contributors to the Theorem Prover Museum

The Theorem prover museum is a community effort, the current collection has been made possible by the following individuals: 

* a discussion with **Jaques Fleuriot** and **Alan Smaill** at the University of Edinburgh in February 2016 and their immediate offer to help made Michael's vague idea of a collection of theorem prover sources sufficiently concrete to get him started. 
* **Tom Wiesing** (FAU Erlangen-Nürnberg) has helped with technical support for the setup and maintenance of the web site. 
* **William Farmer** (McMaster University) supplied the first system: [IMPS](http://github.com/theoremprover-museum/imps).
* **Jörg Siekmann** has been immediately supportive of the idea and organized the contribution of the [MKRP (Markgraph Karl Refutation Procedure)](http://github.com/theoremprover-museum/MKRP) and [OMEGA](http://github.com/theoremprover-museum/OMEGA) systems.
*  **Wolfgang Bibel** triggered colleagues and former members of his group to contribute and promised to look for source code of his early systems.
* **Bob Veroff** pointed Michael to the source of [Otter](http://github.com/theoremprover-museum/otter), packaged [Prover9](http://github.com/theoremprover-museum/prover9), and helped make contact to the Argonne people for the early systems.

