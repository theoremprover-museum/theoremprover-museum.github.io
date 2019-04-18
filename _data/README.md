# The Data Files of the Theorem Prover Museum

The data files of the Theorem Prover Museum. They are used to generate the web pages of
the museum. To contribute, please
[make a pull request](https://help.github.com/articles/using-pull-requests), for instance
by directly editing [`provers.yml`](provers.yml) and then choosing "create a new branch
..." at the bottom.

### The Theorem Provers Data Base
`provers.yml` is a structured list of theorem provers. For each theorem prover we collect
the following metadata.  First the mandatory fields:

* `name`: the name of the system
* `active`: is it currently active, if yes, then it is listed in the [active provers page](/active/) else in the [main museum index](/)
* `status`: currently one of `museum` (in the museum), `wanted`, and `believed-lost`. Together with  `active` this is used to generate the various lists.

And now the optional fields that can be used to describe the systems.

* `teaser`: a one-line teaser for the listing 
* `homepage`: the system home page (if one still exists).
* `authors`:  the (main) authors of the system.
* `maintainers`: the (key) maintainers of the system that are not mentioned under `authors`
* `TPMarchive`: name of the Theorm Prover Museum archive, i.e. a repository under
  <https://github.com/theoremprover-museum>. For active sytems, there can also be a code repository: 
* `repos`: a comma-separated list of URIs of active source code repositories for this system. 
* `swmath`: the URI where the system can be found on the [swMATH](http://swmath.org) information  system.
* `wikipedia`: the wikipedia page
* `development`: the years of development (format: `yyyy-yyyy`). 
* `language`: the main programming languages. 
* `license`: the license(s) of the code 
* `note`: a (short) note with anything you want to s

To contribute, just complete the following YML snippet and contribute it (`status` will be
filled out by us).
```
- name: 
  active: 
  teaser: 
  homepage: 
  authors:
  maintainers:
  repos:
  swmath: 
  wikipedia: 
  development:
  language:
  license: 
  note: 
```
More metadata is to come
([discussion](https://github.com/theoremprover-museum/theoremprover-museum.github.io/issues/11)). If
  you are missing a slot for information you have, please suggest it there. 

