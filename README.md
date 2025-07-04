# SoftwareDownload
- 静态网页下载软件存放仓库，
- 因为使用Workers Pages 加速大于30m的文件有限制

# 实现跨越仓库提供下载方式
- 启用这个仓库的pages服务，
- 用 GitHub Pages 直链（推荐，支持大文件）

## 步骤
- 先拼接出直链
```

当前仓库启用了GitHub Pages服务的地址
https://atx8t.github.io/SoftwareDownload/


当前仓库下的Telegram(1).apk文件名称

拼接

https://atx8t.github.io/SoftwareDownload/AndroidApp/Telegram(1).apk



静态页面下载

<section id="download" class="elixir-card">
    <h2 class="sect-title">功法下载</h2>
    <button class="download-btn" onclick="window.location.href='https://atx8t.github.io/SoftwareDownload/AndroidApp/Telegram(1).apk'">
        🎴 下载《玄天秘录》安卓版
    </button>
</section>

在需要下载的地方添加即可

```