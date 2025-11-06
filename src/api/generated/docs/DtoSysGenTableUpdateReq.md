# DtoSysGenTableUpdateReq


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**businessName** | **string** |  | [optional] [default to undefined]
**className** | **string** |  | [optional] [default to undefined]
**functionAuthor** | **string** |  | [optional] [default to undefined]
**functionName** | **string** |  | [optional] [default to undefined]
**moduleName** | **string** |  | [optional] [default to undefined]
**packageName** | **string** |  | [optional] [default to undefined]
**remark** | **string** |  | [optional] [default to undefined]
**sysGenColumns** | [**Array&lt;DtoSysGenColumnUpdateReq&gt;**](DtoSysGenColumnUpdateReq.md) |  | [optional] [default to undefined]
**tableComment** | **string** | 表备注 | [optional] [default to undefined]

## Example

```typescript
import { DtoSysGenTableUpdateReq } from './api';

const instance: DtoSysGenTableUpdateReq = {
    businessName,
    className,
    functionAuthor,
    functionName,
    moduleName,
    packageName,
    remark,
    sysGenColumns,
    tableComment,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
