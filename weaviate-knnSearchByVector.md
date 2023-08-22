# Panic in function knnSearchByVector of weaviate.
## Vuln info
Affected Product: weaviate

Affected Version: <=1.19.0
## Vuln details
Vulnerability type: OOB

Root Cause: Negative index leadint to an illegal access.

Ref: https://github.com/weaviate/weaviate/issues/3263
