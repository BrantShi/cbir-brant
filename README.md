# cbir-brant

大学生毕业设计，主题是基于移动端相似商品图像检索。项目用于在云服务器上部署后端，前端使用微信小程序搭建。

商品图像检索是一种限定的基于内容的图像检索（content based image retrieval，CBIR），本次毕业设计参照淘宝移动端的手机拍照服务，意图设计并实现一套在小数据集下以较快速度返回的商品图像检索系统。

## 环境

项目基于Flask 框架搭建云端服务，服务器由nginx & uwsgi协作构成，故使用此项目首先需保证安装有以上两者。

## 安装

```bash
# 复制仓库并进入相应目录
$ git clone https://github.com/BrantShi/cbir-brant.git
$ cd cbir-brant

# 激活虚拟环境并安装所有必要的组件
$ virtualenv env
$ source env/bin/activate
$ pip install -r requirements.txt
```

