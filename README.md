
基于Flutter开发，适配 Android 与 iOS。

项目适合Flutter的练手学习，覆盖了各种框架的使用，与原生的交互等。

随着项目的使用情况和反馈，将时不时根据更新并完善用户体验与功能优化吗，欢迎提出问题。


-----

## 须知

> **因为是偏学习项目，所以项目里会有各式各样的模式、库、UI等，请不要介意**
> 
> 1、 TrendPage ： 目前采用纯 bloc 的 rxdart(stream) + streamBuilder 模式效果
>
> 2、 Scoped Model：目前在 RepositoryDetailPage 出使用
>
> 3、 Redux：目前在 MyPage ，UserInfo、Theme、Localization 等上面使用。
>
> 4、 LoginPage：另类的 BLoC 模式。
> 
> 5、 ReposDao.getRepositoryDetailDao 使用 graphQL
> 
> **列表显示有多个，其中：**
> 
> 1、**gsy_pull_load_widget.dart.dart**
> `common_list_page.dart 等使用，搭配 gsy_list_state.dart 使用`
>
> 2、**gsy_pull_new_load_widget.dart.dart**
> `dynamic_page.dart 等使用，搭配 gsy_bloc_list_state.dart 使用`
> `有 iOS 和 Android 两种风格下拉风格支持`
> 
> 3、**gsy_nested_pull_load_widget.dart**
> `trend_page.dart 等使用，配置sliver 效果`

### 第三方框架

>当前 Flutter SDK 版本 2.5

| 库                          | 功能             |
| -------------------------- | -------------- |
| **dio**                    | **网络框架**       |
| **shared_preferences**     | **本地数据缓存**     |
| **fluttertoast**           | **toast**      |
| **flutter_redux**          | **redux**      |
| **device_info**            | **设备信息**       |
| **connectivity**           | **网络链接**       |
| **flutter_markdown**       | **markdown解析** |
| **json_annotation**        | **json模板**     |
| **json_serializable**      | **json模板**     |
| **url_launcher**           | **启动外部浏览器**    |
| **iconfont**               | **字库图标**       |
| **share**                  | **系统分享**       |
| **flutter_spinkit**        | **加载框样式**      |
| **get_version**            | **版本信息**       |
| **flutter_webview_plugin** | **全屏的webview** |
| **sqflite**                | **数据库**        |
| **flutter_statusbar**      | **状态栏**        |
| **flutter_svg**            | **svg**        |
| **photo_view**             | **图片预览**       |
| **flutter_slidable**       | **侧滑**         |
| **flutter_cache_manager**  | **缓存管理**       |
| **path_provider**          | **本地路径**       |
| **permission_handler**     | **权限**         |
| **scope_model**            | **状态管理和共享**    |
| **lottie**                 | **svg动画**    |
| **flare**                  | **路径动画**    |

### 进行中：

[版本更新说明](https://github.com/CarGuo/GSYGithubAppFlutter/blob/master/VERSION.md)
```



​    
