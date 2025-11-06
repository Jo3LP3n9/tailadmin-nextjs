# DefaultApi

All URIs are relative to *http://localhost:8888/admin-api/v1*

|Method | HTTP request | Description|
|------------- | ------------- | -------------|
|[**appUserUserAccountLogExportPost**](#appuseruseraccountlogexportpost) | **POST** /app/user/user-account-log/export | 導出帳變記錄|
|[**appUserUserAccountLogGet**](#appuseruseraccountlogget) | **GET** /app/user/user-account-log | 獲取帳變記錄分頁列表|
|[**appUserUserAccountLogIdGet**](#appuseruseraccountlogidget) | **GET** /app/user/user-account-log/{id} | 獲取帳變記錄詳情|
|[**appUserUserConfGet**](#appuseruserconfget) | **GET** /app/user/user-conf | 獲取用戶配置管理分頁列表|
|[**appUserUserConfIdGet**](#appuseruserconfidget) | **GET** /app/user/user-conf/{id} | 獲取用戶配置管理詳情|
|[**appUserUserConfIdPut**](#appuseruserconfidput) | **PUT** /app/user/user-conf/{id} | 更新用戶配置管理|
|[**appUserUserCountryCodeDelete**](#appuserusercountrycodedelete) | **DELETE** /app/user/user-country-code | 刪除國家區號管理|
|[**appUserUserCountryCodeExportPost**](#appuserusercountrycodeexportpost) | **POST** /app/user/user-country-code/export | 導出國家區號管理|
|[**appUserUserCountryCodeGet**](#appuserusercountrycodeget) | **GET** /app/user/user-country-code | 獲取國家區號管理分頁列表|
|[**appUserUserCountryCodeIdGet**](#appuserusercountrycodeidget) | **GET** /app/user/user-country-code/{id} | 獲取國家區號管理詳情|
|[**appUserUserCountryCodeIdPut**](#appuserusercountrycodeidput) | **PUT** /app/user/user-country-code/{id} | 更新國家區號管理|
|[**appUserUserCountryCodePost**](#appuserusercountrycodepost) | **POST** /app/user/user-country-code | 新增國家區號管理|
|[**appUserUserExportPost**](#appuseruserexportpost) | **POST** /app/user/user/export | 導出用戶管理|
|[**appUserUserGet**](#appuseruserget) | **GET** /app/user/user | 獲取用戶管理分頁列表|
|[**appUserUserIdGet**](#appuseruseridget) | **GET** /app/user/user/{id} | 獲取用戶管理詳情|
|[**appUserUserIdPut**](#appuseruseridput) | **PUT** /app/user/user/{id} | 更新用戶管理|
|[**appUserUserLevelDelete**](#appuseruserleveldelete) | **DELETE** /app/user/user-level | 刪除用戶等級管理|
|[**appUserUserLevelExportPost**](#appuseruserlevelexportpost) | **POST** /app/user/user-level/export | 導出用戶等級管理|
|[**appUserUserLevelGet**](#appuseruserlevelget) | **GET** /app/user/user-level | 獲取用戶等級管理分頁列表|
|[**appUserUserLevelIdGet**](#appuseruserlevelidget) | **GET** /app/user/user-level/{id} | 獲取用戶等級管理詳情|
|[**appUserUserLevelIdPut**](#appuseruserlevelidput) | **PUT** /app/user/user-level/{id} | 更新用戶等級管理|
|[**appUserUserLevelPost**](#appuseruserlevelpost) | **POST** /app/user/user-level | 新增用戶等級管理|
|[**appUserUserOperLogExportPost**](#appuseruseroperlogexportpost) | **POST** /app/user/user-oper-log/export | 導出用戶操作日誌|
|[**appUserUserOperLogGet**](#appuseruseroperlogget) | **GET** /app/user/user-oper-log | 獲取用戶操作日誌分頁列表|
|[**appUserUserOperLogIdGet**](#appuseruseroperlogidget) | **GET** /app/user/user-oper-log/{id} | 獲取用戶操作日誌詳情|
|[**appUserUserPost**](#appuseruserpost) | **POST** /app/user/user | 新增用戶管理|
|[**captchaGet**](#captchaget) | **GET** /captcha | 獲取圖形驗證碼|
|[**deptDelete**](#deptdelete) | **DELETE** /dept | 刪除部門管理|
|[**deptIdGet**](#deptidget) | **GET** /dept/{id} | 獲取部門管理詳情|
|[**deptPost**](#deptpost) | **POST** /dept | 新增部門管理|
|[**deptPut**](#deptput) | **PUT** /dept | 更新部門管理|
|[**deptRoleDeptTreeSelectRoleIdGet**](#deptroledepttreeselectroleidget) | **GET** /dept/role-dept-tree-select/{roleId} | 根據角色獲取部門|
|[**deptTreeGet**](#depttreeget) | **GET** /dept/tree | 獲取部門管理樹|
|[**dictDataDelete**](#dictdatadelete) | **DELETE** /dict/data | 刪除字典數據|
|[**dictDataGet**](#dictdataget) | **GET** /dict/data | 獲取字典數據分頁列表|
|[**dictDataIdGet**](#dictdataidget) | **GET** /dict/data/{id} | 獲取字典數據詳情|
|[**dictDataListGet**](#dictdatalistget) | **GET** /dict/data/list | 獲取字典數據全部列表|
|[**dictDataPost**](#dictdatapost) | **POST** /dict/data | 新增字典數據|
|[**dictDataPut**](#dictdataput) | **PUT** /dict/data | 更新字典數據|
|[**dictTypeDelete**](#dicttypedelete) | **DELETE** /dict/type | 刪除字典類型|
|[**dictTypeExportPost**](#dicttypeexportpost) | **POST** /dict/type/export | 導出字典類型|
|[**dictTypeGet**](#dicttypeget) | **GET** /dict/type | 獲取字典類型分頁列表|
|[**dictTypeIdGet**](#dicttypeidget) | **GET** /dict/type/{id} | 獲取字典類型詳情|
|[**dictTypeListGet**](#dicttypelistget) | **GET** /dict/type/list | 獲取字典類型全部列表|
|[**dictTypePost**](#dicttypepost) | **POST** /dict/type | 新增字典類型|
|[**dictTypePut**](#dicttypeput) | **PUT** /dict/type | 更新字典類型|
|[**loginPost**](#loginpost) | **POST** /login | 登入系統|
|[**logoutPost**](#logoutpost) | **POST** /logout | 退出系統|
|[**menuDelete**](#menudelete) | **DELETE** /menu | 刪除菜單管理|
|[**menuIdGet**](#menuidget) | **GET** /menu/{id} | 獲取菜單管理詳情|
|[**menuPost**](#menupost) | **POST** /menu | 新增菜單管理|
|[**menuPut**](#menuput) | **PUT** /menu | 更新菜單管理|
|[**menuRoleGet**](#menuroleget) | **GET** /menu/role | 根據角色獲取菜單|
|[**menuRoleMenuTreeSelectRoleIdGet**](#menurolemenutreeselectroleidget) | **GET** /menu/role-menu-tree-select/{roleId} | 獲取全部菜單以及選中的菜單編號|
|[**menuTreeGet**](#menutreeget) | **GET** /menu/tree | 獲取菜單管理樹|
|[**metricsGet**](#metricsget) | **GET** /metrics | 獲取Prometheus指標|
|[**monitorGet**](#monitorget) | **GET** /monitor | 獲取伺服器信息|
|[**pingGet**](#pingget) | **GET** /ping | Ping測試|
|[**pluginsContentContentAnnouncementDelete**](#pluginscontentcontentannouncementdelete) | **DELETE** /plugins/content/content-announcement | 刪除公告管理|
|[**pluginsContentContentAnnouncementExportPost**](#pluginscontentcontentannouncementexportpost) | **POST** /plugins/content/content-announcement/export | 導出公告管理|
|[**pluginsContentContentAnnouncementGet**](#pluginscontentcontentannouncementget) | **GET** /plugins/content/content-announcement | 獲取公告管理分頁列表|
|[**pluginsContentContentAnnouncementIdGet**](#pluginscontentcontentannouncementidget) | **GET** /plugins/content/content-announcement/{id} | 獲取公告管理詳情|
|[**pluginsContentContentAnnouncementIdPut**](#pluginscontentcontentannouncementidput) | **PUT** /plugins/content/content-announcement/{id} | 更新公告管理|
|[**pluginsContentContentAnnouncementPost**](#pluginscontentcontentannouncementpost) | **POST** /plugins/content/content-announcement | 新增公告管理|
|[**pluginsContentContentArticleDelete**](#pluginscontentcontentarticledelete) | **DELETE** /plugins/content/content-article | 刪除文章管理|
|[**pluginsContentContentArticleExportPost**](#pluginscontentcontentarticleexportpost) | **POST** /plugins/content/content-article/export | 導出文章管理|
|[**pluginsContentContentArticleGet**](#pluginscontentcontentarticleget) | **GET** /plugins/content/content-article | 獲取文章管理分頁列表|
|[**pluginsContentContentArticleIdGet**](#pluginscontentcontentarticleidget) | **GET** /plugins/content/content-article/{id} | 獲取文章管理詳情|
|[**pluginsContentContentArticleIdPut**](#pluginscontentcontentarticleidput) | **PUT** /plugins/content/content-article/{id} | 更新文章管理|
|[**pluginsContentContentArticlePost**](#pluginscontentcontentarticlepost) | **POST** /plugins/content/content-article | 新增文章管理|
|[**pluginsContentContentCategoryDelete**](#pluginscontentcontentcategorydelete) | **DELETE** /plugins/content/content-category | 刪除內容分類管理|
|[**pluginsContentContentCategoryExportPost**](#pluginscontentcontentcategoryexportpost) | **POST** /plugins/content/content-category/export | 導出內容分類管理|
|[**pluginsContentContentCategoryGet**](#pluginscontentcontentcategoryget) | **GET** /plugins/content/content-category | 獲取內容分類管理分頁列表|
|[**pluginsContentContentCategoryIdGet**](#pluginscontentcontentcategoryidget) | **GET** /plugins/content/content-category/{id} | 獲取內容分類管理詳情|
|[**pluginsContentContentCategoryIdPut**](#pluginscontentcontentcategoryidput) | **PUT** /plugins/content/content-category/{id} | 更新內容分類管理|
|[**pluginsContentContentCategoryPost**](#pluginscontentcontentcategorypost) | **POST** /plugins/content/content-category | 新增內容分類管理|
|[**pluginsMsgMsgCodeGet**](#pluginsmsgmsgcodeget) | **GET** /plugins/msg/msg-code | 獲取驗證碼管理分頁列表|
|[**pluginsMsgMsgCodeIdGet**](#pluginsmsgmsgcodeidget) | **GET** /plugins/msg/msg-code/{id} | 獲取驗證碼管理詳情|
|[**postDelete**](#postdelete) | **DELETE** /post | 刪除崗位管理|
|[**postExportPost**](#postexportpost) | **POST** /post/export | 導出崗位管理|
|[**postGet**](#postget) | **GET** /post | 獲取崗位管理分頁列表|
|[**postIdGet**](#postidget) | **GET** /post/{id} | 獲取崗位管理詳情|
|[**postListGet**](#postlistget) | **GET** /post/list | 獲取崗位管理全部列表|
|[**postPost**](#postpost) | **POST** /post | 新增崗位管理|
|[**postPut**](#postput) | **PUT** /post | 更新崗位管理|
|[**roleDataScopePut**](#roledatascopeput) | **PUT** /role/data-scope | 更新角色管理數據權限|
|[**roleDelete**](#roledelete) | **DELETE** /role | 刪除角色管理|
|[**roleGet**](#roleget) | **GET** /role | 獲取角色管理分頁列表|
|[**roleIdGet**](#roleidget) | **GET** /role/{id} | 獲取角色管理詳情|
|[**roleListGet**](#rolelistget) | **GET** /role/list | 獲取角色管理全部列表|
|[**rolePost**](#rolepost) | **POST** /role | 新增角色管理|
|[**rolePut**](#roleput) | **PUT** /role | 更新角色管理|
|[**roleStatusPut**](#rolestatusput) | **PUT** /role/status | 更新角色管理狀態|
|[**sysApiDelete**](#sysapidelete) | **DELETE** /sys-api | 刪除接口管理|
|[**sysApiExportPost**](#sysapiexportpost) | **POST** /sys-api/export | 導出接口管理|
|[**sysApiGet**](#sysapiget) | **GET** /sys-api | 獲取接口管理分頁列表|
|[**sysApiIdGet**](#sysapiidget) | **GET** /sys-api/{id} | 獲取接口管理詳情|
|[**sysApiListGet**](#sysapilistget) | **GET** /sys-api/list | 獲取接口管理全部列表|
|[**sysApiPut**](#sysapiput) | **PUT** /sys-api | 更新接口管理|
|[**sysApiSyncPost**](#sysapisyncpost) | **POST** /sys-api/sync | 同步接口數據|
|[**sysConfigByKeyConfigKeyGet**](#sysconfigbykeyconfigkeyget) | **GET** /sys-config/by-key/{configKey} | 根據Key獲取配置值|
|[**sysConfigDelete**](#sysconfigdelete) | **DELETE** /sys-config | 刪除配置管理|
|[**sysConfigExportPost**](#sysconfigexportpost) | **POST** /sys-config/export | 導出配置管理|
|[**sysConfigGet**](#sysconfigget) | **GET** /sys-config | 獲取配置管理分頁列表|
|[**sysConfigIdGet**](#sysconfigidget) | **GET** /sys-config/{id} | 獲取配置管理詳情|
|[**sysConfigPost**](#sysconfigpost) | **POST** /sys-config | 新增配置管理|
|[**sysConfigPut**](#sysconfigput) | **PUT** /sys-config | 更新配置管理|
|[**sysGenTablesDbTablesGet**](#sysgentablesdbtablesget) | **GET** /sys-gen-tables/db/tables | 獲取表管理的DB表分頁列表|
|[**sysGenTablesDelete**](#sysgentablesdelete) | **DELETE** /sys-gen-tables | 刪除表管理|
|[**sysGenTablesDownloadPost**](#sysgentablesdownloadpost) | **POST** /sys-gen-tables/download | 表管理下載代碼|
|[**sysGenTablesGenCodePost**](#sysgentablesgencodepost) | **POST** /sys-gen-tables/gen-code | 生成表管理的代碼|
|[**sysGenTablesGenDbIdPost**](#sysgentablesgendbidpost) | **POST** /sys-gen-tables/gen-db/{id} | 表管理中生成菜單數據|
|[**sysGenTablesGet**](#sysgentablesget) | **GET** /sys-gen-tables | 獲取表管理分頁列表|
|[**sysGenTablesIdGet**](#sysgentablesidget) | **GET** /sys-gen-tables/{id} | 獲取表管理詳情|
|[**sysGenTablesPost**](#sysgentablespost) | **POST** /sys-gen-tables | 新增表管理|
|[**sysGenTablesPreviewIdGet**](#sysgentablespreviewidget) | **GET** /sys-gen-tables/preview/{id} | 預覽表管理的代碼頁面|
|[**sysGenTablesPut**](#sysgentablesput) | **PUT** /sys-gen-tables | 更新表管理|
|[**sysLoginLogDelete**](#sysloginlogdelete) | **DELETE** /sys-login-log | 刪除登錄日誌|
|[**sysLoginLogExportPost**](#sysloginlogexportpost) | **POST** /sys-login-log/export | 導出登錄日誌|
|[**sysLoginLogGet**](#sysloginlogget) | **GET** /sys-login-log | 獲取登錄日誌分頁列表|
|[**sysLoginLogIdGet**](#sysloginlogidget) | **GET** /sys-login-log/{id} | 獲取登錄日誌詳情|
|[**sysOperaLogDelete**](#sysoperalogdelete) | **DELETE** /sys-opera-log | 刪除操作日誌|
|[**sysOperaLogExportPost**](#sysoperalogexportpost) | **POST** /sys-opera-log/export | 導出操作日誌|
|[**sysOperaLogGet**](#sysoperalogget) | **GET** /sys-opera-log | 獲取操作日誌分頁列表|
|[**sysOperaLogIdGet**](#sysoperalogidget) | **GET** /sys-opera-log/{id} | 獲取操作日誌詳情|
|[**sysUserDelete**](#sysuserdelete) | **DELETE** /sys-user | 刪除系統用戶管理|
|[**sysUserGet**](#sysuserget) | **GET** /sys-user | 獲取系統用戶管理分頁列表|
|[**sysUserIdGet**](#sysuseridget) | **GET** /sys-user/{id} | 獲取系統用戶管理詳情|
|[**sysUserPost**](#sysuserpost) | **POST** /sys-user | 新增系統用戶管理|
|[**sysUserProfileAvatarPost**](#sysuserprofileavatarpost) | **POST** /sys-user/profile/avatar | 更新系統登入用戶頭像|
|[**sysUserProfileGet**](#sysuserprofileget) | **GET** /sys-user/profile | 獲取系統登入用戶信息|
|[**sysUserProfilePut**](#sysuserprofileput) | **PUT** /sys-user/profile | 更新系統登入用戶信息|
|[**sysUserProfilePwdPut**](#sysuserprofilepwdput) | **PUT** /sys-user/profile/pwd | 更新系統登入用戶密碼|
|[**sysUserPut**](#sysuserput) | **PUT** /sys-user | 更新系統用戶管理|
|[**sysUserPwdResetPut**](#sysuserpwdresetput) | **PUT** /sys-user/pwd/reset | 重置系統用戶密碼|
|[**sysUserStatusPut**](#sysuserstatusput) | **PUT** /sys-user/status | 更新系統用戶狀態|

# **appUserUserAccountLogExportPost**
> ResponseResponse appUserUserAccountLogExportPost()

導出帳變記錄

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let moneyType: string; //金額類型 1:餘額 (optional) (default to undefined)
let changeType: string; //帳變類型(1-類型1) (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)
let trueName: string; //真實姓名 (optional) (default to undefined)
let userName: string; //暱稱 (optional) (default to undefined)
let mobile: string; //手機號 (optional) (default to undefined)
let email: string; //郵箱 (optional) (default to undefined)

const { status, data } = await apiInstance.appUserUserAccountLogExportPost(
    moneyType,
    changeType,
    beginCreatedAt,
    endCreatedAt,
    trueName,
    userName,
    mobile,
    email
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **moneyType** | [**string**] | 金額類型 1:餘額 | (optional) defaults to undefined|
| **changeType** | [**string**] | 帳變類型(1-類型1) | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|
| **trueName** | [**string**] | 真實姓名 | (optional) defaults to undefined|
| **userName** | [**string**] | 暱稱 | (optional) defaults to undefined|
| **mobile** | [**string**] | 手機號 | (optional) defaults to undefined|
| **email** | [**string**] | 郵箱 | (optional) defaults to undefined|


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **appUserUserAccountLogGet**
> AppUserUserAccountLogGet200Response appUserUserAccountLogGet()

獲取帳變記錄分頁列表

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let moneyType: string; //金額類型 1:餘額 (optional) (default to undefined)
let changeType: string; //帳變類型(1-類型1) (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)
let trueName: string; //真實姓名 (optional) (default to undefined)
let userName: string; //暱稱 (optional) (default to undefined)
let mobile: string; //手機號 (optional) (default to undefined)
let email: string; //郵箱 (optional) (default to undefined)
let idOrder: number; //編號排序 (optional) (default to undefined)
let userIdOrder: number; //用戶編號排序 (optional) (default to undefined)
let changeMoneyOrder: number; //帳變金額排序 (optional) (default to undefined)
let moneyTypeOrder: string; //金額類型排序 (optional) (default to undefined)
let changeTypeOrder: string; //帳變類型排序 (optional) (default to undefined)
let statusOrder: string; //狀態排序 (optional) (default to undefined)
let createdAtOrder: string; //建立時間排序 (optional) (default to undefined)
let pageSize: number; //頁條數 (optional) (default to undefined)
let pageIndex: number; //頁碼 (optional) (default to undefined)

const { status, data } = await apiInstance.appUserUserAccountLogGet(
    moneyType,
    changeType,
    beginCreatedAt,
    endCreatedAt,
    trueName,
    userName,
    mobile,
    email,
    idOrder,
    userIdOrder,
    changeMoneyOrder,
    moneyTypeOrder,
    changeTypeOrder,
    statusOrder,
    createdAtOrder,
    pageSize,
    pageIndex
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **moneyType** | [**string**] | 金額類型 1:餘額 | (optional) defaults to undefined|
| **changeType** | [**string**] | 帳變類型(1-類型1) | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|
| **trueName** | [**string**] | 真實姓名 | (optional) defaults to undefined|
| **userName** | [**string**] | 暱稱 | (optional) defaults to undefined|
| **mobile** | [**string**] | 手機號 | (optional) defaults to undefined|
| **email** | [**string**] | 郵箱 | (optional) defaults to undefined|
| **idOrder** | [**number**] | 編號排序 | (optional) defaults to undefined|
| **userIdOrder** | [**number**] | 用戶編號排序 | (optional) defaults to undefined|
| **changeMoneyOrder** | [**number**] | 帳變金額排序 | (optional) defaults to undefined|
| **moneyTypeOrder** | [**string**] | 金額類型排序 | (optional) defaults to undefined|
| **changeTypeOrder** | [**string**] | 帳變類型排序 | (optional) defaults to undefined|
| **statusOrder** | [**string**] | 狀態排序 | (optional) defaults to undefined|
| **createdAtOrder** | [**string**] | 建立時間排序 | (optional) defaults to undefined|
| **pageSize** | [**number**] | 頁條數 | (optional) defaults to undefined|
| **pageIndex** | [**number**] | 頁碼 | (optional) defaults to undefined|


### Return type

**AppUserUserAccountLogGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **appUserUserAccountLogIdGet**
> AppUserUserAccountLogIdGet200Response appUserUserAccountLogIdGet()

獲取帳變記錄詳情

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //帳變記錄編號 (default to undefined)

const { status, data } = await apiInstance.appUserUserAccountLogIdGet(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | 帳變記錄編號 | defaults to undefined|


### Return type

**AppUserUserAccountLogIdGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **appUserUserConfGet**
> AppUserUserConfGet200Response appUserUserConfGet()

獲取用戶配置管理分頁列表

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let canLogin: string; //1-允許登入；2-不允許登入 (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)
let trueName: string; //真實姓名 (optional) (default to undefined)
let userName: string; //暱稱 (optional) (default to undefined)
let mobile: string; //手機號 (optional) (default to undefined)
let email: string; //郵箱 (optional) (default to undefined)
let idOrder: number; //編號排序 (optional) (default to undefined)
let userIdOrder: number; //用戶編號排序 (optional) (default to undefined)
let canLoginOrder: string; //允許登入排序 (optional) (default to undefined)
let statusOrder: string; //狀態排序 (optional) (default to undefined)
let createdAtOrder: string; //建立時間排序 (optional) (default to undefined)
let pageSize: number; //頁條數 (optional) (default to undefined)
let pageIndex: number; //頁碼 (optional) (default to undefined)

const { status, data } = await apiInstance.appUserUserConfGet(
    canLogin,
    beginCreatedAt,
    endCreatedAt,
    trueName,
    userName,
    mobile,
    email,
    idOrder,
    userIdOrder,
    canLoginOrder,
    statusOrder,
    createdAtOrder,
    pageSize,
    pageIndex
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **canLogin** | [**string**] | 1-允許登入；2-不允許登入 | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|
| **trueName** | [**string**] | 真實姓名 | (optional) defaults to undefined|
| **userName** | [**string**] | 暱稱 | (optional) defaults to undefined|
| **mobile** | [**string**] | 手機號 | (optional) defaults to undefined|
| **email** | [**string**] | 郵箱 | (optional) defaults to undefined|
| **idOrder** | [**number**] | 編號排序 | (optional) defaults to undefined|
| **userIdOrder** | [**number**] | 用戶編號排序 | (optional) defaults to undefined|
| **canLoginOrder** | [**string**] | 允許登入排序 | (optional) defaults to undefined|
| **statusOrder** | [**string**] | 狀態排序 | (optional) defaults to undefined|
| **createdAtOrder** | [**string**] | 建立時間排序 | (optional) defaults to undefined|
| **pageSize** | [**number**] | 頁條數 | (optional) defaults to undefined|
| **pageIndex** | [**number**] | 頁碼 | (optional) defaults to undefined|


### Return type

**AppUserUserConfGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **appUserUserConfIdGet**
> AppUserUserConfIdGet200Response appUserUserConfIdGet()

獲取用戶配置管理詳情

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //配置編號 (default to undefined)

const { status, data } = await apiInstance.appUserUserConfIdGet(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | 配置編號 | defaults to undefined|


### Return type

**AppUserUserConfIdGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **appUserUserConfIdPut**
> ResponseResponse appUserUserConfIdPut(data)

更新用戶配置管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoUserConfUpdateReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //配置編號 (default to undefined)
let data: DtoUserConfUpdateReq; //body

const { status, data } = await apiInstance.appUserUserConfIdPut(
    id,
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoUserConfUpdateReq**| body | |
| **id** | [**number**] | 配置編號 | defaults to undefined|


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **appUserUserCountryCodeDelete**
> ResponseResponse appUserUserCountryCodeDelete(data)

刪除國家區號管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoUserCountryCodeDeleteReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoUserCountryCodeDeleteReq; //body

const { status, data } = await apiInstance.appUserUserCountryCodeDelete(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoUserCountryCodeDeleteReq**| body | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **appUserUserCountryCodeExportPost**
> ResponseResponse appUserUserCountryCodeExportPost()

導出國家區號管理

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let country: string; //國家地區 (optional) (default to undefined)
let code: string; //區號 (optional) (default to undefined)
let status: string; //狀態(1-可用 2-停用) (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)

const { status, data } = await apiInstance.appUserUserCountryCodeExportPost(
    country,
    code,
    status,
    beginCreatedAt,
    endCreatedAt
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **country** | [**string**] | 國家地區 | (optional) defaults to undefined|
| **code** | [**string**] | 區號 | (optional) defaults to undefined|
| **status** | [**string**] | 狀態(1-可用 2-停用) | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **appUserUserCountryCodeGet**
> AppUserUserCountryCodeGet200Response appUserUserCountryCodeGet()

獲取國家區號管理分頁列表

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let country: string; //國家地區 (optional) (default to undefined)
let code: string; //區號 (optional) (default to undefined)
let status: string; //狀態(1-可用 2-停用) (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)
let idOrder: number; //編號排序 (optional) (default to undefined)
let countryOrder: string; //國家地區排序 (optional) (default to undefined)
let codeOrder: string; //區號排序 (optional) (default to undefined)
let statusOrder: string; //狀態排序 (optional) (default to undefined)
let createdAtOrder: string; //建立時間排序 (optional) (default to undefined)
let pageSize: number; //頁條數 (optional) (default to undefined)
let pageIndex: number; //頁碼 (optional) (default to undefined)

const { status, data } = await apiInstance.appUserUserCountryCodeGet(
    country,
    code,
    status,
    beginCreatedAt,
    endCreatedAt,
    idOrder,
    countryOrder,
    codeOrder,
    statusOrder,
    createdAtOrder,
    pageSize,
    pageIndex
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **country** | [**string**] | 國家地區 | (optional) defaults to undefined|
| **code** | [**string**] | 區號 | (optional) defaults to undefined|
| **status** | [**string**] | 狀態(1-可用 2-停用) | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|
| **idOrder** | [**number**] | 編號排序 | (optional) defaults to undefined|
| **countryOrder** | [**string**] | 國家地區排序 | (optional) defaults to undefined|
| **codeOrder** | [**string**] | 區號排序 | (optional) defaults to undefined|
| **statusOrder** | [**string**] | 狀態排序 | (optional) defaults to undefined|
| **createdAtOrder** | [**string**] | 建立時間排序 | (optional) defaults to undefined|
| **pageSize** | [**number**] | 頁條數 | (optional) defaults to undefined|
| **pageIndex** | [**number**] | 頁碼 | (optional) defaults to undefined|


### Return type

**AppUserUserCountryCodeGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **appUserUserCountryCodeIdGet**
> AppUserUserCountryCodeIdGet200Response appUserUserCountryCodeIdGet()

獲取國家區號管理詳情

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //編號 (default to undefined)

const { status, data } = await apiInstance.appUserUserCountryCodeIdGet(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | 編號 | defaults to undefined|


### Return type

**AppUserUserCountryCodeIdGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **appUserUserCountryCodeIdPut**
> ResponseResponse appUserUserCountryCodeIdPut(data)

更新國家區號管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoUserCountryCodeUpdateReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //編號 (default to undefined)
let data: DtoUserCountryCodeUpdateReq; //body

const { status, data } = await apiInstance.appUserUserCountryCodeIdPut(
    id,
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoUserCountryCodeUpdateReq**| body | |
| **id** | [**number**] | 編號 | defaults to undefined|


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **appUserUserCountryCodePost**
> AppUserUserCountryCodePost200Response appUserUserCountryCodePost(data)

新增國家區號管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoUserCountryCodeInsertReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoUserCountryCodeInsertReq; //body

const { status, data } = await apiInstance.appUserUserCountryCodePost(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoUserCountryCodeInsertReq**| body | |


### Return type

**AppUserUserCountryCodePost200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **appUserUserExportPost**
> ResponseResponse appUserUserExportPost()

導出用戶管理

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)
let levelId: number; //用戶等級編號 (optional) (default to undefined)
let userName: string; //用戶昵稱 (optional) (default to undefined)
let trueName: string; //真實姓名 (optional) (default to undefined)
let email: string; //電子郵箱 (optional) (default to undefined)
let mobileTitle: string; //國家區號 (optional) (default to undefined)
let mobile: string; //手機號碼 (optional) (default to undefined)
let parentId: number; //父級編號 (optional) (default to undefined)
let status: string; //狀態 (optional) (default to undefined)
let parentRefCode: string; //上級用戶邀請碼 (optional) (default to undefined)
let name: string; //等級名稱 (optional) (default to undefined)
let levelType: string; //等級類型 (optional) (default to undefined)
let level: number; //等級 (optional) (default to undefined)

const { status, data } = await apiInstance.appUserUserExportPost(
    beginCreatedAt,
    endCreatedAt,
    levelId,
    userName,
    trueName,
    email,
    mobileTitle,
    mobile,
    parentId,
    status,
    parentRefCode,
    name,
    levelType,
    level
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|
| **levelId** | [**number**] | 用戶等級編號 | (optional) defaults to undefined|
| **userName** | [**string**] | 用戶昵稱 | (optional) defaults to undefined|
| **trueName** | [**string**] | 真實姓名 | (optional) defaults to undefined|
| **email** | [**string**] | 電子郵箱 | (optional) defaults to undefined|
| **mobileTitle** | [**string**] | 國家區號 | (optional) defaults to undefined|
| **mobile** | [**string**] | 手機號碼 | (optional) defaults to undefined|
| **parentId** | [**number**] | 父級編號 | (optional) defaults to undefined|
| **status** | [**string**] | 狀態 | (optional) defaults to undefined|
| **parentRefCode** | [**string**] | 上級用戶邀請碼 | (optional) defaults to undefined|
| **name** | [**string**] | 等級名稱 | (optional) defaults to undefined|
| **levelType** | [**string**] | 等級類型 | (optional) defaults to undefined|
| **level** | [**number**] | 等級 | (optional) defaults to undefined|


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **appUserUserGet**
> AppUserUserGet200Response appUserUserGet()

獲取用戶管理分頁列表

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)
let levelId: number; //用戶等級編號 (optional) (default to undefined)
let userName: string; //用戶昵稱 (optional) (default to undefined)
let trueName: string; //真實姓名 (optional) (default to undefined)
let email: string; //電子郵箱 (optional) (default to undefined)
let mobileTitle: string; //國家區號 (optional) (default to undefined)
let mobile: string; //手機號碼 (optional) (default to undefined)
let parentId: number; //父級編號 (optional) (default to undefined)
let status: string; //狀態 (optional) (default to undefined)
let parentRefCode: string; //上級用戶邀請碼 (optional) (default to undefined)
let name: string; //等級名稱 (optional) (default to undefined)
let levelType: string; //等級類型 (optional) (default to undefined)
let level: number; //等級 (optional) (default to undefined)
let idOrder: number; //編號排序 (optional) (default to undefined)
let levelIdOrder: number; //用戶等級編號排序 (optional) (default to undefined)
let userNameOrder: string; //用戶昵稱排序 (optional) (default to undefined)
let trueNameOrder: string; //真實姓名排序 (optional) (default to undefined)
let moneyOrder: string; //餘額排序 (optional) (default to undefined)
let emailOrder: string; //電子郵箱排序 (optional) (default to undefined)
let mobileTitleOrder: string; //國家區號排序 (optional) (default to undefined)
let mobileOrder: string; //手機號碼排序 (optional) (default to undefined)
let avatarOrder: string; //頭像排序 (optional) (default to undefined)
let payPwdOrder: string; //提現密碼排序 (optional) (default to undefined)
let pwdOrder: string; //登錄密碼排序 (optional) (default to undefined)
let refCodeOrder: string; //推薦碼排序 (optional) (default to undefined)
let parentIdOrder: number; //父級編號排序 (optional) (default to undefined)
let parentIdsOrder: string; //所有父級編號排序 (optional) (default to undefined)
let treeSortOrder: string; //本級排序號排序 (optional) (default to undefined)
let treeSortsOrder: string; //所有級別排序號排序 (optional) (default to undefined)
let treeLeafOrder: string; //是否最末級排序 (optional) (default to undefined)
let treeLevelOrder: number; //層次級別排序 (optional) (default to undefined)
let statusOrder: string; //狀態排序 (optional) (default to undefined)
let remarkOrder: string; //備註排序 (optional) (default to undefined)
let createByOrder: number; //建立者排序 (optional) (default to undefined)
let updateByOrder: number; //更新者排序 (optional) (default to undefined)
let createdAtOrder: string; //建立時間排序 (optional) (default to undefined)
let updatedAtOrder: string; //更新時間排序 (optional) (default to undefined)
let pageSize: number; //頁條數 (optional) (default to undefined)
let pageIndex: number; //頁碼 (optional) (default to undefined)

const { status, data } = await apiInstance.appUserUserGet(
    beginCreatedAt,
    endCreatedAt,
    levelId,
    userName,
    trueName,
    email,
    mobileTitle,
    mobile,
    parentId,
    status,
    parentRefCode,
    name,
    levelType,
    level,
    idOrder,
    levelIdOrder,
    userNameOrder,
    trueNameOrder,
    moneyOrder,
    emailOrder,
    mobileTitleOrder,
    mobileOrder,
    avatarOrder,
    payPwdOrder,
    pwdOrder,
    refCodeOrder,
    parentIdOrder,
    parentIdsOrder,
    treeSortOrder,
    treeSortsOrder,
    treeLeafOrder,
    treeLevelOrder,
    statusOrder,
    remarkOrder,
    createByOrder,
    updateByOrder,
    createdAtOrder,
    updatedAtOrder,
    pageSize,
    pageIndex
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|
| **levelId** | [**number**] | 用戶等級編號 | (optional) defaults to undefined|
| **userName** | [**string**] | 用戶昵稱 | (optional) defaults to undefined|
| **trueName** | [**string**] | 真實姓名 | (optional) defaults to undefined|
| **email** | [**string**] | 電子郵箱 | (optional) defaults to undefined|
| **mobileTitle** | [**string**] | 國家區號 | (optional) defaults to undefined|
| **mobile** | [**string**] | 手機號碼 | (optional) defaults to undefined|
| **parentId** | [**number**] | 父級編號 | (optional) defaults to undefined|
| **status** | [**string**] | 狀態 | (optional) defaults to undefined|
| **parentRefCode** | [**string**] | 上級用戶邀請碼 | (optional) defaults to undefined|
| **name** | [**string**] | 等級名稱 | (optional) defaults to undefined|
| **levelType** | [**string**] | 等級類型 | (optional) defaults to undefined|
| **level** | [**number**] | 等級 | (optional) defaults to undefined|
| **idOrder** | [**number**] | 編號排序 | (optional) defaults to undefined|
| **levelIdOrder** | [**number**] | 用戶等級編號排序 | (optional) defaults to undefined|
| **userNameOrder** | [**string**] | 用戶昵稱排序 | (optional) defaults to undefined|
| **trueNameOrder** | [**string**] | 真實姓名排序 | (optional) defaults to undefined|
| **moneyOrder** | [**string**] | 餘額排序 | (optional) defaults to undefined|
| **emailOrder** | [**string**] | 電子郵箱排序 | (optional) defaults to undefined|
| **mobileTitleOrder** | [**string**] | 國家區號排序 | (optional) defaults to undefined|
| **mobileOrder** | [**string**] | 手機號碼排序 | (optional) defaults to undefined|
| **avatarOrder** | [**string**] | 頭像排序 | (optional) defaults to undefined|
| **payPwdOrder** | [**string**] | 提現密碼排序 | (optional) defaults to undefined|
| **pwdOrder** | [**string**] | 登錄密碼排序 | (optional) defaults to undefined|
| **refCodeOrder** | [**string**] | 推薦碼排序 | (optional) defaults to undefined|
| **parentIdOrder** | [**number**] | 父級編號排序 | (optional) defaults to undefined|
| **parentIdsOrder** | [**string**] | 所有父級編號排序 | (optional) defaults to undefined|
| **treeSortOrder** | [**string**] | 本級排序號排序 | (optional) defaults to undefined|
| **treeSortsOrder** | [**string**] | 所有級別排序號排序 | (optional) defaults to undefined|
| **treeLeafOrder** | [**string**] | 是否最末級排序 | (optional) defaults to undefined|
| **treeLevelOrder** | [**number**] | 層次級別排序 | (optional) defaults to undefined|
| **statusOrder** | [**string**] | 狀態排序 | (optional) defaults to undefined|
| **remarkOrder** | [**string**] | 備註排序 | (optional) defaults to undefined|
| **createByOrder** | [**number**] | 建立者排序 | (optional) defaults to undefined|
| **updateByOrder** | [**number**] | 更新者排序 | (optional) defaults to undefined|
| **createdAtOrder** | [**string**] | 建立時間排序 | (optional) defaults to undefined|
| **updatedAtOrder** | [**string**] | 更新時間排序 | (optional) defaults to undefined|
| **pageSize** | [**number**] | 頁條數 | (optional) defaults to undefined|
| **pageIndex** | [**number**] | 頁碼 | (optional) defaults to undefined|


### Return type

**AppUserUserGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **appUserUserIdGet**
> AppUserUserIdGet200Response appUserUserIdGet()

獲取用戶管理詳情

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //用戶編號 (default to undefined)

const { status, data } = await apiInstance.appUserUserIdGet(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | 用戶編號 | defaults to undefined|


### Return type

**AppUserUserIdGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **appUserUserIdPut**
> ResponseResponse appUserUserIdPut(data)

更新用戶管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoUserUpdateReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //用戶編號 (default to undefined)
let data: DtoUserUpdateReq; //body

const { status, data } = await apiInstance.appUserUserIdPut(
    id,
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoUserUpdateReq**| body | |
| **id** | [**number**] | 用戶編號 | defaults to undefined|


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **appUserUserLevelDelete**
> ResponseResponse appUserUserLevelDelete(data)

刪除用戶等級管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoUserLevelDeleteReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoUserLevelDeleteReq; //body

const { status, data } = await apiInstance.appUserUserLevelDelete(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoUserLevelDeleteReq**| body | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **appUserUserLevelExportPost**
> ResponseResponse appUserUserLevelExportPost()

導出用戶等級管理

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)
let name: string; //等級名稱 (optional) (default to undefined)
let levelType: string; //等級類型 (optional) (default to undefined)
let level: number; //等級 (optional) (default to undefined)

const { status, data } = await apiInstance.appUserUserLevelExportPost(
    beginCreatedAt,
    endCreatedAt,
    name,
    levelType,
    level
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|
| **name** | [**string**] | 等級名稱 | (optional) defaults to undefined|
| **levelType** | [**string**] | 等級類型 | (optional) defaults to undefined|
| **level** | [**number**] | 等級 | (optional) defaults to undefined|


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **appUserUserLevelGet**
> AppUserUserLevelGet200Response appUserUserLevelGet()

獲取用戶等級管理分頁列表

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)
let name: string; //等級名稱 (optional) (default to undefined)
let levelType: string; //等級類型 (optional) (default to undefined)
let level: number; //等級 (optional) (default to undefined)
let idOrder: number; //編號排序 (optional) (default to undefined)
let nameOrder: string; //等級名稱排序 (optional) (default to undefined)
let levelTypeOrder: string; //等級類型排序 (optional) (default to undefined)
let levelOrder: number; //等級排序 (optional) (default to undefined)
let statusOrder: string; //狀態排序 (optional) (default to undefined)
let createdAtOrder: string; //建立時間排序 (optional) (default to undefined)
let pageSize: number; //頁條數 (optional) (default to undefined)
let pageIndex: number; //頁碼 (optional) (default to undefined)

const { status, data } = await apiInstance.appUserUserLevelGet(
    beginCreatedAt,
    endCreatedAt,
    name,
    levelType,
    level,
    idOrder,
    nameOrder,
    levelTypeOrder,
    levelOrder,
    statusOrder,
    createdAtOrder,
    pageSize,
    pageIndex
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|
| **name** | [**string**] | 等級名稱 | (optional) defaults to undefined|
| **levelType** | [**string**] | 等級類型 | (optional) defaults to undefined|
| **level** | [**number**] | 等級 | (optional) defaults to undefined|
| **idOrder** | [**number**] | 編號排序 | (optional) defaults to undefined|
| **nameOrder** | [**string**] | 等級名稱排序 | (optional) defaults to undefined|
| **levelTypeOrder** | [**string**] | 等級類型排序 | (optional) defaults to undefined|
| **levelOrder** | [**number**] | 等級排序 | (optional) defaults to undefined|
| **statusOrder** | [**string**] | 狀態排序 | (optional) defaults to undefined|
| **createdAtOrder** | [**string**] | 建立時間排序 | (optional) defaults to undefined|
| **pageSize** | [**number**] | 頁條數 | (optional) defaults to undefined|
| **pageIndex** | [**number**] | 頁碼 | (optional) defaults to undefined|


### Return type

**AppUserUserLevelGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **appUserUserLevelIdGet**
> AppUserUserLevelIdGet200Response appUserUserLevelIdGet()

獲取用戶等級管理詳情

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //等級編號 (default to undefined)

const { status, data } = await apiInstance.appUserUserLevelIdGet(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | 等級編號 | defaults to undefined|


### Return type

**AppUserUserLevelIdGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **appUserUserLevelIdPut**
> ResponseResponse appUserUserLevelIdPut(data)

更新用戶等級管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoUserLevelUpdateReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //等級編號 (default to undefined)
let data: DtoUserLevelUpdateReq; //body

const { status, data } = await apiInstance.appUserUserLevelIdPut(
    id,
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoUserLevelUpdateReq**| body | |
| **id** | [**number**] | 等級編號 | defaults to undefined|


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **appUserUserLevelPost**
> AppUserUserCountryCodePost200Response appUserUserLevelPost(data)

新增用戶等級管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoUserLevelInsertReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoUserLevelInsertReq; //body

const { status, data } = await apiInstance.appUserUserLevelPost(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoUserLevelInsertReq**| body | |


### Return type

**AppUserUserCountryCodePost200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **appUserUserOperLogExportPost**
> ResponseResponse appUserUserOperLogExportPost()

導出用戶操作日誌

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let actionType: string; //用戶行為類型 (optional) (default to undefined)
let byType: string; //更新用戶類型 1-app用戶 2-後台用戶 (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)
let trueName: string; //真實姓名 (optional) (default to undefined)
let userName: string; //用戶名稱 (optional) (default to undefined)
let mobile: string; //手機號碼 (optional) (default to undefined)
let email: string; //電子郵件 (optional) (default to undefined)

const { status, data } = await apiInstance.appUserUserOperLogExportPost(
    actionType,
    byType,
    beginCreatedAt,
    endCreatedAt,
    trueName,
    userName,
    mobile,
    email
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **actionType** | [**string**] | 用戶行為類型 | (optional) defaults to undefined|
| **byType** | [**string**] | 更新用戶類型 1-app用戶 2-後台用戶 | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|
| **trueName** | [**string**] | 真實姓名 | (optional) defaults to undefined|
| **userName** | [**string**] | 用戶名稱 | (optional) defaults to undefined|
| **mobile** | [**string**] | 手機號碼 | (optional) defaults to undefined|
| **email** | [**string**] | 電子郵件 | (optional) defaults to undefined|


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **appUserUserOperLogGet**
> AppUserUserOperLogGet200Response appUserUserOperLogGet()

獲取用戶操作日誌分頁列表

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let actionType: string; //用戶行為類型 (optional) (default to undefined)
let byType: string; //更新用戶類型 1-app用戶 2-後台用戶 (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)
let trueName: string; //真實姓名 (optional) (default to undefined)
let userName: string; //用戶名稱 (optional) (default to undefined)
let mobile: string; //手機號碼 (optional) (default to undefined)
let email: string; //電子郵件 (optional) (default to undefined)
let actionTypeOrder: string; //用戶行為類型排序 (optional) (default to undefined)
let byTypeOrder: string; //更新用戶類型排序 (optional) (default to undefined)
let createByOrder: number; //建立者排序 (optional) (default to undefined)
let createdAtOrder: string; //建立時間排序 (optional) (default to undefined)
let idOrder: number; //編號排序 (optional) (default to undefined)
let remarkOrder: string; //備註排序 (optional) (default to undefined)
let statusOrder: string; //狀態排序 (optional) (default to undefined)
let updateByOrder: number; //更新者排序 (optional) (default to undefined)
let updatedAtOrder: string; //更新時間排序 (optional) (default to undefined)
let userIdOrder: number; //用戶編號排序 (optional) (default to undefined)
let pageSize: number; //頁條數 (optional) (default to undefined)
let pageIndex: number; //頁碼 (optional) (default to undefined)

const { status, data } = await apiInstance.appUserUserOperLogGet(
    actionType,
    byType,
    beginCreatedAt,
    endCreatedAt,
    trueName,
    userName,
    mobile,
    email,
    actionTypeOrder,
    byTypeOrder,
    createByOrder,
    createdAtOrder,
    idOrder,
    remarkOrder,
    statusOrder,
    updateByOrder,
    updatedAtOrder,
    userIdOrder,
    pageSize,
    pageIndex
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **actionType** | [**string**] | 用戶行為類型 | (optional) defaults to undefined|
| **byType** | [**string**] | 更新用戶類型 1-app用戶 2-後台用戶 | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|
| **trueName** | [**string**] | 真實姓名 | (optional) defaults to undefined|
| **userName** | [**string**] | 用戶名稱 | (optional) defaults to undefined|
| **mobile** | [**string**] | 手機號碼 | (optional) defaults to undefined|
| **email** | [**string**] | 電子郵件 | (optional) defaults to undefined|
| **actionTypeOrder** | [**string**] | 用戶行為類型排序 | (optional) defaults to undefined|
| **byTypeOrder** | [**string**] | 更新用戶類型排序 | (optional) defaults to undefined|
| **createByOrder** | [**number**] | 建立者排序 | (optional) defaults to undefined|
| **createdAtOrder** | [**string**] | 建立時間排序 | (optional) defaults to undefined|
| **idOrder** | [**number**] | 編號排序 | (optional) defaults to undefined|
| **remarkOrder** | [**string**] | 備註排序 | (optional) defaults to undefined|
| **statusOrder** | [**string**] | 狀態排序 | (optional) defaults to undefined|
| **updateByOrder** | [**number**] | 更新者排序 | (optional) defaults to undefined|
| **updatedAtOrder** | [**string**] | 更新時間排序 | (optional) defaults to undefined|
| **userIdOrder** | [**number**] | 用戶編號排序 | (optional) defaults to undefined|
| **pageSize** | [**number**] | 頁條數 | (optional) defaults to undefined|
| **pageIndex** | [**number**] | 頁碼 | (optional) defaults to undefined|


### Return type

**AppUserUserOperLogGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **appUserUserOperLogIdGet**
> AppUserUserOperLogIdGet200Response appUserUserOperLogIdGet()

獲取用戶操作日誌詳情

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //日誌編號 (default to undefined)

const { status, data } = await apiInstance.appUserUserOperLogIdGet(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | 日誌編號 | defaults to undefined|


### Return type

**AppUserUserOperLogIdGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **appUserUserPost**
> ResponseResponse appUserUserPost(data)

新增用戶管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoUserInsertReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoUserInsertReq; //body

const { status, data } = await apiInstance.appUserUserPost(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoUserInsertReq**| body | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **captchaGet**
> CaptchaGet200Response captchaGet()

獲取圖形驗證碼

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

const { status, data } = await apiInstance.captchaGet();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**CaptchaGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deptDelete**
> ResponseResponse deptDelete(data)

刪除部門管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysDeptDeleteReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysDeptDeleteReq; //內容

const { status, data } = await apiInstance.deptDelete(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysDeptDeleteReq**| 內容 | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deptIdGet**
> DeptIdGet200Response deptIdGet()

獲取部門管理詳情

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //編號 (default to undefined)

const { status, data } = await apiInstance.deptIdGet(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | 編號 | defaults to undefined|


### Return type

**DeptIdGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deptPost**
> AppUserUserCountryCodePost200Response deptPost(data)

新增部門管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysDeptInsertReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysDeptInsertReq; //內容

const { status, data } = await apiInstance.deptPost(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysDeptInsertReq**| 內容 | |


### Return type

**AppUserUserCountryCodePost200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deptPut**
> ResponseResponse deptPut(data)

更新部門管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysDeptUpdateReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysDeptUpdateReq; //內容

const { status, data } = await apiInstance.deptPut(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysDeptUpdateReq**| 內容 | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deptRoleDeptTreeSelectRoleIdGet**
> DeptRoleDeptTreeSelectRoleIdGet200Response deptRoleDeptTreeSelectRoleIdGet()

根據角色獲取部門

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let roleId: number; //角色編號 (default to undefined)

const { status, data } = await apiInstance.deptRoleDeptTreeSelectRoleIdGet(
    roleId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **roleId** | [**number**] | 角色編號 | defaults to undefined|


### Return type

**DeptRoleDeptTreeSelectRoleIdGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **deptTreeGet**
> DeptTreeGet200Response deptTreeGet()

獲取部門管理樹

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let deptName: string; //部門名稱 (optional) (default to undefined)
let parentId: number; //上級部門 (optional) (default to undefined)
let leader: string; //負責人 (optional) (default to undefined)
let phone: string; //手機 (optional) (default to undefined)
let email: string; //郵箱 (optional) (default to undefined)

const { status, data } = await apiInstance.deptTreeGet(
    deptName,
    parentId,
    leader,
    phone,
    email
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **deptName** | [**string**] | 部門名稱 | (optional) defaults to undefined|
| **parentId** | [**number**] | 上級部門 | (optional) defaults to undefined|
| **leader** | [**string**] | 負責人 | (optional) defaults to undefined|
| **phone** | [**string**] | 手機 | (optional) defaults to undefined|
| **email** | [**string**] | 郵箱 | (optional) defaults to undefined|


### Return type

**DeptTreeGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **dictDataDelete**
> ResponseResponse dictDataDelete(data)

刪除字典數據

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysDictDataDeleteReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysDictDataDeleteReq; //內容

const { status, data } = await apiInstance.dictDataDelete(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysDictDataDeleteReq**| 內容 | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **dictDataGet**
> DictDataGet200Response dictDataGet()

獲取字典數據分頁列表

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //編號 (optional) (default to undefined)
let dictLabel: string; //字典標籤 (optional) (default to undefined)
let dictValue: string; //字典鍵值 (optional) (default to undefined)
let dictType: string; //字典類型 (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)
let pageSize: number; //每頁條數 (optional) (default to undefined)
let pageIndex: number; //頁碼 (optional) (default to undefined)

const { status, data } = await apiInstance.dictDataGet(
    id,
    dictLabel,
    dictValue,
    dictType,
    beginCreatedAt,
    endCreatedAt,
    pageSize,
    pageIndex
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | 編號 | (optional) defaults to undefined|
| **dictLabel** | [**string**] | 字典標籤 | (optional) defaults to undefined|
| **dictValue** | [**string**] | 字典鍵值 | (optional) defaults to undefined|
| **dictType** | [**string**] | 字典類型 | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|
| **pageSize** | [**number**] | 每頁條數 | (optional) defaults to undefined|
| **pageIndex** | [**number**] | 頁碼 | (optional) defaults to undefined|


### Return type

**DictDataGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **dictDataIdGet**
> DictDataIdGet200Response dictDataIdGet()

獲取字典數據詳情

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //編號 (default to undefined)

const { status, data } = await apiInstance.dictDataIdGet(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | 編號 | defaults to undefined|


### Return type

**DictDataIdGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **dictDataListGet**
> DictDataListGet200Response dictDataListGet()

獲取字典數據全部列表

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let dictType: string; //字典類型 (optional) (default to undefined)

const { status, data } = await apiInstance.dictDataListGet(
    dictType
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **dictType** | [**string**] | 字典類型 | (optional) defaults to undefined|


### Return type

**DictDataListGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **dictDataPost**
> AppUserUserCountryCodePost200Response dictDataPost(data)

新增字典數據

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysDictDataInsertReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysDictDataInsertReq; //內容

const { status, data } = await apiInstance.dictDataPost(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysDictDataInsertReq**| 內容 | |


### Return type

**AppUserUserCountryCodePost200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **dictDataPut**
> ResponseResponse dictDataPut(data)

更新字典數據

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysDictDataUpdateReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysDictDataUpdateReq; //內容

const { status, data } = await apiInstance.dictDataPut(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysDictDataUpdateReq**| 內容 | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **dictTypeDelete**
> ResponseResponse dictTypeDelete(data)

刪除字典類型

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysDictrDeleteReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysDictrDeleteReq; //內容

const { status, data } = await apiInstance.dictTypeDelete(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysDictrDeleteReq**| 內容 | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **dictTypeExportPost**
> ResponseResponse dictTypeExportPost()

導出字典類型

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let dictName: string; //字典名稱 (optional) (default to undefined)
let dictType: string; //字典類型 (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)

const { status, data } = await apiInstance.dictTypeExportPost(
    dictName,
    dictType,
    beginCreatedAt,
    endCreatedAt
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **dictName** | [**string**] | 字典名稱 | (optional) defaults to undefined|
| **dictType** | [**string**] | 字典類型 | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **dictTypeGet**
> DictTypeGet200Response dictTypeGet()

獲取字典類型分頁列表

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let dictName: string; //字典名稱 (optional) (default to undefined)
let dictType: string; //字典類型 (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)
let idOrder: string; //ID排序 (optional) (default to undefined)
let pageSize: number; //每頁條數 (optional) (default to undefined)
let pageIndex: number; //頁碼 (optional) (default to undefined)

const { status, data } = await apiInstance.dictTypeGet(
    dictName,
    dictType,
    beginCreatedAt,
    endCreatedAt,
    idOrder,
    pageSize,
    pageIndex
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **dictName** | [**string**] | 字典名稱 | (optional) defaults to undefined|
| **dictType** | [**string**] | 字典類型 | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|
| **idOrder** | [**string**] | ID排序 | (optional) defaults to undefined|
| **pageSize** | [**number**] | 每頁條數 | (optional) defaults to undefined|
| **pageIndex** | [**number**] | 頁碼 | (optional) defaults to undefined|


### Return type

**DictTypeGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **dictTypeIdGet**
> DictTypeIdGet200Response dictTypeIdGet()

獲取字典類型詳情

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //編號 (default to undefined)

const { status, data } = await apiInstance.dictTypeIdGet(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | 編號 | defaults to undefined|


### Return type

**DictTypeIdGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **dictTypeListGet**
> DictTypeListGet200Response dictTypeListGet()

獲取字典類型全部列表

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

const { status, data } = await apiInstance.dictTypeListGet();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**DictTypeListGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **dictTypePost**
> AppUserUserCountryCodePost200Response dictTypePost(data)

新增字典類型

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysDictTypeInsertReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysDictTypeInsertReq; //內容

const { status, data } = await apiInstance.dictTypePost(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysDictTypeInsertReq**| 內容 | |


### Return type

**AppUserUserCountryCodePost200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **dictTypePut**
> ResponseResponse dictTypePut(data)

更新字典類型

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysDictTypeUpdateReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysDictTypeUpdateReq; //內容

const { status, data } = await apiInstance.dictTypePut(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysDictTypeUpdateReq**| 內容 | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **loginPost**
> LoginPost200Response loginPost(data)

登入系統

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoLoginReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoLoginReq; //body

const { status, data } = await apiInstance.loginPost(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoLoginReq**| body | |


### Return type

**LoginPost200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **logoutPost**
> ResponseResponse logoutPost()

退出系統

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

const { status, data } = await apiInstance.logoutPost();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **menuDelete**
> ResponseResponse menuDelete(data)

刪除菜單管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysMenuDeleteReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysMenuDeleteReq; //內容

const { status, data } = await apiInstance.menuDelete(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysMenuDeleteReq**| 內容 | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **menuIdGet**
> MenuIdGet200Response menuIdGet()

獲取菜單管理詳情

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //編號 (default to undefined)

const { status, data } = await apiInstance.menuIdGet(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | 編號 | defaults to undefined|


### Return type

**MenuIdGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **menuPost**
> AppUserUserCountryCodePost200Response menuPost(data)

新增菜單管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysMenuInsertReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysMenuInsertReq; //內容

const { status, data } = await apiInstance.menuPost(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysMenuInsertReq**| 內容 | |


### Return type

**AppUserUserCountryCodePost200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **menuPut**
> ResponseResponse menuPut(data)

更新菜單管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysMenuUpdateReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysMenuUpdateReq; //內容

const { status, data } = await apiInstance.menuPut(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysMenuUpdateReq**| 內容 | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **menuRoleGet**
> MenuRoleGet200Response menuRoleGet()

根據角色獲取菜單

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

const { status, data } = await apiInstance.menuRoleGet();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**MenuRoleGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **menuRoleMenuTreeSelectRoleIdGet**
> MenuRoleMenuTreeSelectRoleIdGet200Response menuRoleMenuTreeSelectRoleIdGet()

獲取全部菜單以及選中的菜單編號

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let roleId: number; //角色編號 (default to undefined)

const { status, data } = await apiInstance.menuRoleMenuTreeSelectRoleIdGet(
    roleId
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **roleId** | [**number**] | 角色編號 | defaults to undefined|


### Return type

**MenuRoleMenuTreeSelectRoleIdGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **menuTreeGet**
> MenuRoleGet200Response menuTreeGet()

獲取菜單管理樹

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: string; //菜單編號 (optional) (default to undefined)
let title: string; //菜單名稱 (optional) (default to undefined)
let path: string; //路由地址 (optional) (default to undefined)
let isHidden: string; //顯示狀態 (optional) (default to undefined)

const { status, data } = await apiInstance.menuTreeGet(
    id,
    title,
    path,
    isHidden
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**string**] | 菜單編號 | (optional) defaults to undefined|
| **title** | [**string**] | 菜單名稱 | (optional) defaults to undefined|
| **path** | [**string**] | 路由地址 | (optional) defaults to undefined|
| **isHidden** | [**string**] | 顯示狀態 | (optional) defaults to undefined|


### Return type

**MenuRoleGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **metricsGet**
> string metricsGet()

獲取Prometheus指標

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

const { status, data } = await apiInstance.metricsGet();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | Prometheus metrics |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **monitorGet**
> MonitorGet200Response monitorGet()

獲取伺服器信息

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

const { status, data } = await apiInstance.monitorGet();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**MonitorGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **pingGet**
> string pingGet()

Ping測試

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

const { status, data } = await apiInstance.pingGet();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**string**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | pong |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **pluginsContentContentAnnouncementDelete**
> ResponseResponse pluginsContentContentAnnouncementDelete(data)

刪除公告管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoContentAnnouncementDeleteReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoContentAnnouncementDeleteReq; //body

const { status, data } = await apiInstance.pluginsContentContentAnnouncementDelete(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoContentAnnouncementDeleteReq**| body | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **pluginsContentContentAnnouncementExportPost**
> ResponseResponse pluginsContentContentAnnouncementExportPost()

導出公告管理

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let title: string; //標題 (optional) (default to undefined)
let status: string; //狀態（0正常 1刪除 2停用 3凍結） (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)

const { status, data } = await apiInstance.pluginsContentContentAnnouncementExportPost(
    title,
    status,
    beginCreatedAt,
    endCreatedAt
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **title** | [**string**] | 標題 | (optional) defaults to undefined|
| **status** | [**string**] | 狀態（0正常 1刪除 2停用 3凍結） | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **pluginsContentContentAnnouncementGet**
> PluginsContentContentAnnouncementGet200Response pluginsContentContentAnnouncementGet()

獲取公告管理分頁列表

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let title: string; //標題 (optional) (default to undefined)
let status: string; //狀態（0正常 1刪除 2停用 3凍結） (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)
let idOrder: number; //編號排序 (optional) (default to undefined)
let titleOrder: string; //標題排序 (optional) (default to undefined)
let contentOrder: string; //內容排序 (optional) (default to undefined)
let numOrder: number; //閱讀次數排序 (optional) (default to undefined)
let statusOrder: string; //狀態排序 (optional) (default to undefined)
let createdAtOrder: string; //建立時間排序 (optional) (default to undefined)
let pageSize: number; //頁條數 (optional) (default to undefined)
let pageIndex: number; //頁碼 (optional) (default to undefined)

const { status, data } = await apiInstance.pluginsContentContentAnnouncementGet(
    title,
    status,
    beginCreatedAt,
    endCreatedAt,
    idOrder,
    titleOrder,
    contentOrder,
    numOrder,
    statusOrder,
    createdAtOrder,
    pageSize,
    pageIndex
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **title** | [**string**] | 標題 | (optional) defaults to undefined|
| **status** | [**string**] | 狀態（0正常 1刪除 2停用 3凍結） | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|
| **idOrder** | [**number**] | 編號排序 | (optional) defaults to undefined|
| **titleOrder** | [**string**] | 標題排序 | (optional) defaults to undefined|
| **contentOrder** | [**string**] | 內容排序 | (optional) defaults to undefined|
| **numOrder** | [**number**] | 閱讀次數排序 | (optional) defaults to undefined|
| **statusOrder** | [**string**] | 狀態排序 | (optional) defaults to undefined|
| **createdAtOrder** | [**string**] | 建立時間排序 | (optional) defaults to undefined|
| **pageSize** | [**number**] | 頁條數 | (optional) defaults to undefined|
| **pageIndex** | [**number**] | 頁碼 | (optional) defaults to undefined|


### Return type

**PluginsContentContentAnnouncementGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **pluginsContentContentAnnouncementIdGet**
> PluginsContentContentAnnouncementIdGet200Response pluginsContentContentAnnouncementIdGet()

獲取公告管理詳情

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //公告編號 (default to undefined)

const { status, data } = await apiInstance.pluginsContentContentAnnouncementIdGet(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | 公告編號 | defaults to undefined|


### Return type

**PluginsContentContentAnnouncementIdGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **pluginsContentContentAnnouncementIdPut**
> ResponseResponse pluginsContentContentAnnouncementIdPut(data)

更新公告管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoContentAnnouncementUpdateReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //公告編號 (default to undefined)
let data: DtoContentAnnouncementUpdateReq; //body

const { status, data } = await apiInstance.pluginsContentContentAnnouncementIdPut(
    id,
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoContentAnnouncementUpdateReq**| body | |
| **id** | [**number**] | 公告編號 | defaults to undefined|


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **pluginsContentContentAnnouncementPost**
> AppUserUserCountryCodePost200Response pluginsContentContentAnnouncementPost(data)

新增公告管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoContentAnnouncementInsertReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoContentAnnouncementInsertReq; //body

const { status, data } = await apiInstance.pluginsContentContentAnnouncementPost(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoContentAnnouncementInsertReq**| body | |


### Return type

**AppUserUserCountryCodePost200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **pluginsContentContentArticleDelete**
> ResponseResponse pluginsContentContentArticleDelete(data)

刪除文章管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoContentArticleDeleteReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoContentArticleDeleteReq; //body

const { status, data } = await apiInstance.pluginsContentContentArticleDelete(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoContentArticleDeleteReq**| body | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **pluginsContentContentArticleExportPost**
> ResponseResponse pluginsContentContentArticleExportPost()

導出文章管理

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //文章編號 (optional) (default to undefined)
let cateId: number; //分類編號 (optional) (default to undefined)
let name: string; //標題 (optional) (default to undefined)
let status: string; //狀態（1-正常 2-異常） (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)

const { status, data } = await apiInstance.pluginsContentContentArticleExportPost(
    id,
    cateId,
    name,
    status,
    beginCreatedAt,
    endCreatedAt
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | 文章編號 | (optional) defaults to undefined|
| **cateId** | [**number**] | 分類編號 | (optional) defaults to undefined|
| **name** | [**string**] | 標題 | (optional) defaults to undefined|
| **status** | [**string**] | 狀態（1-正常 2-異常） | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **pluginsContentContentArticleGet**
> PluginsContentContentArticleGet200Response pluginsContentContentArticleGet()

獲取文章管理分頁列表

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //文章編號 (optional) (default to undefined)
let cateId: number; //分類編號 (optional) (default to undefined)
let name: string; //標題 (optional) (default to undefined)
let status: string; //狀態（1-正常 2-異常） (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)
let idOrder: number; //編號排序 (optional) (default to undefined)
let cateIdOrder: number; //分類編號排序 (optional) (default to undefined)
let nameOrder: string; //標題排序 (optional) (default to undefined)
let contentOrder: string; //內容排序 (optional) (default to undefined)
let statusOrder: string; //狀態排序 (optional) (default to undefined)
let createdAtOrder: string; //建立時間排序 (optional) (default to undefined)
let pageSize: number; //頁條數 (optional) (default to undefined)
let pageIndex: number; //頁碼 (optional) (default to undefined)

const { status, data } = await apiInstance.pluginsContentContentArticleGet(
    id,
    cateId,
    name,
    status,
    beginCreatedAt,
    endCreatedAt,
    idOrder,
    cateIdOrder,
    nameOrder,
    contentOrder,
    statusOrder,
    createdAtOrder,
    pageSize,
    pageIndex
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | 文章編號 | (optional) defaults to undefined|
| **cateId** | [**number**] | 分類編號 | (optional) defaults to undefined|
| **name** | [**string**] | 標題 | (optional) defaults to undefined|
| **status** | [**string**] | 狀態（1-正常 2-異常） | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|
| **idOrder** | [**number**] | 編號排序 | (optional) defaults to undefined|
| **cateIdOrder** | [**number**] | 分類編號排序 | (optional) defaults to undefined|
| **nameOrder** | [**string**] | 標題排序 | (optional) defaults to undefined|
| **contentOrder** | [**string**] | 內容排序 | (optional) defaults to undefined|
| **statusOrder** | [**string**] | 狀態排序 | (optional) defaults to undefined|
| **createdAtOrder** | [**string**] | 建立時間排序 | (optional) defaults to undefined|
| **pageSize** | [**number**] | 頁條數 | (optional) defaults to undefined|
| **pageIndex** | [**number**] | 頁碼 | (optional) defaults to undefined|


### Return type

**PluginsContentContentArticleGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **pluginsContentContentArticleIdGet**
> PluginsContentContentArticleIdGet200Response pluginsContentContentArticleIdGet()

獲取文章管理詳情

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //文章編號 (default to undefined)

const { status, data } = await apiInstance.pluginsContentContentArticleIdGet(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | 文章編號 | defaults to undefined|


### Return type

**PluginsContentContentArticleIdGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **pluginsContentContentArticleIdPut**
> ResponseResponse pluginsContentContentArticleIdPut(data)

更新文章管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoContentArticleUpdateReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //文章編號 (default to undefined)
let data: DtoContentArticleUpdateReq; //body

const { status, data } = await apiInstance.pluginsContentContentArticleIdPut(
    id,
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoContentArticleUpdateReq**| body | |
| **id** | [**number**] | 文章編號 | defaults to undefined|


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **pluginsContentContentArticlePost**
> AppUserUserCountryCodePost200Response pluginsContentContentArticlePost(data)

新增文章管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoContentArticleInsertReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoContentArticleInsertReq; //body

const { status, data } = await apiInstance.pluginsContentContentArticlePost(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoContentArticleInsertReq**| body | |


### Return type

**AppUserUserCountryCodePost200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **pluginsContentContentCategoryDelete**
> ResponseResponse pluginsContentContentCategoryDelete(data)

刪除內容分類管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoContentCategoryDeleteReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoContentCategoryDeleteReq; //body

const { status, data } = await apiInstance.pluginsContentContentCategoryDelete(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoContentCategoryDeleteReq**| body | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **pluginsContentContentCategoryExportPost**
> ResponseResponse pluginsContentContentCategoryExportPost()

導出內容分類管理

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //編號 (optional) (default to undefined)
let name: string; //分類名稱 (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)

const { status, data } = await apiInstance.pluginsContentContentCategoryExportPost(
    id,
    name,
    beginCreatedAt,
    endCreatedAt
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | 編號 | (optional) defaults to undefined|
| **name** | [**string**] | 分類名稱 | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **pluginsContentContentCategoryGet**
> PluginsContentContentCategoryGet200Response pluginsContentContentCategoryGet()

獲取內容分類管理分頁列表

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //編號 (optional) (default to undefined)
let name: string; //分類名稱 (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)
let idOrder: number; //編號排序 (optional) (default to undefined)
let nameOrder: string; //分類名稱排序 (optional) (default to undefined)
let statusOrder: string; //狀態排序 (optional) (default to undefined)
let createdAtOrder: string; //建立時間排序 (optional) (default to undefined)
let pageSize: number; //頁條數 (optional) (default to undefined)
let pageIndex: number; //頁碼 (optional) (default to undefined)

const { status, data } = await apiInstance.pluginsContentContentCategoryGet(
    id,
    name,
    beginCreatedAt,
    endCreatedAt,
    idOrder,
    nameOrder,
    statusOrder,
    createdAtOrder,
    pageSize,
    pageIndex
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | 編號 | (optional) defaults to undefined|
| **name** | [**string**] | 分類名稱 | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|
| **idOrder** | [**number**] | 編號排序 | (optional) defaults to undefined|
| **nameOrder** | [**string**] | 分類名稱排序 | (optional) defaults to undefined|
| **statusOrder** | [**string**] | 狀態排序 | (optional) defaults to undefined|
| **createdAtOrder** | [**string**] | 建立時間排序 | (optional) defaults to undefined|
| **pageSize** | [**number**] | 頁條數 | (optional) defaults to undefined|
| **pageIndex** | [**number**] | 頁碼 | (optional) defaults to undefined|


### Return type

**PluginsContentContentCategoryGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **pluginsContentContentCategoryIdGet**
> PluginsContentContentCategoryIdGet200Response pluginsContentContentCategoryIdGet()

獲取內容分類管理詳情

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //分類編號 (default to undefined)

const { status, data } = await apiInstance.pluginsContentContentCategoryIdGet(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | 分類編號 | defaults to undefined|


### Return type

**PluginsContentContentCategoryIdGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **pluginsContentContentCategoryIdPut**
> ResponseResponse pluginsContentContentCategoryIdPut(data)

更新內容分類管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoContentCategoryUpdateReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //分類編號 (default to undefined)
let data: DtoContentCategoryUpdateReq; //body

const { status, data } = await apiInstance.pluginsContentContentCategoryIdPut(
    id,
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoContentCategoryUpdateReq**| body | |
| **id** | [**number**] | 分類編號 | defaults to undefined|


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **pluginsContentContentCategoryPost**
> AppUserUserCountryCodePost200Response pluginsContentContentCategoryPost(data)

新增內容分類管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoContentCategoryInsertReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoContentCategoryInsertReq; //body

const { status, data } = await apiInstance.pluginsContentContentCategoryPost(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoContentCategoryInsertReq**| body | |


### Return type

**AppUserUserCountryCodePost200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **pluginsMsgMsgCodeGet**
> PluginsMsgMsgCodeGet200Response pluginsMsgMsgCodeGet()

獲取驗證碼管理分頁列表

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let userId: number; //用戶編號 (optional) (default to undefined)
let codeType: string; //驗證碼類型 1-郵箱；2-短信 (optional) (default to undefined)
let status: string; //驗證碼狀態 1-發送成功 2-發送失敗 (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)
let idOrder: number; //編號排序 (optional) (default to undefined)
let userIdOrder: number; //用戶編號排序 (optional) (default to undefined)
let codeTypeOrder: string; //驗證碼類型排序 (optional) (default to undefined)
let statusOrder: string; //狀態排序 (optional) (default to undefined)
let createdAtOrder: string; //建立時間排序 (optional) (default to undefined)
let pageSize: number; //頁條數 (optional) (default to undefined)
let pageIndex: number; //頁碼 (optional) (default to undefined)

const { status, data } = await apiInstance.pluginsMsgMsgCodeGet(
    userId,
    codeType,
    status,
    beginCreatedAt,
    endCreatedAt,
    idOrder,
    userIdOrder,
    codeTypeOrder,
    statusOrder,
    createdAtOrder,
    pageSize,
    pageIndex
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **userId** | [**number**] | 用戶編號 | (optional) defaults to undefined|
| **codeType** | [**string**] | 驗證碼類型 1-郵箱；2-短信 | (optional) defaults to undefined|
| **status** | [**string**] | 驗證碼狀態 1-發送成功 2-發送失敗 | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|
| **idOrder** | [**number**] | 編號排序 | (optional) defaults to undefined|
| **userIdOrder** | [**number**] | 用戶編號排序 | (optional) defaults to undefined|
| **codeTypeOrder** | [**string**] | 驗證碼類型排序 | (optional) defaults to undefined|
| **statusOrder** | [**string**] | 狀態排序 | (optional) defaults to undefined|
| **createdAtOrder** | [**string**] | 建立時間排序 | (optional) defaults to undefined|
| **pageSize** | [**number**] | 頁條數 | (optional) defaults to undefined|
| **pageIndex** | [**number**] | 頁碼 | (optional) defaults to undefined|


### Return type

**PluginsMsgMsgCodeGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **pluginsMsgMsgCodeIdGet**
> PluginsMsgMsgCodeIdGet200Response pluginsMsgMsgCodeIdGet()

獲取驗證碼管理詳情

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //驗證碼編號 (default to undefined)

const { status, data } = await apiInstance.pluginsMsgMsgCodeIdGet(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | 驗證碼編號 | defaults to undefined|


### Return type

**PluginsMsgMsgCodeIdGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **postDelete**
> ResponseResponse postDelete(data)

刪除崗位管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysPostDeleteReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysPostDeleteReq; //body

const { status, data } = await apiInstance.postDelete(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysPostDeleteReq**| body | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **postExportPost**
> ResponseResponse postExportPost()

導出崗位管理

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let postName: string; //崗位名稱 (optional) (default to undefined)
let postCode: string; //崗位代碼 (optional) (default to undefined)
let status: string; //狀態 (optional) (default to undefined)

const { status, data } = await apiInstance.postExportPost(
    postName,
    postCode,
    status
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **postName** | [**string**] | 崗位名稱 | (optional) defaults to undefined|
| **postCode** | [**string**] | 崗位代碼 | (optional) defaults to undefined|
| **status** | [**string**] | 狀態 | (optional) defaults to undefined|


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **postGet**
> PostGet200Response postGet()

獲取崗位管理分頁列表

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let postName: string; //崗位名稱 (optional) (default to undefined)
let postCode: string; //崗位代碼 (optional) (default to undefined)
let status: string; //狀態 (optional) (default to undefined)
let pageSize: number; //頁條數 (optional) (default to undefined)
let pageIndex: number; //頁碼 (optional) (default to undefined)

const { status, data } = await apiInstance.postGet(
    postName,
    postCode,
    status,
    pageSize,
    pageIndex
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **postName** | [**string**] | 崗位名稱 | (optional) defaults to undefined|
| **postCode** | [**string**] | 崗位代碼 | (optional) defaults to undefined|
| **status** | [**string**] | 狀態 | (optional) defaults to undefined|
| **pageSize** | [**number**] | 頁條數 | (optional) defaults to undefined|
| **pageIndex** | [**number**] | 頁碼 | (optional) defaults to undefined|


### Return type

**PostGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **postIdGet**
> PostIdGet200Response postIdGet()

獲取崗位管理詳情

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //id (default to undefined)

const { status, data } = await apiInstance.postIdGet(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | id | defaults to undefined|


### Return type

**PostIdGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **postListGet**
> PostListGet200Response postListGet()

獲取崗位管理全部列表

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let postName: string; //崗位名稱 (optional) (default to undefined)
let postCode: string; //崗位代碼 (optional) (default to undefined)
let status: string; //狀態 (optional) (default to undefined)

const { status, data } = await apiInstance.postListGet(
    postName,
    postCode,
    status
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **postName** | [**string**] | 崗位名稱 | (optional) defaults to undefined|
| **postCode** | [**string**] | 崗位代碼 | (optional) defaults to undefined|
| **status** | [**string**] | 狀態 | (optional) defaults to undefined|


### Return type

**PostListGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **postPost**
> AppUserUserCountryCodePost200Response postPost(data)

新增崗位管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysPostInsertReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysPostInsertReq; //body

const { status, data } = await apiInstance.postPost(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysPostInsertReq**| body | |


### Return type

**AppUserUserCountryCodePost200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **postPut**
> ResponseResponse postPut(data)

更新崗位管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysPostUpdateReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysPostUpdateReq; //body

const { status, data } = await apiInstance.postPut(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysPostUpdateReq**| body | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **roleDataScopePut**
> ResponseResponse roleDataScopePut(data)

更新角色管理數據權限

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoRoleDataScopeReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoRoleDataScopeReq; //body

const { status, data } = await apiInstance.roleDataScopePut(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoRoleDataScopeReq**| body | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **roleDelete**
> RoleDelete200Response roleDelete(data)

刪除角色管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysRoleDeleteReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysRoleDeleteReq; //body

const { status, data } = await apiInstance.roleDelete(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysRoleDeleteReq**| body | |


### Return type

**RoleDelete200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **roleGet**
> RoleGet200Response roleGet()

獲取角色管理分頁列表

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let roleName: string; //角色名稱 (optional) (default to undefined)
let status: string; //狀態 (optional) (default to undefined)
let roleKey: string; //角色代碼 (optional) (default to undefined)
let pageSize: number; //頁條數 (optional) (default to undefined)
let pageIndex: number; //頁碼 (optional) (default to undefined)

const { status, data } = await apiInstance.roleGet(
    roleName,
    status,
    roleKey,
    pageSize,
    pageIndex
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **roleName** | [**string**] | 角色名稱 | (optional) defaults to undefined|
| **status** | [**string**] | 狀態 | (optional) defaults to undefined|
| **roleKey** | [**string**] | 角色代碼 | (optional) defaults to undefined|
| **pageSize** | [**number**] | 頁條數 | (optional) defaults to undefined|
| **pageIndex** | [**number**] | 頁碼 | (optional) defaults to undefined|


### Return type

**RoleGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **roleIdGet**
> RoleIdGet200Response roleIdGet()

獲取角色管理詳情

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //id (default to undefined)

const { status, data } = await apiInstance.roleIdGet(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | id | defaults to undefined|


### Return type

**RoleIdGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **roleListGet**
> RoleListGet200Response roleListGet()

獲取角色管理全部列表

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let roleName: string; //角色名稱 (optional) (default to undefined)
let status: string; //狀態 (optional) (default to undefined)
let roleKey: string; //角色代碼 (optional) (default to undefined)

const { status, data } = await apiInstance.roleListGet(
    roleName,
    status,
    roleKey
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **roleName** | [**string**] | 角色名稱 | (optional) defaults to undefined|
| **status** | [**string**] | 狀態 | (optional) defaults to undefined|
| **roleKey** | [**string**] | 角色代碼 | (optional) defaults to undefined|


### Return type

**RoleListGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **rolePost**
> AppUserUserCountryCodePost200Response rolePost(data)

新增角色管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysRoleInsertReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysRoleInsertReq; //body

const { status, data } = await apiInstance.rolePost(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysRoleInsertReq**| body | |


### Return type

**AppUserUserCountryCodePost200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **rolePut**
> ResponseResponse rolePut(data)

更新角色管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysRoleUpdateReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysRoleUpdateReq; //body

const { status, data } = await apiInstance.rolePut(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysRoleUpdateReq**| body | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **roleStatusPut**
> RoleStatusPut200Response roleStatusPut(data)

更新角色管理狀態

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoUpdateStatusReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoUpdateStatusReq; //body

const { status, data } = await apiInstance.roleStatusPut(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoUpdateStatusReq**| body | |


### Return type

**RoleStatusPut200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysApiDelete**
> ResponseResponse sysApiDelete(data)

刪除接口管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysApiDeleteReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysApiDeleteReq; //內容

const { status, data } = await apiInstance.sysApiDelete(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysApiDeleteReq**| 內容 | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysApiExportPost**
> ResponseResponse sysApiExportPost()

導出接口管理

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let description: string; //功能描述 (optional) (default to undefined)
let path: string; //地址 (optional) (default to undefined)
let method: string; //請求方法 (optional) (default to undefined)
let apiType: string; //接口類型 (optional) (default to undefined)
let apiTypes: Array<string>; //接口類型(多選) (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)
let descriptionOrder: string; //描述排序 (optional) (default to undefined)
let pathOrder: string; //地址排序 (optional) (default to undefined)
let createdAtOrder: string; //建立時間排序 (optional) (default to undefined)
let pageSize: number; //每頁條數 (optional) (default to undefined)
let pageIndex: number; //頁碼 (optional) (default to undefined)

const { status, data } = await apiInstance.sysApiExportPost(
    description,
    path,
    method,
    apiType,
    apiTypes,
    beginCreatedAt,
    endCreatedAt,
    descriptionOrder,
    pathOrder,
    createdAtOrder,
    pageSize,
    pageIndex
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **description** | [**string**] | 功能描述 | (optional) defaults to undefined|
| **path** | [**string**] | 地址 | (optional) defaults to undefined|
| **method** | [**string**] | 請求方法 | (optional) defaults to undefined|
| **apiType** | [**string**] | 接口類型 | (optional) defaults to undefined|
| **apiTypes** | **Array&lt;string&gt;** | 接口類型(多選) | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|
| **descriptionOrder** | [**string**] | 描述排序 | (optional) defaults to undefined|
| **pathOrder** | [**string**] | 地址排序 | (optional) defaults to undefined|
| **createdAtOrder** | [**string**] | 建立時間排序 | (optional) defaults to undefined|
| **pageSize** | [**number**] | 每頁條數 | (optional) defaults to undefined|
| **pageIndex** | [**number**] | 頁碼 | (optional) defaults to undefined|


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysApiGet**
> SysApiGet200Response sysApiGet()

獲取接口管理分頁列表

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let description: string; //功能描述 (optional) (default to undefined)
let path: string; //地址 (optional) (default to undefined)
let method: string; //請求方法 (optional) (default to undefined)
let apiType: string; //接口類型 (optional) (default to undefined)
let apiTypes: Array<string>; //接口類型(多選) (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)
let descriptionOrder: string; //描述排序 (optional) (default to undefined)
let pathOrder: string; //地址排序 (optional) (default to undefined)
let createdAtOrder: string; //建立時間排序 (optional) (default to undefined)
let pageSize: number; //每頁條數 (optional) (default to undefined)
let pageIndex: number; //頁碼 (optional) (default to undefined)

const { status, data } = await apiInstance.sysApiGet(
    description,
    path,
    method,
    apiType,
    apiTypes,
    beginCreatedAt,
    endCreatedAt,
    descriptionOrder,
    pathOrder,
    createdAtOrder,
    pageSize,
    pageIndex
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **description** | [**string**] | 功能描述 | (optional) defaults to undefined|
| **path** | [**string**] | 地址 | (optional) defaults to undefined|
| **method** | [**string**] | 請求方法 | (optional) defaults to undefined|
| **apiType** | [**string**] | 接口類型 | (optional) defaults to undefined|
| **apiTypes** | **Array&lt;string&gt;** | 接口類型(多選) | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|
| **descriptionOrder** | [**string**] | 描述排序 | (optional) defaults to undefined|
| **pathOrder** | [**string**] | 地址排序 | (optional) defaults to undefined|
| **createdAtOrder** | [**string**] | 建立時間排序 | (optional) defaults to undefined|
| **pageSize** | [**number**] | 每頁條數 | (optional) defaults to undefined|
| **pageIndex** | [**number**] | 頁碼 | (optional) defaults to undefined|


### Return type

**SysApiGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysApiIdGet**
> SysApiIdGet200Response sysApiIdGet()

獲取接口管理詳情

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //編號 (default to undefined)

const { status, data } = await apiInstance.sysApiIdGet(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | 編號 | defaults to undefined|


### Return type

**SysApiIdGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysApiListGet**
> SysApiListGet200Response sysApiListGet()

獲取接口管理全部列表

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let description: string; //功能描述 (optional) (default to undefined)
let path: string; //地址 (optional) (default to undefined)
let method: string; //請求方法 (optional) (default to undefined)
let apiType: string; //接口類型 (optional) (default to undefined)
let apiTypes: Array<string>; //接口類型(多選) (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)
let descriptionOrder: string; //描述排序 (optional) (default to undefined)
let pathOrder: string; //地址排序 (optional) (default to undefined)
let createdAtOrder: string; //建立時間排序 (optional) (default to undefined)
let pageSize: number; //每頁條數 (optional) (default to undefined)
let pageIndex: number; //頁碼 (optional) (default to undefined)

const { status, data } = await apiInstance.sysApiListGet(
    description,
    path,
    method,
    apiType,
    apiTypes,
    beginCreatedAt,
    endCreatedAt,
    descriptionOrder,
    pathOrder,
    createdAtOrder,
    pageSize,
    pageIndex
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **description** | [**string**] | 功能描述 | (optional) defaults to undefined|
| **path** | [**string**] | 地址 | (optional) defaults to undefined|
| **method** | [**string**] | 請求方法 | (optional) defaults to undefined|
| **apiType** | [**string**] | 接口類型 | (optional) defaults to undefined|
| **apiTypes** | **Array&lt;string&gt;** | 接口類型(多選) | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|
| **descriptionOrder** | [**string**] | 描述排序 | (optional) defaults to undefined|
| **pathOrder** | [**string**] | 地址排序 | (optional) defaults to undefined|
| **createdAtOrder** | [**string**] | 建立時間排序 | (optional) defaults to undefined|
| **pageSize** | [**number**] | 每頁條數 | (optional) defaults to undefined|
| **pageIndex** | [**number**] | 頁碼 | (optional) defaults to undefined|


### Return type

**SysApiListGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysApiPut**
> ResponseResponse sysApiPut(data)

更新接口管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysApiUpdateReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysApiUpdateReq; //內容

const { status, data } = await apiInstance.sysApiPut(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysApiUpdateReq**| 內容 | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysApiSyncPost**
> ResponseResponse sysApiSyncPost()

同步接口數據

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

const { status, data } = await apiInstance.sysApiSyncPost();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysConfigByKeyConfigKeyGet**
> SysConfigByKeyConfigKeyGet200Response sysConfigByKeyConfigKeyGet()

根據Key獲取配置值

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let configKey: string; //鍵值 (default to undefined)

const { status, data } = await apiInstance.sysConfigByKeyConfigKeyGet(
    configKey
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **configKey** | [**string**] | 鍵值 | defaults to undefined|


### Return type

**SysConfigByKeyConfigKeyGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysConfigDelete**
> ResponseResponse sysConfigDelete(data)

刪除配置管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysConfigDeleteReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysConfigDeleteReq; //內容

const { status, data } = await apiInstance.sysConfigDelete(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysConfigDeleteReq**| 內容 | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysConfigExportPost**
> ResponseResponse sysConfigExportPost()

導出配置管理

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let configName: string; //名稱 (optional) (default to undefined)
let configKey: string; //鍵值 (optional) (default to undefined)
let configType: string; //類型 (optional) (default to undefined)
let isFrontend: string; //是否前端 (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)

const { status, data } = await apiInstance.sysConfigExportPost(
    configName,
    configKey,
    configType,
    isFrontend,
    beginCreatedAt,
    endCreatedAt
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **configName** | [**string**] | 名稱 | (optional) defaults to undefined|
| **configKey** | [**string**] | 鍵值 | (optional) defaults to undefined|
| **configType** | [**string**] | 類型 | (optional) defaults to undefined|
| **isFrontend** | [**string**] | 是否前端 | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysConfigGet**
> SysConfigGet200Response sysConfigGet()

獲取配置管理分頁列表

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let configName: string; //名稱 (optional) (default to undefined)
let configKey: string; //鍵值 (optional) (default to undefined)
let configType: string; //類型 (optional) (default to undefined)
let isFrontend: string; //是否前端 (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)
let idOrder: string; //ID排序 (optional) (default to undefined)
let configNameOrder: string; //名稱排序 (optional) (default to undefined)
let configKeyOrder: string; //鍵值排序 (optional) (default to undefined)
let configTypeOrder: string; //類型排序 (optional) (default to undefined)
let createdAtOrder: string; //建立時間排序 (optional) (default to undefined)
let pageSize: number; //每頁條數 (optional) (default to undefined)
let pageIndex: number; //頁碼 (optional) (default to undefined)

const { status, data } = await apiInstance.sysConfigGet(
    configName,
    configKey,
    configType,
    isFrontend,
    beginCreatedAt,
    endCreatedAt,
    idOrder,
    configNameOrder,
    configKeyOrder,
    configTypeOrder,
    createdAtOrder,
    pageSize,
    pageIndex
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **configName** | [**string**] | 名稱 | (optional) defaults to undefined|
| **configKey** | [**string**] | 鍵值 | (optional) defaults to undefined|
| **configType** | [**string**] | 類型 | (optional) defaults to undefined|
| **isFrontend** | [**string**] | 是否前端 | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|
| **idOrder** | [**string**] | ID排序 | (optional) defaults to undefined|
| **configNameOrder** | [**string**] | 名稱排序 | (optional) defaults to undefined|
| **configKeyOrder** | [**string**] | 鍵值排序 | (optional) defaults to undefined|
| **configTypeOrder** | [**string**] | 類型排序 | (optional) defaults to undefined|
| **createdAtOrder** | [**string**] | 建立時間排序 | (optional) defaults to undefined|
| **pageSize** | [**number**] | 每頁條數 | (optional) defaults to undefined|
| **pageIndex** | [**number**] | 頁碼 | (optional) defaults to undefined|


### Return type

**SysConfigGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysConfigIdGet**
> SysConfigIdGet200Response sysConfigIdGet()

獲取配置管理詳情

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //編號 (default to undefined)

const { status, data } = await apiInstance.sysConfigIdGet(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | 編號 | defaults to undefined|


### Return type

**SysConfigIdGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysConfigPost**
> AppUserUserCountryCodePost200Response sysConfigPost(data)

新增配置管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysConfigInsertReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysConfigInsertReq; //內容

const { status, data } = await apiInstance.sysConfigPost(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysConfigInsertReq**| 內容 | |


### Return type

**AppUserUserCountryCodePost200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysConfigPut**
> ResponseResponse sysConfigPut(data)

更新配置管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysConfigUpdateReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysConfigUpdateReq; //內容

const { status, data } = await apiInstance.sysConfigPut(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysConfigUpdateReq**| 內容 | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysGenTablesDbTablesGet**
> SysGenTablesDbTablesGet200Response sysGenTablesDbTablesGet()

獲取表管理的DB表分頁列表

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let tableName: string; //表名稱 (optional) (default to undefined)
let tableComment: string; //表描述 (optional) (default to undefined)
let pageSize: number; //每頁條數 (optional) (default to undefined)
let pageIndex: number; //頁碼 (optional) (default to undefined)

const { status, data } = await apiInstance.sysGenTablesDbTablesGet(
    tableName,
    tableComment,
    pageSize,
    pageIndex
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **tableName** | [**string**] | 表名稱 | (optional) defaults to undefined|
| **tableComment** | [**string**] | 表描述 | (optional) defaults to undefined|
| **pageSize** | [**number**] | 每頁條數 | (optional) defaults to undefined|
| **pageIndex** | [**number**] | 頁碼 | (optional) defaults to undefined|


### Return type

**SysGenTablesDbTablesGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysGenTablesDelete**
> ResponseResponse sysGenTablesDelete(data)

刪除表管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysGenTableDeleteReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysGenTableDeleteReq; //內容

const { status, data } = await apiInstance.sysGenTablesDelete(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysGenTableDeleteReq**| 內容 | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysGenTablesDownloadPost**
> ResponseResponse sysGenTablesDownloadPost(data)

表管理下載代碼

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: object; //內容

const { status, data } = await apiInstance.sysGenTablesDownloadPost(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **object**| 內容 | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysGenTablesGenCodePost**
> ResponseResponse sysGenTablesGenCodePost(data)

生成表管理的代碼

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: object; //內容

const { status, data } = await apiInstance.sysGenTablesGenCodePost(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **object**| 內容 | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysGenTablesGenDbIdPost**
> ResponseResponse sysGenTablesGenDbIdPost()

表管理中生成菜單數據

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //編號 (default to undefined)

const { status, data } = await apiInstance.sysGenTablesGenDbIdPost(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | 編號 | defaults to undefined|


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysGenTablesGet**
> SysGenTablesGet200Response sysGenTablesGet()

獲取表管理分頁列表

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let tableName: string; //表名稱 (optional) (default to undefined)
let tableComment: string; //表描述 (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)
let tableNameOrder: string; //表名稱排序 (optional) (default to undefined)
let tableCommentOrder: string; //表描述排序 (optional) (default to undefined)
let createdAtOrder: string; //建立時間排序 (optional) (default to undefined)
let pageSize: number; //每頁條數 (optional) (default to undefined)
let pageIndex: number; //頁碼 (optional) (default to undefined)

const { status, data } = await apiInstance.sysGenTablesGet(
    tableName,
    tableComment,
    beginCreatedAt,
    endCreatedAt,
    tableNameOrder,
    tableCommentOrder,
    createdAtOrder,
    pageSize,
    pageIndex
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **tableName** | [**string**] | 表名稱 | (optional) defaults to undefined|
| **tableComment** | [**string**] | 表描述 | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|
| **tableNameOrder** | [**string**] | 表名稱排序 | (optional) defaults to undefined|
| **tableCommentOrder** | [**string**] | 表描述排序 | (optional) defaults to undefined|
| **createdAtOrder** | [**string**] | 建立時間排序 | (optional) defaults to undefined|
| **pageSize** | [**number**] | 每頁條數 | (optional) defaults to undefined|
| **pageIndex** | [**number**] | 頁碼 | (optional) defaults to undefined|


### Return type

**SysGenTablesGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysGenTablesIdGet**
> SysGenTablesIdGet200Response sysGenTablesIdGet()

獲取表管理詳情

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //編號 (default to undefined)

const { status, data } = await apiInstance.sysGenTablesIdGet(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | 編號 | defaults to undefined|


### Return type

**SysGenTablesIdGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysGenTablesPost**
> ResponseResponse sysGenTablesPost(data)

新增表管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysGenTableInsertReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysGenTableInsertReq; //內容

const { status, data } = await apiInstance.sysGenTablesPost(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysGenTableInsertReq**| 內容 | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysGenTablesPreviewIdGet**
> SysGenTablesPreviewIdGet200Response sysGenTablesPreviewIdGet()

預覽表管理的代碼頁面

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //編號 (default to undefined)

const { status, data } = await apiInstance.sysGenTablesPreviewIdGet(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | 編號 | defaults to undefined|


### Return type

**SysGenTablesPreviewIdGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysGenTablesPut**
> ResponseResponse sysGenTablesPut(data)

更新表管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysGenTableUpdateReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysGenTableUpdateReq; //內容

const { status, data } = await apiInstance.sysGenTablesPut(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysGenTableUpdateReq**| 內容 | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysLoginLogDelete**
> ResponseResponse sysLoginLogDelete(data)

刪除登錄日誌

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysLoginLogDeleteReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysLoginLogDeleteReq; //內容

const { status, data } = await apiInstance.sysLoginLogDelete(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysLoginLogDeleteReq**| 內容 | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysLoginLogExportPost**
> ResponseResponse sysLoginLogExportPost()

導出登錄日誌

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let userId: string; //用戶編號 (optional) (default to undefined)
let username: string; //用戶名 (optional) (default to undefined)
let status: string; //狀態 (optional) (default to undefined)
let ipaddr: string; //IP地址 (optional) (default to undefined)
let loginLocation: string; //歸屬地 (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)

const { status, data } = await apiInstance.sysLoginLogExportPost(
    userId,
    username,
    status,
    ipaddr,
    loginLocation,
    beginCreatedAt,
    endCreatedAt
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **userId** | [**string**] | 用戶編號 | (optional) defaults to undefined|
| **username** | [**string**] | 用戶名 | (optional) defaults to undefined|
| **status** | [**string**] | 狀態 | (optional) defaults to undefined|
| **ipaddr** | [**string**] | IP地址 | (optional) defaults to undefined|
| **loginLocation** | [**string**] | 歸屬地 | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysLoginLogGet**
> SysLoginLogGet200Response sysLoginLogGet()

獲取登錄日誌分頁列表

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let userId: string; //用戶編號 (optional) (default to undefined)
let username: string; //用戶名 (optional) (default to undefined)
let status: string; //狀態 (optional) (default to undefined)
let ipaddr: string; //IP地址 (optional) (default to undefined)
let loginLocation: string; //歸屬地 (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)
let createdAtOrder: string; //建立時間排序 (optional) (default to undefined)
let pageSize: number; //每頁條數 (optional) (default to undefined)
let pageIndex: number; //頁碼 (optional) (default to undefined)

const { status, data } = await apiInstance.sysLoginLogGet(
    userId,
    username,
    status,
    ipaddr,
    loginLocation,
    beginCreatedAt,
    endCreatedAt,
    createdAtOrder,
    pageSize,
    pageIndex
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **userId** | [**string**] | 用戶編號 | (optional) defaults to undefined|
| **username** | [**string**] | 用戶名 | (optional) defaults to undefined|
| **status** | [**string**] | 狀態 | (optional) defaults to undefined|
| **ipaddr** | [**string**] | IP地址 | (optional) defaults to undefined|
| **loginLocation** | [**string**] | 歸屬地 | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|
| **createdAtOrder** | [**string**] | 建立時間排序 | (optional) defaults to undefined|
| **pageSize** | [**number**] | 每頁條數 | (optional) defaults to undefined|
| **pageIndex** | [**number**] | 頁碼 | (optional) defaults to undefined|


### Return type

**SysLoginLogGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysLoginLogIdGet**
> SysLoginLogIdGet200Response sysLoginLogIdGet()

獲取登錄日誌詳情

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //編號 (default to undefined)

const { status, data } = await apiInstance.sysLoginLogIdGet(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | 編號 | defaults to undefined|


### Return type

**SysLoginLogIdGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysOperaLogDelete**
> ResponseResponse sysOperaLogDelete(data)

刪除操作日誌

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysOperLogDeleteReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysOperLogDeleteReq; //內容

const { status, data } = await apiInstance.sysOperaLogDelete(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysOperLogDeleteReq**| 內容 | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysOperaLogExportPost**
> ResponseResponse sysOperaLogExportPost()

導出操作日誌

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let title: string; //操作模組 (optional) (default to undefined)
let method: string; //函數 (optional) (default to undefined)
let requestMethod: string; //請求方式 (optional) (default to undefined)
let operUrl: string; //訪問地址 (optional) (default to undefined)
let operIp: string; //客戶端IP (optional) (default to undefined)
let status: string; //狀態 (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)

const { status, data } = await apiInstance.sysOperaLogExportPost(
    title,
    method,
    requestMethod,
    operUrl,
    operIp,
    status,
    beginCreatedAt,
    endCreatedAt
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **title** | [**string**] | 操作模組 | (optional) defaults to undefined|
| **method** | [**string**] | 函數 | (optional) defaults to undefined|
| **requestMethod** | [**string**] | 請求方式 | (optional) defaults to undefined|
| **operUrl** | [**string**] | 訪問地址 | (optional) defaults to undefined|
| **operIp** | [**string**] | 客戶端IP | (optional) defaults to undefined|
| **status** | [**string**] | 狀態 | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysOperaLogGet**
> SysOperaLogGet200Response sysOperaLogGet()

獲取操作日誌分頁列表

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let title: string; //操作模組 (optional) (default to undefined)
let method: string; //函數 (optional) (default to undefined)
let requestMethod: string; //請求方式 (optional) (default to undefined)
let operUrl: string; //訪問地址 (optional) (default to undefined)
let operIp: string; //客戶端IP (optional) (default to undefined)
let status: string; //狀態 (optional) (default to undefined)
let beginCreatedAt: string; //建立時間起 (optional) (default to undefined)
let endCreatedAt: string; //建立時間止 (optional) (default to undefined)
let createdAtOrder: string; //建立時間排序 (optional) (default to undefined)
let pageSize: number; //每頁條數 (optional) (default to undefined)
let pageIndex: number; //頁碼 (optional) (default to undefined)

const { status, data } = await apiInstance.sysOperaLogGet(
    title,
    method,
    requestMethod,
    operUrl,
    operIp,
    status,
    beginCreatedAt,
    endCreatedAt,
    createdAtOrder,
    pageSize,
    pageIndex
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **title** | [**string**] | 操作模組 | (optional) defaults to undefined|
| **method** | [**string**] | 函數 | (optional) defaults to undefined|
| **requestMethod** | [**string**] | 請求方式 | (optional) defaults to undefined|
| **operUrl** | [**string**] | 訪問地址 | (optional) defaults to undefined|
| **operIp** | [**string**] | 客戶端IP | (optional) defaults to undefined|
| **status** | [**string**] | 狀態 | (optional) defaults to undefined|
| **beginCreatedAt** | [**string**] | 建立時間起 | (optional) defaults to undefined|
| **endCreatedAt** | [**string**] | 建立時間止 | (optional) defaults to undefined|
| **createdAtOrder** | [**string**] | 建立時間排序 | (optional) defaults to undefined|
| **pageSize** | [**number**] | 每頁條數 | (optional) defaults to undefined|
| **pageIndex** | [**number**] | 頁碼 | (optional) defaults to undefined|


### Return type

**SysOperaLogGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysOperaLogIdGet**
> SysOperaLogIdGet200Response sysOperaLogIdGet()

獲取操作日誌詳情

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //編號 (default to undefined)

const { status, data } = await apiInstance.sysOperaLogIdGet(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | 編號 | defaults to undefined|


### Return type

**SysOperaLogIdGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 找不到資源 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysUserDelete**
> ResponseResponse sysUserDelete(data)

刪除系統用戶管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysUserDeleteReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysUserDeleteReq; //body

const { status, data } = await apiInstance.sysUserDelete(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysUserDeleteReq**| body | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysUserGet**
> SysUserGet200Response sysUserGet()

獲取系統用戶管理分頁列表

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let username: string; //用戶名 (optional) (default to undefined)
let status: string; //狀態 (optional) (default to undefined)
let phone: string; //手機號 (optional) (default to undefined)
let beginTime: string; //開始時間 (optional) (default to undefined)
let endTime: string; //結束時間 (optional) (default to undefined)
let deptId: string; //部門id (optional) (default to undefined)
let pageSize: number; //頁條數 (optional) (default to undefined)
let pageIndex: number; //頁碼 (optional) (default to undefined)

const { status, data } = await apiInstance.sysUserGet(
    username,
    status,
    phone,
    beginTime,
    endTime,
    deptId,
    pageSize,
    pageIndex
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **username** | [**string**] | 用戶名 | (optional) defaults to undefined|
| **status** | [**string**] | 狀態 | (optional) defaults to undefined|
| **phone** | [**string**] | 手機號 | (optional) defaults to undefined|
| **beginTime** | [**string**] | 開始時間 | (optional) defaults to undefined|
| **endTime** | [**string**] | 結束時間 | (optional) defaults to undefined|
| **deptId** | [**string**] | 部門id | (optional) defaults to undefined|
| **pageSize** | [**number**] | 頁條數 | (optional) defaults to undefined|
| **pageIndex** | [**number**] | 頁碼 | (optional) defaults to undefined|


### Return type

**SysUserGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysUserIdGet**
> SysUserIdGet200Response sysUserIdGet()

獲取系統用戶管理詳情

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let id: number; //id (default to undefined)

const { status, data } = await apiInstance.sysUserIdGet(
    id
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **id** | [**number**] | id | defaults to undefined|


### Return type

**SysUserIdGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysUserPost**
> AppUserUserCountryCodePost200Response sysUserPost(data)

新增系統用戶管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysUserInsertReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysUserInsertReq; //body

const { status, data } = await apiInstance.sysUserPost(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysUserInsertReq**| body | |


### Return type

**AppUserUserCountryCodePost200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysUserProfileAvatarPost**
> SysUserProfileAvatarPost200Response sysUserProfileAvatarPost()

更新系統登入用戶頭像

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let avatar: File; //avatar (default to undefined)

const { status, data } = await apiInstance.sysUserProfileAvatarPost(
    avatar
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **avatar** | [**File**] | avatar | defaults to undefined|


### Return type

**SysUserProfileAvatarPost200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: multipart/form-data
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysUserProfileGet**
> SysUserProfileGet200Response sysUserProfileGet()

獲取系統登入用戶信息

### Example

```typescript
import {
    DefaultApi,
    Configuration
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

const { status, data } = await apiInstance.sysUserProfileGet();
```

### Parameters
This endpoint does not have any parameters.


### Return type

**SysUserProfileGet200Response**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysUserProfilePut**
> ResponseResponse sysUserProfilePut(data)

更新系統登入用戶信息

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysUserUpdateReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysUserUpdateReq; //body

const { status, data } = await apiInstance.sysUserProfilePut(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysUserUpdateReq**| body | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysUserProfilePwdPut**
> ResponseResponse sysUserProfilePwdPut(data)

更新系統登入用戶密碼

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoUpdateSysUserPwdReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoUpdateSysUserPwdReq; //body

const { status, data } = await apiInstance.sysUserProfilePwdPut(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoUpdateSysUserPwdReq**| body | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysUserPut**
> ResponseResponse sysUserPut(data)

更新系統用戶管理

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysUserUpdateReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysUserUpdateReq; //body

const { status, data } = await apiInstance.sysUserPut(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysUserUpdateReq**| body | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysUserPwdResetPut**
> ResponseResponse sysUserPwdResetPut(data)

重置系統用戶密碼

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoResetSysUserPwdReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoResetSysUserPwdReq; //body

const { status, data } = await apiInstance.sysUserPwdResetPut(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoResetSysUserPwdReq**| body | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sysUserStatusPut**
> ResponseResponse sysUserStatusPut(data)

更新系統用戶狀態

### Example

```typescript
import {
    DefaultApi,
    Configuration,
    DtoSysUserStatusUpdateReq
} from './api';

const configuration = new Configuration();
const apiInstance = new DefaultApi(configuration);

let data: DtoSysUserStatusUpdateReq; //body

const { status, data } = await apiInstance.sysUserStatusPut(
    data
);
```

### Parameters

|Name | Type | Description  | Notes|
|------------- | ------------- | ------------- | -------------|
| **data** | **DtoSysUserStatusUpdateReq**| body | |


### Return type

**ResponseResponse**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: */*


### HTTP response details
| Status code | Description | Response headers |
|-------------|-------------|------------------|
|**200** | OK |  -  |
|**400** | 請求參數錯誤 |  -  |
|**401** | 未授權 |  -  |
|**403** | 權限不足 |  -  |
|**404** | 資源不存在 |  -  |
|**500** | 伺服器內部錯誤 |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

