[@redhat-cloud-services/insights-client](README.md) › [Globals](globals.md)

# @redhat-cloud-services/insights-client

## Index

### Classes

* [AccountSettingApi](classes/accountsettingapi.md)
* [BaseAPI](classes/baseapi.md)
* [Configuration](classes/configuration.md)
* [KcsApi](classes/kcsapi.md)
* [RequiredError](classes/requirederror.md)
* [ResolutionRiskApi](classes/resolutionriskapi.md)
* [RulecategoryApi](classes/rulecategoryapi.md)
* [SettingsApi](classes/settingsapi.md)
* [StatusApi](classes/statusapi.md)
* [SystemtypeApi](classes/systemtypeapi.md)
* [TotalRiskApi](classes/totalriskapi.md)

### Interfaces

* [ConfigurationParameters](interfaces/configurationparameters.md)
* [Kcs](interfaces/kcs.md)
* [RequestArgs](interfaces/requestargs.md)
* [RuleCategory](interfaces/rulecategory.md)
* [SettingDDF](interfaces/settingddf.md)
* [SettingsDDF](interfaces/settingsddf.md)
* [StatusReady](interfaces/statusready.md)
* [SystemType](interfaces/systemtype.md)

### Variables

* [BASE_PATH](globals.md#const-base_path)

### Functions

* [AccountSettingApiAxiosParamCreator](globals.md#const-accountsettingapiaxiosparamcreator)
* [AccountSettingApiFactory](globals.md#const-accountsettingapifactory)
* [AccountSettingApiFp](globals.md#const-accountsettingapifp)
* [KcsApiAxiosParamCreator](globals.md#const-kcsapiaxiosparamcreator)
* [KcsApiFactory](globals.md#const-kcsapifactory)
* [KcsApiFp](globals.md#const-kcsapifp)
* [ResolutionRiskApiAxiosParamCreator](globals.md#const-resolutionriskapiaxiosparamcreator)
* [ResolutionRiskApiFactory](globals.md#const-resolutionriskapifactory)
* [ResolutionRiskApiFp](globals.md#const-resolutionriskapifp)
* [RulecategoryApiAxiosParamCreator](globals.md#const-rulecategoryapiaxiosparamcreator)
* [RulecategoryApiFactory](globals.md#const-rulecategoryapifactory)
* [RulecategoryApiFp](globals.md#const-rulecategoryapifp)
* [SettingsApiAxiosParamCreator](globals.md#const-settingsapiaxiosparamcreator)
* [SettingsApiFactory](globals.md#const-settingsapifactory)
* [SettingsApiFp](globals.md#const-settingsapifp)
* [StatusApiAxiosParamCreator](globals.md#const-statusapiaxiosparamcreator)
* [StatusApiFactory](globals.md#const-statusapifactory)
* [StatusApiFp](globals.md#const-statusapifp)
* [SystemtypeApiAxiosParamCreator](globals.md#const-systemtypeapiaxiosparamcreator)
* [SystemtypeApiFactory](globals.md#const-systemtypeapifactory)
* [SystemtypeApiFp](globals.md#const-systemtypeapifp)
* [TotalRiskApiAxiosParamCreator](globals.md#const-totalriskapiaxiosparamcreator)
* [TotalRiskApiFactory](globals.md#const-totalriskapifactory)
* [TotalRiskApiFp](globals.md#const-totalriskapifp)

### Object literals

* [COLLECTION_FORMATS](globals.md#const-collection_formats)

## Variables

### `Const` BASE_PATH

• **BASE_PATH**: *string* = "https://cloud.redhat.com/api/insights/v1".replace(/\/+$/, "")

*Defined in [packages/insights/base.ts:20](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/base.ts#L20)*

## Functions

### `Const` AccountSettingApiAxiosParamCreator

▸ **AccountSettingApiAxiosParamCreator**(`configuration?`: [Configuration](classes/configuration.md)): *object*

*Defined in [packages/insights/api.ts:189](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L189)*

AccountSettingApi - axios parameter creator

**`export`** 

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |

**Returns:** *object*

* **accountSettingList**(`options`: any): *Promise‹[RequestArgs](interfaces/requestargs.md)›*

___

### `Const` AccountSettingApiFactory

▸ **AccountSettingApiFactory**(`configuration?`: [Configuration](classes/configuration.md), `basePath?`: string, `axios?`: AxiosInstance): *object*

*Defined in [packages/insights/api.ts:250](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L250)*

AccountSettingApi - factory interface

**`export`** 

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |
`basePath?` | string |
`axios?` | AxiosInstance |

**Returns:** *object*

* **accountSettingList**(`options?`: any): *AxiosPromise‹void›*

___

### `Const` AccountSettingApiFp

▸ **AccountSettingApiFp**(`configuration?`: [Configuration](classes/configuration.md)): *object*

*Defined in [packages/insights/api.ts:228](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L228)*

AccountSettingApi - functional programming interface

**`export`** 

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |

**Returns:** *object*

* **accountSettingList**(`options?`: any): *Promise‹function›*

___

### `Const` KcsApiAxiosParamCreator

▸ **KcsApiAxiosParamCreator**(`configuration?`: [Configuration](classes/configuration.md)): *object*

*Defined in [packages/insights/api.ts:289](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L289)*

KcsApi - axios parameter creator

**`export`** 

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |

**Returns:** *object*

* **kcsList**(`nodeIds?`: Array‹string›, `options`: any): *Promise‹[RequestArgs](interfaces/requestargs.md)›*

* **kcsRead**(`nodeId`: string, `options`: any): *Promise‹[RequestArgs](interfaces/requestargs.md)›*

___

### `Const` KcsApiFactory

▸ **KcsApiFactory**(`configuration?`: [Configuration](classes/configuration.md), `basePath?`: string, `axios?`: AxiosInstance): *object*

*Defined in [packages/insights/api.ts:406](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L406)*

KcsApi - factory interface

**`export`** 

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |
`basePath?` | string |
`axios?` | AxiosInstance |

**Returns:** *object*

* **kcsList**(`nodeIds?`: Array‹string›, `options?`: any): *AxiosPromise‹Array‹[Kcs](interfaces/kcs.md)››*

* **kcsRead**(`nodeId`: string, `options?`: any): *AxiosPromise‹Array‹string››*

___

### `Const` KcsApiFp

▸ **KcsApiFp**(`configuration?`: [Configuration](classes/configuration.md)): *object*

*Defined in [packages/insights/api.ts:369](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L369)*

KcsApi - functional programming interface

**`export`** 

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |

**Returns:** *object*

* **kcsList**(`nodeIds?`: Array‹string›, `options?`: any): *Promise‹function›*

* **kcsRead**(`nodeId`: string, `options?`: any): *Promise‹function›*

___

### `Const` ResolutionRiskApiAxiosParamCreator

▸ **ResolutionRiskApiAxiosParamCreator**(`configuration?`: [Configuration](classes/configuration.md)): *object*

*Defined in [packages/insights/api.ts:469](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L469)*

ResolutionRiskApi - axios parameter creator

**`export`** 

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |

**Returns:** *object*

* **resolutionRiskList**(`options`: any): *Promise‹[RequestArgs](interfaces/requestargs.md)›*

___

### `Const` ResolutionRiskApiFactory

▸ **ResolutionRiskApiFactory**(`configuration?`: [Configuration](classes/configuration.md), `basePath?`: string, `axios?`: AxiosInstance): *object*

*Defined in [packages/insights/api.ts:530](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L530)*

ResolutionRiskApi - factory interface

**`export`** 

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |
`basePath?` | string |
`axios?` | AxiosInstance |

**Returns:** *object*

* **resolutionRiskList**(`options?`: any): *AxiosPromise‹void›*

___

### `Const` ResolutionRiskApiFp

▸ **ResolutionRiskApiFp**(`configuration?`: [Configuration](classes/configuration.md)): *object*

*Defined in [packages/insights/api.ts:508](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L508)*

ResolutionRiskApi - functional programming interface

**`export`** 

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |

**Returns:** *object*

* **resolutionRiskList**(`options?`: any): *Promise‹function›*

___

### `Const` RulecategoryApiAxiosParamCreator

▸ **RulecategoryApiAxiosParamCreator**(`configuration?`: [Configuration](classes/configuration.md)): *object*

*Defined in [packages/insights/api.ts:569](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L569)*

RulecategoryApi - axios parameter creator

**`export`** 

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |

**Returns:** *object*

* **rulecategoryList**(`options`: any): *Promise‹[RequestArgs](interfaces/requestargs.md)›*

* **rulecategoryRead**(`id`: number, `options`: any): *Promise‹[RequestArgs](interfaces/requestargs.md)›*

___

### `Const` RulecategoryApiFactory

▸ **RulecategoryApiFactory**(`configuration?`: [Configuration](classes/configuration.md), `basePath?`: string, `axios?`: AxiosInstance): *object*

*Defined in [packages/insights/api.ts:680](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L680)*

RulecategoryApi - factory interface

**`export`** 

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |
`basePath?` | string |
`axios?` | AxiosInstance |

**Returns:** *object*

* **rulecategoryList**(`options?`: any): *AxiosPromise‹Array‹[RuleCategory](interfaces/rulecategory.md)››*

* **rulecategoryRead**(`id`: number, `options?`: any): *AxiosPromise‹[RuleCategory](interfaces/rulecategory.md)›*

___

### `Const` RulecategoryApiFp

▸ **RulecategoryApiFp**(`configuration?`: [Configuration](classes/configuration.md)): *object*

*Defined in [packages/insights/api.ts:644](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L644)*

RulecategoryApi - functional programming interface

**`export`** 

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |

**Returns:** *object*

* **rulecategoryList**(`options?`: any): *Promise‹function›*

* **rulecategoryRead**(`id`: number, `options?`: any): *Promise‹function›*

___

### `Const` SettingsApiAxiosParamCreator

▸ **SettingsApiAxiosParamCreator**(`configuration?`: [Configuration](classes/configuration.md)): *object*

*Defined in [packages/insights/api.ts:741](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L741)*

SettingsApi - axios parameter creator

**`export`** 

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |

**Returns:** *object*

* **settingsList**(`options`: any): *Promise‹[RequestArgs](interfaces/requestargs.md)›*

___

### `Const` SettingsApiFactory

▸ **SettingsApiFactory**(`configuration?`: [Configuration](classes/configuration.md), `basePath?`: string, `axios?`: AxiosInstance): *object*

*Defined in [packages/insights/api.ts:802](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L802)*

SettingsApi - factory interface

**`export`** 

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |
`basePath?` | string |
`axios?` | AxiosInstance |

**Returns:** *object*

* **settingsList**(`options?`: any): *AxiosPromise‹Array‹[SettingsDDF](interfaces/settingsddf.md)››*

___

### `Const` SettingsApiFp

▸ **SettingsApiFp**(`configuration?`: [Configuration](classes/configuration.md)): *object*

*Defined in [packages/insights/api.ts:780](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L780)*

SettingsApi - functional programming interface

**`export`** 

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |

**Returns:** *object*

* **settingsList**(`options?`: any): *Promise‹function›*

___

### `Const` StatusApiAxiosParamCreator

▸ **StatusApiAxiosParamCreator**(`configuration?`: [Configuration](classes/configuration.md)): *object*

*Defined in [packages/insights/api.ts:841](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L841)*

StatusApi - axios parameter creator

**`export`** 

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |

**Returns:** *object*

* **statusList**(`options`: any): *Promise‹[RequestArgs](interfaces/requestargs.md)›*

* **statusLiveRead**(`options`: any): *Promise‹[RequestArgs](interfaces/requestargs.md)›*

* **statusReadyRead**(`options`: any): *Promise‹[RequestArgs](interfaces/requestargs.md)›*

___

### `Const` StatusApiFactory

▸ **StatusApiFactory**(`configuration?`: [Configuration](classes/configuration.md), `basePath?`: string, `axios?`: AxiosInstance): *object*

*Defined in [packages/insights/api.ts:988](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L988)*

StatusApi - factory interface

**`export`** 

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |
`basePath?` | string |
`axios?` | AxiosInstance |

**Returns:** *object*

* **statusList**(`options?`: any): *AxiosPromise‹void›*

* **statusLiveRead**(`options?`: any): *AxiosPromise‹[StatusReady](interfaces/statusready.md)›*

* **statusReadyRead**(`options?`: any): *AxiosPromise‹[StatusReady](interfaces/statusready.md)›*

___

### `Const` StatusApiFp

▸ **StatusApiFp**(`configuration?`: [Configuration](classes/configuration.md)): *object*

*Defined in [packages/insights/api.ts:940](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L940)*

StatusApi - functional programming interface

**`export`** 

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |

**Returns:** *object*

* **statusList**(`options?`: any): *Promise‹function›*

* **statusLiveRead**(`options?`: any): *Promise‹function›*

* **statusReadyRead**(`options?`: any): *Promise‹function›*

___

### `Const` SystemtypeApiAxiosParamCreator

▸ **SystemtypeApiAxiosParamCreator**(`configuration?`: [Configuration](classes/configuration.md)): *object*

*Defined in [packages/insights/api.ts:1067](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L1067)*

SystemtypeApi - axios parameter creator

**`export`** 

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |

**Returns:** *object*

* **systemtypeList**(`options`: any): *Promise‹[RequestArgs](interfaces/requestargs.md)›*

* **systemtypeRead**(`id`: number, `options`: any): *Promise‹[RequestArgs](interfaces/requestargs.md)›*

___

### `Const` SystemtypeApiFactory

▸ **SystemtypeApiFactory**(`configuration?`: [Configuration](classes/configuration.md), `basePath?`: string, `axios?`: AxiosInstance): *object*

*Defined in [packages/insights/api.ts:1178](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L1178)*

SystemtypeApi - factory interface

**`export`** 

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |
`basePath?` | string |
`axios?` | AxiosInstance |

**Returns:** *object*

* **systemtypeList**(`options?`: any): *AxiosPromise‹Array‹[SystemType](interfaces/systemtype.md)››*

* **systemtypeRead**(`id`: number, `options?`: any): *AxiosPromise‹[SystemType](interfaces/systemtype.md)›*

___

### `Const` SystemtypeApiFp

▸ **SystemtypeApiFp**(`configuration?`: [Configuration](classes/configuration.md)): *object*

*Defined in [packages/insights/api.ts:1142](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L1142)*

SystemtypeApi - functional programming interface

**`export`** 

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |

**Returns:** *object*

* **systemtypeList**(`options?`: any): *Promise‹function›*

* **systemtypeRead**(`id`: number, `options?`: any): *Promise‹function›*

___

### `Const` TotalRiskApiAxiosParamCreator

▸ **TotalRiskApiAxiosParamCreator**(`configuration?`: [Configuration](classes/configuration.md)): *object*

*Defined in [packages/insights/api.ts:1239](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L1239)*

TotalRiskApi - axios parameter creator

**`export`** 

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |

**Returns:** *object*

* **totalRiskList**(`options`: any): *Promise‹[RequestArgs](interfaces/requestargs.md)›*

___

### `Const` TotalRiskApiFactory

▸ **TotalRiskApiFactory**(`configuration?`: [Configuration](classes/configuration.md), `basePath?`: string, `axios?`: AxiosInstance): *object*

*Defined in [packages/insights/api.ts:1300](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L1300)*

TotalRiskApi - factory interface

**`export`** 

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |
`basePath?` | string |
`axios?` | AxiosInstance |

**Returns:** *object*

* **totalRiskList**(`options?`: any): *AxiosPromise‹void›*

___

### `Const` TotalRiskApiFp

▸ **TotalRiskApiFp**(`configuration?`: [Configuration](classes/configuration.md)): *object*

*Defined in [packages/insights/api.ts:1278](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/api.ts#L1278)*

TotalRiskApi - functional programming interface

**`export`** 

**Parameters:**

Name | Type |
------ | ------ |
`configuration?` | [Configuration](classes/configuration.md) |

**Returns:** *object*

* **totalRiskList**(`options?`: any): *Promise‹function›*

## Object literals

### `Const` COLLECTION_FORMATS

### ▪ **COLLECTION_FORMATS**: *object*

*Defined in [packages/insights/base.ts:26](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/base.ts#L26)*

**`export`** 

###  csv

• **csv**: *string* = ","

*Defined in [packages/insights/base.ts:27](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/base.ts#L27)*

###  pipes

• **pipes**: *string* = "|"

*Defined in [packages/insights/base.ts:30](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/base.ts#L30)*

###  ssv

• **ssv**: *string* = " "

*Defined in [packages/insights/base.ts:28](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/base.ts#L28)*

###  tsv

• **tsv**: *string* = "	"

*Defined in [packages/insights/base.ts:29](https://github.com/RedHatInsights/javascript-clients/blob/master/packages/insights/base.ts#L29)*
