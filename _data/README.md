The data files of the Theorem Prover Museum. They are used to generate the web pages of the museum

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
* `repos`: the URI of the source code repository (we need this for listing). This is usually in the `theoremprover-museum` organization, but can also be external. If it is a repository outside of GitHub, we maintain our own fork and keep it up to date.  
* `swmath`: the URI where the system can be found on the [swMATH](http://swmath.org) information  system.
* `wikipedia`: the wikipedia page
* `development`: the years of development (format: `yyyy-yyyy`). 
* `language`: the main programming languages. 
* `license`: the license(s) of the code 
* `note`: a (short) note with anything you want to s

More metadata is to come ([discussion](https://github.com/theoremprover-museum/theoremprover-museum.github.io/issues/11)).
