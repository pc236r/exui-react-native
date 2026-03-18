# 在手机上通过Expo Go查看项目

## 步骤

### 1. 设置GitHub Secrets
在GitHub仓库中设置以下Secrets：
- `EXPO_TOKEN`: 你的Expo访问令牌

获取Expo Token的方法：
1. 访问 https://expo.dev/
2. 登录你的账号
3. 进入 Settings → Access Tokens
4. 创建新的访问令牌

### 2. 触发GitHub Actions
当你推送代码到main分支时，GitHub Actions会自动：
1. 安装依赖
2. 发布项目到Expo

### 3. 在手机上查看
1. 在手机上安装 **Expo Go** 应用
2. 打开Expo Go应用
3. 扫描GitHub Actions运行完成后生成的二维码
4. 或者手动输入项目URL

## 项目URL格式
发布后，项目URL格式为：
```
exp://exp.host/@你的用户名/ExpoMessaging
```

## 注意事项
1. 确保Expo Token有足够的权限
2. 第一次发布可能需要几分钟时间
3. 确保手机和电脑在同一个网络（用于开发调试）
4. 生产环境建议使用EAS Build构建独立应用