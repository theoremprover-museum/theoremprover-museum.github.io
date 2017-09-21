---
title: Most Wanted List
layout: jumbo
---

# The Most Wanted List for the Theorem Prover Museum

The following theorem provers are not featured in the <a href="/">Theorem Prover Museum</a> but are important cultural artifacts. 
We list the system and known associates here. 
There is also a list of <a href="systems-believed-lost.html">systems believed lost</a>.


Note that the Theorem Prover Museum wants to preserve the (stable) source code of theorem proving systems that are no longer under active development. 
Active systems typically have repositories of their own. 
We <a href="active-tp.html">list them separately</a>.

If you know the last authors/maintainers and please contact them and ask them to contribute the sources. 
To contribute source code or suggest a system for inclusion, please contact <a href="mailto:m.kohlhase@jacobs-university.de">Michael Kohlhase</a>. 
Alternatively, just open <a href="https://github.com/theoremprover-museum/theoremprover-museum.github.io/issues/">an issue on our tracker</a>.

**Acknowledgements**: Thanks to the following colleagues for suggestions: 
Alan Bundy, Josef Urban, Jacques Fleuriot, Cezar Munoz, Freek Wiedijk, Jörg Siekmann, Georges Gonthier, Florian Rabe, Larry Paulson, Konrad Slind, David Plaisted, Matt Kaufmann, John Harrison, Mike Gordon.


We list theorem proving systems and their known associates (for contact) and state

<ol>
{% for item in site.data.wanted %}
  <li>{{item}}</li>
{% endfor %}
</ol>