# Thistle

Thistle is a Scala library that provides an easy way to create custom DSLs for finding patterns in arbitrary collections, but is particularly suited for funnel analysis.

Thistle allows you to build libraries of boolean predicates which can be combined to create queries. Given a collection, Thistle find all partial and full matches, allowing you to easily capture fallout between steps. Predicates and their resulting matches have access to the entire underlying collection, which makes it easy to utilize lookahead logic allowing for simple, yet powerful queries. 
