sse_video_filter
================

视频过滤器，目前只支持优酷和土豆

## 安装

启用本模块后，前往 `admin/config/content/formats` 配置过滤器。

请确保 `将URL转换成链接` 在本过滤器之后，`限制使用HTML标记` 在本过滤器之前

## 使用方法

`[video:url]`

基本用法：`[video:http://v.youku.com/v_show/id_XMTM0OTIyNzkyNA==.html?from=y1.7-1.2]`

设置长宽：`[video:http://v.youku.com/v_show/id_XMTM0OTIyNzkyNA==.html?from=y1.7-1.2 width:800 height:600]`

设置画面比：`[video:http://v.youku.com/v_show/id_XMTM0OTIyNzkyNA==.html?from=y1.7-1.2 width:800 height:600 ratio:4/3]`

## 备注

在Ckeditor上添加多媒体按钮的方法暂时没有研究出来
