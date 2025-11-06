# DtoSysRoleInsertReq


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dataScope** | **string** |  | [optional] [default to undefined]
**deptIds** | **Array&lt;number&gt;** |  | [optional] [default to undefined]
**menuIds** | **Array&lt;number&gt;** |  | [optional] [default to undefined]
**remark** | **string** | 备注 | [optional] [default to undefined]
**roleKey** | **string** | 角色代码 | [optional] [default to undefined]
**roleName** | **string** | 角色名称 | [optional] [default to undefined]
**roleSort** | **number** | 角色排序 | [optional] [default to undefined]
**status** | **string** | 状态 | [optional] [default to undefined]
**sysDept** | [**Array&lt;ModelsSysDept&gt;**](ModelsSysDept.md) |  | [optional] [default to undefined]
**sysMenu** | [**Array&lt;ModelsSysMenu&gt;**](ModelsSysMenu.md) |  | [optional] [default to undefined]

## Example

```typescript
import { DtoSysRoleInsertReq } from './api';

const instance: DtoSysRoleInsertReq = {
    dataScope,
    deptIds,
    menuIds,
    remark,
    roleKey,
    roleName,
    roleSort,
    status,
    sysDept,
    sysMenu,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
