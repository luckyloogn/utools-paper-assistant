# uTools 插件 - 论文工具

一款 uTools 插件，用于去除复制PDF中的文字时出现的空格、换行、全角字符或乱码。

## 说明
* 本项目是开源项目 **[paper-assistant](https://github.com/laorange/paper-assistant)** 核心功能的 uTools 插件实现

* **文本复制工具** 的核心代码移植自 **[paper-assistant](https://github.com/laorange/paper-assistant)** 的 **[handlers.ts](https://github.com/laorange/paper-assistant/blob/master/src/assets/ts/article-copy-tool/handlers.ts)** 文件

* 本项目基于 uTools 官方开源插件 **[utools-qrcode](https://github.com/uTools-Labs/utools-qrcode)** 修改而来

* 设置数据的保存参考 uTools 官方开源插件 **[utools-code-helper](https://github.com/uTools-Labs/utools-code-helper)** 的 **[Timestamp.js](https://github.com/uTools-Labs/utools-code-helper/blob/main/src/Timestamp.js)** 文件

## 截图
### 明亮模式

![light-home-page](./images/light-home-page.png)

![light-settings-page](./images/light-settings-page.png)

### 暗黑模式

![dark-home-page](./images/dark-home-page.png)

![dark-settings-page](./images/dark-settings-page.png)

## 运行本项目
1. 安装 **[Note.js](https://nodejs.org/en)**
2. 克隆本项目
    ```
    git clone https://github.com/luckyloogn/utools-paper-assistant.git
    ```
3. 构建运行
    ```
    cd utools-paper-assistant
    npm install
    npm run build
    ```
4. 在 **uTools** 中搜索 `开发者工具`，并点击图标打开
    ![search-for-developer-tools](./images/search-for-developer-tools.png)
    ![developer-tools-home-page](./images/developer-tools-home-page.png)

5. 点击 `开发者工具` 左下角 `新建项目` 按钮，按照提示填写信息，创建新项目
    ![developer-tools-new-project-page](./images/developer-tools-new-project-page.png)

6. 点击 `选择工程「plugin.json」文件`，选择 `utools-paper-assistant/dist/plugin.json`，然后点击 `接入开发`
    ![developer-tools-new-project-config-page1](./images/developer-tools-new-project-config-page1.png)
    ![developer-tools-new-project-config-page2](./images/developer-tools-new-project-config-page2.png)

## 安装插件
1. 在 **[Releases](https://github.com/luckyloogn/utools-paper-assistant/releases)** 页面下载 `upxs` 离线安装文件到您的电脑
2. `Ctrl + C` 复制下载的文件，然后 `Alt + 空格` 唤出 **utools**，点击 `安装插件应用` 图标，再点 `安装插件应用`，然后再点 `已知风险继续安装` 即可
    ![install-plugin](./images/install-plugin.png)
    ![install-plugin-confirm1](./images/install-plugin-confirm1.png)
    ![install-plugin-confirm2](./images/install-plugin-confirm2.png)