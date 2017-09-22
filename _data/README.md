The data files of the Theorem Prover Museum. They are used to generate the web pages of the musuem

Some of them (in particuylar the first two) should probably obtain more struture. 

### A list of lost theorem provers
`lost.yml` is a bulleted list of notes that feeds into the list of  [systems believed lost](/lost/).

### A list of most wanted  theorem provers
`wanted.yml` is a bulleted list of notes making the case for a particular theorem prover, and the actions taken. It feeds the  [most wanted list](/wanted/).

### The Theorem Provers Data Base
`provers.yml` is a structured list of theorem provers. For each theorem prover we collect the following metadata 
* `name` the name of the system
* `active` is it currently active, if yes, then it is listed in the [active provers page](/active/) else in the [main museum index](/)
* `teaser` a one-line teaser for the listing 
* `repos` the URI of the source code repository (we need this for listing). This is usually in the `theoremprover-museum` organization, but can also be external. If it is a repository outside of GitHub, we maintain our own fork and keep it up to date.  
* `swmath` the URI where the system can be found on the [swMATH](http://swmath.org) information  system.

More metadata is to come [discussion](https://github.com/theoremprover-museum/theoremprover-museum.github.io/issues/11).


