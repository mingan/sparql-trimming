General SPARQL query for trimming string literals. Intended as a configuration for [UnifiedViews](https://github.com/UnifiedViews/Core)/[ODCS](https://github.com/mff-uk/ODCS) SPARQL Transformer DPU.

Takes into account all whitespace characters as understood by SPARQL on both ends of the string.

In default form it trims all literals, alternative filter by predicate is prepared commented out. Additionl optional filter by subject class is commented out as well. Any other filter can be added as long as variable ?o is bound to the the literal being trimmed. Optional filter by language tag is prepared.