这是HCE的整合包源文件。
失联期间由mingyu_games进行维护。
给mingyu_games的忠告：
每上传一个文件，必须在server-manifest.json文件里做出更改。
在此文件中加入以下内容：    
{
      "hash": "待上传文件的SHA1校验值",
      "path": "overrides目录下的文件路径"
    },
    比如上传一个资源包名为resources.zip，就要这么写：
        {
      "hash": "c3035dfdbd68efab506dd4f07a3df108ec4eb429",
      "path": "resourcepacks/resources.zip"
    },
    这应该可以看懂了罢
