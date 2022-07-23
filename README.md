# subscribe_event_demo
 
1. 创建项目文件夹subscribe_event_demo

2. 运行终端，运行命令
npm install typescript
npm install ts-node

npm init //初始化一个Node.js项目
npm install typescript --save-dev
npm i --save-dev @types/node
yarn add @polkadot/api
npx tsc --init //将创建一个typescript默认配置文件tsconfig.json

3. 修改配置文件
tsconfig.json
"rootDir": "./",
"outDir": "dist", 定义TS编译后的目录，如果没有声明，默认编译后的文件位置将和ts源文件在同一位置
"suppressImplicitAnyIndexErrors":true, //解决typescript报错

package.json


4. 运行
substrate-node-template文件夹中，终端运行命令，开启节点
./target/release/node-template --dev --tmp

本项目中，终端运行命令
ts-node main.ts 

