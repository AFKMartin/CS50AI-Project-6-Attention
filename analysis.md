# Analysis

NOTE: Rows = Who's paying attention, Cols = to whom

## Layer 6, Head 10

This attention head shows that adjectives pay attention to the nouns they modify. 
When an adjective appears before a noun, the adjective token strongly attends 
to the noun token.

Example Sentences:
- "She found a black [MASK] outside." - "black" attends to "[MASK]"
- "The [MASK] cat was running fast." - "[MASK]" (adjective position) attends to "cat"

## Layer 4, Head 10

This attention head shows that determiners (articles) pay attention to the nouns 
they precede. Determiners like "the" and "a" attend to the noun that follows them 
in the noun phrase.

Example Sentences:
- "The [MASK] cat was running fast." - "The" attends to "cat"
- "I saw a [MASK] cat the other day walking down the street." - "a" attends to "cat"
