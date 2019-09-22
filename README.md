# mi-airfresh

> 项目基于[米家新风（dmake.airfresh.t2017）接入homeassistant](https://bbs.hassbian.com/thread-8218-1-1.html)，上传到GitHub方便接入HACS，后面有时间再补上其余功能的实现

本项目为米家新风（dmake.airfresh.t2017）在ha上的自定义组件。
可通过HACS进行安装。
配置脚本如下：
```yaml
fan:
  - platform: dairfresh
    host: $(your_IP)
    token: $(your_token)
    name: MijiaAirfresh
    model: dmaker.airfresh.t2017
```
