---
category: breaking
---
* Deleted the deprecated `explorationLimit` predicate from `DataFlow::Configuration`, use `FlowExploration<explorationLimit>` instead.
* Deleted the deprecated `getDerivedTypeDecl` predicate from the `TypeDecl` class, use `getADerivedTypeDecl` or `getABaseTypeDecl` instead.