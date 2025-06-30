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
- Auto Sign-in run successful on Sun Apr  6 01:46:54 UTC 2025
- Auto Sign-in run successful on Mon Apr  7 01:45:03 UTC 2025
- Auto Sign-in run successful on Tue Apr  8 01:42:32 UTC 2025
- Auto Sign-in run successful on Wed Apr  9 01:42:38 UTC 2025
- Auto Sign-in run successful on Thu Apr 10 01:42:44 UTC 2025
- Auto Sign-in run successful on Fri Apr 11 01:43:08 UTC 2025
- Auto Sign-in run successful on Sat Apr 12 01:40:29 UTC 2025
- Auto Sign-in run successful on Sun Apr 13 03:09:15 UTC 2025
- Auto Sign-in run successful on Mon Apr 14 01:47:32 UTC 2025
- Auto Sign-in run successful on Tue Apr 15 01:45:56 UTC 2025
- Auto Sign-in run successful on Wed Apr 16 01:45:24 UTC 2025
- Auto Sign-in run successful on Thu Apr 17 01:43:48 UTC 2025
- Auto Sign-in run successful on Fri Apr 18 01:41:37 UTC 2025
- Auto Sign-in run successful on Sat Apr 19 01:39:47 UTC 2025
- Auto Sign-in run successful on Sun Apr 20 01:49:51 UTC 2025
- Auto Sign-in run successful on Mon Apr 21 01:49:07 UTC 2025
- Auto Sign-in run successful on Tue Apr 22 01:44:46 UTC 2025
- Auto Sign-in run successful on Wed Apr 23 01:44:57 UTC 2025
- Auto Sign-in run successful on Thu Apr 24 01:45:14 UTC 2025
- Auto Sign-in run successful on Fri Apr 25 01:46:00 UTC 2025
- Auto Sign-in run successful on Sat Apr 26 01:41:52 UTC 2025
- Auto Sign-in run successful on Sun Apr 27 01:50:15 UTC 2025
- Auto Sign-in run successful on Mon Apr 28 01:48:35 UTC 2025
- Auto Sign-in run successful on Tue Apr 29 01:46:45 UTC 2025
- Auto Sign-in run successful on Wed Apr 30 01:46:02 UTC 2025
- Auto Sign-in run successful on Thu May  1 01:54:46 UTC 2025
- Auto Sign-in run successful on Fri May  2 01:46:38 UTC 2025
- Auto Sign-in run successful on Sat May  3 01:44:11 UTC 2025
- Auto Sign-in run successful on Sun May  4 01:55:30 UTC 2025
- Auto Sign-in run successful on Mon May  5 01:50:44 UTC 2025
- Auto Sign-in run successful on Tue May  6 01:47:30 UTC 2025
- Auto Sign-in run successful on Wed May  7 01:48:05 UTC 2025
- Auto Sign-in run successful on Thu May  8 01:48:30 UTC 2025
- Auto Sign-in run successful on Fri May  9 01:47:53 UTC 2025
- Auto Sign-in run successful on Sat May 10 01:43:30 UTC 2025
- Auto Sign-in run successful on Sun May 11 01:53:36 UTC 2025
- Auto Sign-in run successful on Mon May 12 01:51:59 UTC 2025
- Auto Sign-in run successful on Tue May 13 01:49:22 UTC 2025
- Auto Sign-in run successful on Wed May 14 01:48:12 UTC 2025
- Auto Sign-in run successful on Thu May 15 01:46:23 UTC 2025
- Auto Sign-in run successful on Fri May 16 01:49:33 UTC 2025
- Auto Sign-in run successful on Sat May 17 01:46:17 UTC 2025
- Auto Sign-in run successful on Sun May 18 01:54:57 UTC 2025
- Auto Sign-in run successful on Mon May 19 01:54:12 UTC 2025
- Auto Sign-in run successful on Tue May 20 01:49:59 UTC 2025
- Auto Sign-in run successful on Wed May 21 01:49:31 UTC 2025
- Auto Sign-in run successful on Thu May 22 01:48:56 UTC 2025
- Auto Sign-in run successful on Fri May 23 01:48:49 UTC 2025
- Auto Sign-in run successful on Sat May 24 01:45:07 UTC 2025
- Auto Sign-in run successful on Sun May 25 01:57:27 UTC 2025
- Auto Sign-in run successful on Mon May 26 01:52:44 UTC 2025
- Auto Sign-in run successful on Tue May 27 01:48:12 UTC 2025
- Auto Sign-in run successful on Wed May 28 01:49:59 UTC 2025
- Auto Sign-in run successful on Thu May 29 01:49:48 UTC 2025
- Auto Sign-in run successful on Fri May 30 01:47:43 UTC 2025
- Auto Sign-in run successful on Sat May 31 01:47:24 UTC 2025
- Auto Sign-in run successful on Sun Jun  1 02:07:39 UTC 2025
- Auto Sign-in run successful on Mon Jun  2 01:55:13 UTC 2025
- Auto Sign-in run successful on Tue Jun  3 01:51:57 UTC 2025
- Auto Sign-in run successful on Wed Jun  4 01:52:01 UTC 2025
- Auto Sign-in run successful on Thu Jun  5 01:50:38 UTC 2025
- Auto Sign-in run successful on Fri Jun  6 01:49:57 UTC 2025
- Auto Sign-in run successful on Sat Jun  7 01:49:20 UTC 2025
- Auto Sign-in run successful on Sun Jun  8 01:59:53 UTC 2025
- Auto Sign-in run successful on Mon Jun  9 01:57:14 UTC 2025
- Auto Sign-in run successful on Tue Jun 10 01:53:17 UTC 2025
- Auto Sign-in run successful on Wed Jun 11 01:52:46 UTC 2025
- Auto Sign-in run successful on Thu Jun 12 01:51:22 UTC 2025
- Auto Sign-in run successful on Fri Jun 13 01:52:26 UTC 2025
- Auto Sign-in run successful on Sat Jun 14 01:48:25 UTC 2025
- Auto Sign-in run successful on Sun Jun 15 02:02:08 UTC 2025
- Auto Sign-in run successful on Mon Jun 16 01:56:08 UTC 2025
- Auto Sign-in run successful on Tue Jun 17 01:53:04 UTC 2025
- Auto Sign-in run successful on Wed Jun 18 01:52:18 UTC 2025
- Auto Sign-in run successful on Thu Jun 19 01:53:17 UTC 2025
- Auto Sign-in run successful on Fri Jun 20 01:52:13 UTC 2025
- Auto Sign-in run successful on Sat Jun 21 01:50:03 UTC 2025
- Auto Sign-in run successful on Sun Jun 22 02:01:17 UTC 2025
- Auto Sign-in run successful on Mon Jun 23 01:59:45 UTC 2025
- Auto Sign-in run successful on Tue Jun 24 01:53:56 UTC 2025
- Auto Sign-in run successful on Wed Jun 25 01:53:58 UTC 2025
- Auto Sign-in run successful on Thu Jun 26 01:52:43 UTC 2025
- Auto Sign-in run successful on Fri Jun 27 01:53:48 UTC 2025
- Auto Sign-in run successful on Sat Jun 28 01:49:28 UTC 2025
- Auto Sign-in run successful on Sun Jun 29 02:03:40 UTC 2025
- Auto Sign-in run successful on Mon Jun 30 01:58:35 UTC 2025
