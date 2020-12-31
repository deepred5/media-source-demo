# media-source-demo
视频分段下载和播放demo

### mp4转换fmp4
```bash
MP4Box -dash 4000 1.mp4 #### 每4s分割1段
```

### 启动
```bash
npm i
npm run start
```

浏览器访问: http://127.0.0.1:4444/