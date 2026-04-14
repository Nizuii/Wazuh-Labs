# FIM - Lab

In this lab we are going to check **File Integrity Monitoring**. So our goal is to monitor a specific directory in our ubuntu server and that specific directory is `/home/zoooi/spacex`. So before we monitor that directory we need to tell our agent by adding this following line in `<syscheck>` block.
```bash
<directories realtime="yes" report_changes="yes" check_all="yes">/home/zoooi/spacex</directories>
```
<img src="Images/fim1.png">
