# Django Demo

## 步骤

### 00. Install and setup django

00. 创建虚拟环境

    ```shell
    pip3 install virtualenv
    source ./venv/Scripts/activate  # 启动虚拟环境
    ```

01. 安装依赖

    ```shell
    # 安装依赖
    pip3 install django
    pip3 install django-rest-framework
    pip3 install stripe
    pip3 install pillow
    pip3 install django-cors-headers
    ```

### 01. Install and setup vue

00. 安装 node.js

    ```shell
    # 参照官网
    ```

01. 安装 vue

    ```shell
    npm config set registry https://registry.npm.taobao.org
    # 全局安装 vue
    npm install -g @vue/cli
    ```

02. 创建项目

    ```shell
    vue create djackets_vue
    cd djackets_vue
    # 在项目内的安装包
    vue install axios
    vue install bulma
    ```
