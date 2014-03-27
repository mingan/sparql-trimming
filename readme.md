General SPARQL query for trimming string literals. Intended as a configuration for [UnifiedViews](https://github.com/UnifiedViews/Core)/[ODCS](https://github.com/mff-uk/ODCS) SPARQL Transformer DPU.

Takes into account all whitespace characters as understood by SPARQL on both ends of the string.

In default form it trims all literals, optional filter by predicate is prepared and commented out. Filters by subject class and langauge tag are commented out as well. Any other filter can be added as long as variable ?o is bound to the the literal being trimmed. If you modify the graph pattern, make sure you DELETE the correct triple.