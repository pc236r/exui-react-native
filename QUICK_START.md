# 快速开始：在手机上查看Expo项目

## 最简单的方法：本地运行

### 步骤：
1. **克隆项目**
   ```bash
   git clone https://github.com/pc236r/moy-w.git
   cd moy-w/exui/examples/ExpoMessaging
   ```

2. **安装依赖**
   ```bash
   yarn install
   ```

3. **启动开发服务器**
   ```bash
   npx expo start
   ```

4. **在手机上查看**
   - 在手机上安装 **Expo Go** 应用（App Store或Google Play）
   - 确保手机和电脑在同一WiFi网络
   - 打开Expo Go，扫描终端中显示的二维码

## 使用GitHub Codespaces（无需本地安装）

### 步骤：
1. 访问 https://github.com/pc236r/moy-w
2. 点击绿色的 "Code" 按钮
3. 选择 "Codespaces" 标签
4. 点击 "Create codespace on main"
5. 在Codespaces终端中运行：
   ```bash
   cd exui/examples/ExpoMessaging
   yarn install
   npx expo start
   ```
6. 使用端口转发功能，在手机上查看

## 项目信息
- 项目名称：ExpoMessaging
- 这是一个Stream Chat React Native示例应用
- 使用Expo Router进行导航
- 支持iOS和Android
- 无需Expo账号即可本地运行