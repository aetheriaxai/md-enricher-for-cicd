<!--
# Copyright 2022, 2023 IBM Inc. All rights reserved
# SPDX-License-Identifier: Apache2.0
# Last updated: 2023-06-01
-->

# Feature flag file example


```
[{
    "name": "new-feature",
    "location": "staging"
},
{
    "name": "old-feature",
    "location": "prod"
},
{
    "name": "unchanged-feature",
    "location": "all"
},
{
    "name": "another-unchanged-feature",
    "location": "staging,prod"
}]
```

