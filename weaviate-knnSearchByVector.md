# Panic in function knnSearchByVector of weaviate.
## Vuln info
Affected Product: weaviate

Affected Version: <=1.20.2
## Vuln details
Vulnerability type: OOB

Root Cause: Negative index leadint to an illegal access.

Ref:
https://github.com/weaviate/weaviate/issues/3263

https://github.com/weaviate/weaviate/pull/3288/files#diff-93fc30537573a9ae6899217ecd21ead17735efce271bf8a864dfc8a394599622

