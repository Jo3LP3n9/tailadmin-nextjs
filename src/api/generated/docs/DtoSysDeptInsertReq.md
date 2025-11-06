# DtoSysDeptInsertReq


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**deptName** | **string** | 部门名称 | [optional] [default to undefined]
**email** | **string** | 邮箱 | [optional] [default to undefined]
**leader** | **string** | 负责人 | [optional] [default to undefined]
**parentId** | **number** | 上级部门 | [optional] [default to undefined]
**phone** | **string** | 手机 | [optional] [default to undefined]
**sort** | **number** | 排序 | [optional] [default to undefined]

## Example

```typescript
import { DtoSysDeptInsertReq } from './api';

const instance: DtoSysDeptInsertReq = {
    deptName,
    email,
    leader,
    parentId,
    phone,
    sort,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
