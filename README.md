# gz-cz

依托于commitizen的emoji提示


## 使用
`需要 Node 版本 >=v12.20`

## 项目中使用

#### 1、安装依赖
```sh
npm install -D gz-cz commitizen
```

#### 2、修改 `package.json` 添加 `config` 指定使用的适配器
```json
{
  "scripts": {

  },
  "config": {
    "commitizen": {
      "path": "node_modules/gz-cz"
    }
  }
}
```

## 全局使用

#### 1、安装依赖
```sh
npm install -g gz-cz commitizen
```

#### 2、全局配置适配器类型
```sh
echo '{ "path": "gz-cz" }' > ~/.czrc
```

## 使用截图
![样例](./images/example.png)