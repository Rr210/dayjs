## 预览软件

![软件预览](https://gitee.com/rbozo/picgo_image/raw/master/image/0/20210826000245.png)

## 仓库简介

* 该软件开发主要是用于前端知识的学习. 方便切换题目, 本地记录学习天数
* 前端题库来源`前端知识每日3+1`

## 开发技术

* 使用`python+tkinter`
* `exe`打包工具为`pyinstaller`
* `pip install -r requirements.txt`  安装依赖
* `pyinstaller -F -w -i day_favicon.ico tit.py`  

## 更新日志

* v1.0.5 2021-08-29
1. 修复开屏后本地题库问题
2. 修改访问镜像站，加快访问速度
3. 加入搜索板块，去除背景模块

* v1.0.3 2021-08-28
1. 修复切换上下页时问题
2. 对菜单栏部分进行优化处理
3. 加入主题配置页面背景颜色

* v1.0.2 2021-08-27
1. 加入本地题库数据判断，为空获取数据时有报错提示，需要重载
2. fix:修复本地题库不存在时的加载卡顿
3. 修改跳转接口地址，直接跳转源地址（GitHub issue）
4. 优化请求速度减少循环次数，加入本地题库总数获取

* v1.0.1 2021-08-26
1. 加入上一页，下一页，快速翻页效果
2. 加入重新加载题录操作,并且加入重载提示
3. 加入题库数量统计
4. 加入链接空值判断，加入加载进度条

* v1.0 2021-08-25
1. 开发exe版本
2. 加入本地记录天数

## 转载须知

* 转载请标明出处
* 如果觉得我写的程序对你小有帮助, 可以点个⭐⭐

## :copyright: License

[![MIT](http://api.haizlin.cn/api?mod=interview&ctr=issues&act=generateSVG&type=a.svg)](https://github.com/Rr210/hot_search/blob/master/LICENSE) [![上一次提交](https://badgen.net/github/last-commit/Rr210/dayjs)]()
