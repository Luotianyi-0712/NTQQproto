## 钱包pb协议使用指南

- 全局安装protobufjs
  npm install -g protobufjs@7.2.4

  全局安装protobufjs-cli
  npm install -g protobufjs-cli

- 执行命令
  - cd ./business/wallet/wallet_api/src/main/resources/rawfile/pb/
  - python3 wallet_build_pb.py

- 产物
  - 最后会将当前目录下所有.proto文件都合并生成wallet_all_pb.js和wallet_all_pb.d.ts中