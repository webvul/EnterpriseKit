# EnterpriseKit

  工作中整理的安全工具箱,方便有同样需求的你

## 目录

  每个目录为一个小工具,都是一些小工具方便使用和集成

### elk_syslog

    使用elk解析和收集系统日志，包含syslog日志，secure日志，bash日志，和启动脚本

### nessus_report

    nessus扫描多个任务，需要统计为一份报告，先创建一个扫描文件夹，把任务添加进去，
    使用统计脚本，配置好文件夹的id，就可以批量统计多个扫描的数据，自带nessus-ruby-api库

### nmap_format

    针对nmap扫描结果日志，进行查询和格式化的脚步

### nmap_multi

    nmap自带并发功能，但是对于企业级的网络一个nmap进程实在是太慢了，服务器占有很小，浪费了我大服务器!
    纯bash实现多进程nmap，将多个网段写入input.txt，在脚本中配置namp参数和并发数，机器多强并发多快，请自己斟酌
    开始扫描，体验大网段65535扫描的新速度

### 3rd_audit

    第三方软件系统检查工具

### filemon.sh

    系统安全角度使用这个脚本，监控web目录，是否被上传了webshell，并发送邮件及时告知

