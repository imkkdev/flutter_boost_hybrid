# flutter_boost_hybrid
flutter_boost_hybrid root project

### 代码目录结构
```
-- flutter_boost_hybrid
   |
   |----- flutter_boost_fmodule
   |----- flutter_boost_android
   |----- flutter_boost_ios
```   

git仓库使用 gitsubmodule方式托管：
```
git submodule add <url> <path>
```
flutter_boost_hybrid root project 仓库
flutter_boost_fmodule flutter 仓库
flutter_boost_android android 仓库
flutter_boost_ios ios仓库



### 协同开发
```
// ① clone项目
git clone <root project url>

// ② 子module update
git submodule init && git submodule update

// ③ flutter get
flutter packages get
```
flutter module子项目ignore文件不包含.android .ios目录。执行flutter packages get 自动生成两个文件


