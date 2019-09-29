# aliyun-oss-sync

### 简介
阿里云 OSS 增量上传脚本，此脚本[原作者传送门](https://github.com/tianshuang/aliyun-oss-sync)，这里复制仓库用于学习研究。
环境要求：
Python 3.2 +

使用方法：

下载[incremental_upload_to_aliyun_oss.py](https://github.com/HHulk/aliyun-oss-sync/blob/master/incremental_upload_to_aliyun_oss.py)与[oss_config.json](https://github.com/tianshuang/aliyun-oss-sync/blob/master/oss_config.json)到本地。

将你的 OSS 配置信息替换掉 oss_config.json 中的模版配置，并将以上两个文件放置于同一目录下即可运行。

```Bash
python3 incremental_upload_to_aliyun_oss.py
```
