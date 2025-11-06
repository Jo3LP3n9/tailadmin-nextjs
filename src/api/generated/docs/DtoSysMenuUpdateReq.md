# DtoSysMenuUpdateReq


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**apis** | **Array&lt;number&gt;** |  | [optional] [default to undefined]
**element** | **string** | 组件 | [optional] [default to undefined]
**icon** | **string** | 图标 | [optional] [default to undefined]
**isAffix** | **string** | 是否固定 | [optional] [default to undefined]
**isFrame** | **string** | 是否frame | [optional] [default to undefined]
**isHidden** | **string** | 是否显示 | [optional] [default to undefined]
**isKeepAlive** | **string** | 是否缓存 | [optional] [default to undefined]
**menuType** | **string** | 菜单类型 | [optional] [default to undefined]
**parentId** | **number** | 上级菜单 | [optional] [default to undefined]
**path** | **string** | 路径 | [optional] [default to undefined]
**permission** | **string** | 权限编码 | [optional] [default to undefined]
**redirect** | **string** | 针对目录跳转，比如搜索出菜单 | [optional] [default to undefined]
**sort** | **number** | 排序 | [optional] [default to undefined]
**sysApi** | [**Array&lt;ModelsSysApi&gt;**](ModelsSysApi.md) |  | [optional] [default to undefined]
**title** | **string** | 显示名称 | [optional] [default to undefined]

## Example

```typescript
import { DtoSysMenuUpdateReq } from './api';

const instance: DtoSysMenuUpdateReq = {
    apis,
    element,
    icon,
    isAffix,
    isFrame,
    isHidden,
    isKeepAlive,
    menuType,
    parentId,
    path,
    permission,
    redirect,
    sort,
    sysApi,
    title,
};
```

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)
