# trxhao
TRX/波场地址靓号生成器。支持前/后缀、连续字符与关键词匹配，多线程、断点续跑与批量导出；可选 CPU、GPU（CUDA/OpenCL）或浏览器 WASM。按 TRON 规则派生地址：keccak256(pubkey) 末 20 字节 + 0x41 前缀，经 Base58Check 编码。仅用于学习与性能研究，建议离线使用，不收集或上传任何私钥。
