[@redhat-cloud-services/vulnerabilities-client](../README.md) › [Globals](../globals.md) › [MetaCvesAllOf](metacvesallof.md)

# Interface: MetaCvesAllOf

**`export`** 

**`interface`** MetaCvesAllOf

## Hierarchy

* **MetaCvesAllOf**

## Index

### Properties

* [business_risk_id](metacvesallof.md#business_risk_id)
* [cvss_from](metacvesallof.md#cvss_from)
* [cvss_to](metacvesallof.md#cvss_to)
* [impact](metacvesallof.md#impact)
* [patch_access](metacvesallof.md#patch_access)
* [public_from](metacvesallof.md#public_from)
* [public_to](metacvesallof.md#public_to)
* [rule_presence](metacvesallof.md#rule_presence)
* [security_rule](metacvesallof.md#security_rule)
* [status_id](metacvesallof.md#status_id)

## Properties

###  business_risk_id

• **business_risk_id**: *string | null*

*Defined in [packages/vulnerabilities/git-api/api.ts:1020](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L1020)*

Filter based on business risk IDs.

**`memberof`** MetaCvesAllOf

___

###  cvss_from

• **cvss_from**: *number | null*

*Defined in [packages/vulnerabilities/git-api/api.ts:1026](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L1026)*

Filter based on cvss score, starting from the value. Use -1 to include also CVEs with N/A cvss score.

**`memberof`** MetaCvesAllOf

___

###  cvss_to

• **cvss_to**: *number | null*

*Defined in [packages/vulnerabilities/git-api/api.ts:1032](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L1032)*

Filter based on cvss score, up to the value.

**`memberof`** MetaCvesAllOf

___

###  impact

• **impact**: *string | null*

*Defined in [packages/vulnerabilities/git-api/api.ts:1050](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L1050)*

Filter based on impact IDs.

**`memberof`** MetaCvesAllOf

___

###  patch_access

• **patch_access**: *boolean | null*

*Defined in [packages/vulnerabilities/git-api/api.ts:1074](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L1074)*

If show_advisories=true shows access to patch service else null

**`memberof`** MetaCvesAllOf

___

###  public_from

• **public_from**: *string | null*

*Defined in [packages/vulnerabilities/git-api/api.ts:1038](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L1038)*

Filter CVEs based on their published date, starting from the date.

**`memberof`** MetaCvesAllOf

___

###  public_to

• **public_to**: *string | null*

*Defined in [packages/vulnerabilities/git-api/api.ts:1044](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L1044)*

Filter CVEs based on their published date, up to the date.

**`memberof`** MetaCvesAllOf

___

###  rule_presence

• **rule_presence**: *string | null*

*Defined in [packages/vulnerabilities/git-api/api.ts:1062](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L1062)*

Filter based on presence of security rule

**`memberof`** MetaCvesAllOf

___

###  security_rule

• **security_rule**: *boolean | null*

*Defined in [packages/vulnerabilities/git-api/api.ts:1068](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L1068)*

Filter based on presence of security_rule - deprecated

**`memberof`** MetaCvesAllOf

___

###  status_id

• **status_id**: *string | null*

*Defined in [packages/vulnerabilities/git-api/api.ts:1056](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/vulnerabilities/git-api/api.ts#L1056)*

Filer based on CVE status ID.

**`memberof`** MetaCvesAllOf
