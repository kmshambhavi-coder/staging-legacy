# New Playbook
test



**Enabled:** True

**Version:** 0

**Type:** Playbook

**Priority:** 2

**Playbook Simulator:** False



### Playbook Trigger
**Trigger Type:** All

**Conditions Operator:** And

##### Conditions
|Key|Operator|Value|
|---|--------|-----|
||Equals||



### Involved Steps (Unordered)
|Step Name|Description|Integration|Original Action|
|---------|-----------|-----------|---------------|
|Siemplify_Change Alert Priority_1|Automatically change the alert priority to the given input. Note: This action is compatible only with Siemplify version 5.6 and higher.|Siemplify|Change Alert Priority|
|Siemplify_Case Comment_1|Add a comment to the case the current alert has been grouped to|Siemplify|Case Comment|
|Siemplify_Case Tag_1|Add given tag to the case the current alert is grouped to|Siemplify|Case Tag|

### Involved Blocks
|Name|Description|
|----|-----------|
|New Block|An embedded workflow that can receive inputs and return an output.|
Test Playbook readme addons