# 快速开始：在手机上查看Expo项目

## 方法一：通过GitHub Actions自动发布

### 设置步骤：
1. 在GitHub仓库的 Settings → Secrets and variables → Actions
2. 添加 `EXPO_TOKEN`（从 https://expo.dev/settings/access-tokens 获取）
3. 推送代码到main分支触发自动发布

### 在手机上查看：
1. 安装 **Expo Go** 应用（App Store或Google Play）
2. 打开Expo Go
3. 扫描GitHub Actions运行日志中的二维码
4. 或输入URL：`exp://exp.host/@你的用户名/ExpoMessaging`

## 方法二：手动发布（开发环境）

### 本地设置：
```bash
cd examples/ExpoMessaging
yarn install
npx expo start
```

### 在手机上查看：
1. 确保手机和电脑在同一WiFi网络
2. 在手机上打开Expo Go
3. 扫描终端中显示的二维码

## 项目信息
- 项目名称：ExpoMessaging
- 这是一个Stream Chat React Native示例应用
- 使用Expo Router进行导航
- 支持iOS和Android