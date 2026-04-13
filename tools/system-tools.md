# 系统工具

## 系统自带工具

### 任务管理器
按 Ctrl+Shift+Esc 打开
- 查看进程、性能、启动项

### 资源监视器
按 Win+R 输入 resmon 打开
- 查看详细系统资源使用情况

### 事件查看器
按 Win+R 输入 eventvwr.msc 打开
- 查看系统日志和错误信息

### 磁盘清理
按 Win+R 输入 cleanmgr 打开
- 清理系统垃圾文件

### 磁盘碎片整理
输入 dfrgui 打开
- 优化磁盘性能

## 常用命令

### 系统信息
```
systeminfo
```

### 检查磁盘
```
chkdsk /f
```

### 系统文件检查
```
sfc /scannow
```

### 部署映像服务和管理
```
DISM /Online /Cleanup-Image /RestoreHealth
```

### 网络重置
```
netsh winsock reset
netsh int ip reset
```
