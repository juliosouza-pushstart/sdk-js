> **[@directus/sdk-js](../README.md)**

[Globals](../README.md) / ["schemes/response/Setting"](../modules/_schemes_response_setting_.md) / [ISettingsResponse](_schemes_response_setting_.isettingsresponse.md) /

# Interface: ISettingsResponse

**`see`** https://docs.directus.io/api/reference.html#settings

## Hierarchy

  * [IAPIResponse](_schemes_apiresponse_.iapiresponse.md)‹*[ISetting](_schemes_directus_setting_.isetting.md)[]*, *[IAPIMetaList](_schemes_apiresponse_.iapimetalist.md)*›

  * **ISettingsResponse**

### Index

#### Properties

* [data](_schemes_response_setting_.isettingsresponse.md#data)
* [error](_schemes_response_setting_.isettingsresponse.md#optional-error)
* [meta](_schemes_response_setting_.isettingsresponse.md#meta)

## Properties

###  data

• **data**: *[ISetting](_schemes_directus_setting_.isetting.md)[]*

*Inherited from [IAPIResponse](_schemes_apiresponse_.iapiresponse.md).[data](_schemes_apiresponse_.iapiresponse.md#data)*

*Defined in [schemes/APIResponse.ts:13](https://github.com/direcuts/sdk-js/tree/master/schemes/APIResponse.ts#L13)*

___

### `Optional` error

• **error**? : *object*

*Inherited from [IAbstractAPIResponse](_schemes_apiresponse_.iabstractapiresponse.md).[error](_schemes_apiresponse_.iabstractapiresponse.md#optional-error)*

*Defined in [schemes/APIResponse.ts:2](https://github.com/direcuts/sdk-js/tree/master/schemes/APIResponse.ts#L2)*

#### Type declaration:

* **code**: *number*

* **message**: *string*

___

###  meta

• **meta**: *[IAPIMetaList](_schemes_apiresponse_.iapimetalist.md)*

*Inherited from [IAPIResponse](_schemes_apiresponse_.iapiresponse.md).[meta](_schemes_apiresponse_.iapiresponse.md#meta)*

*Defined in [schemes/APIResponse.ts:12](https://github.com/direcuts/sdk-js/tree/master/schemes/APIResponse.ts#L12)*