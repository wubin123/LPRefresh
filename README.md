# LPRefresh
模仿QQ橡皮筋刷新的控件，动画流畅、渲染高效。UIScrollView延展，只需一行代码。

下载地址 https://github.com/SwiftLiu/LPRefresh.git
https://github.com/SwiftLiu/LPRefresh/blob/master/image.png?raw=true

####初始化
```objc 
// UIScrollView延展，UITableView也可用
@interface UIScrollView (LPRefresh)
///添加刷新事件
- (void)addRefreshWithBlock:(void (^)())block;
```
####结束刷新
```objc
///刷新成功
- (void)endRefreshingSuccess;
///刷新失败
- (void)endRefreshingFail;
```
