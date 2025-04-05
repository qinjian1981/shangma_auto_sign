## 上马自动签到 [![Run Auto Sign](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml/badge.svg)](https://github.com/zhaohongxuan/shangma_auto_sign/actions/workflows/auto-sign.yaml)

### 基于 Node.js + GitHub Action 实现上海马拉松官网每日签到

### Use 使用

1. Fork本项目（顺手点Star以示鼓励～🥳）
2. 在Repo的Setting页面，添加名为上马官网的用户名：`SM_USERNAME`和密码：`SM_PASSWORD`的Secret 
3. 手动测试运行
<img width="1444" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/695683c9-fbc2-4cab-9ef8-41e2ddf59b78">
在控制台应该能看到 `签到成功/请勿重复签到` 的提示
<img width="990" alt="image" src="https://github.com/zhaohongxuan/shangma_auto_sign/assets/8613196/399e89f7-2ad6-486e-9e67-8953564ec528">


### 关于Job执行时间
签到Job执行时间是**UTC时间0点**，也就是**北京时间8点**执行，**不过由于GitHub的负载比较重**，真正签到时间可能延后一段时间，一般是几十分钟，这个延迟时间取决于GitHub Action的负载。

### 申明
- 本项目仅做学习交流, 禁止用于各种非法途径
- Auto Sign-in run successful on Wed Mar 12 04:38:09 UTC 2025
- Auto Sign-in run successful on Thu Mar 13 01:40:14 UTC 2025
- Auto Sign-in run successful on Fri Mar 14 01:38:20 UTC 2025
- Auto Sign-in run successful on Sat Mar 15 01:37:37 UTC 2025
- Auto Sign-in run successful on Sat Mar 15 09:13:20 UTC 2025
- Auto Sign-in run successful on Sun Mar 16 01:45:04 UTC 2025
- Auto Sign-in run successful on Mon Mar 17 01:42:20 UTC 2025
- Auto Sign-in run successful on Tue Mar 18 01:40:44 UTC 2025
- Auto Sign-in run successful on Wed Mar 19 01:40:36 UTC 2025
- Auto Sign-in run successful on Thu Mar 20 01:39:30 UTC 2025
- Auto Sign-in run successful on Fri Mar 21 01:41:18 UTC 2025
- Auto Sign-in run successful on Sat Mar 22 01:38:43 UTC 2025
- Auto Sign-in run successful on Sun Mar 23 01:45:59 UTC 2025
- Auto Sign-in run successful on Mon Mar 24 01:44:04 UTC 2025
- Auto Sign-in run successful on Tue Mar 25 01:41:51 UTC 2025
- Auto Sign-in run successful on Wed Mar 26 01:41:12 UTC 2025
- Auto Sign-in run successful on Thu Mar 27 01:41:12 UTC 2025
- Auto Sign-in run successful on Fri Mar 28 01:41:16 UTC 2025
- Auto Sign-in run successful on Sat Mar 29 01:40:13 UTC 2025
- Auto Sign-in run successful on Sun Mar 30 01:48:13 UTC 2025
- Auto Sign-in run successful on Mon Mar 31 01:46:43 UTC 2025
- Auto Sign-in run successful on Tue Apr  1 01:52:54 UTC 2025
- Auto Sign-in run successful on Wed Apr  2 01:43:12 UTC 2025
- Auto Sign-in run successful on Thu Apr  3 01:41:52 UTC 2025
- Auto Sign-in run successful on Fri Apr  4 01:41:40 UTC 2025
- Auto Sign-in run successful on Sat Apr  5 01:40:02 UTC 2025
