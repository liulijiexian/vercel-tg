# vercel-tg
vercel-tg
测试vercel无服务器函数


就按照这个格式来，然后部署的时候，选择到这个目录下，不选择api文件夹目录下，然后就可以部署成功，然后访问链接https://vercel-tg-xi.vercel.app/api/index ，其中前面的https://vercel-tg-xi.vercel.app 是vercel自动配置的域名，后面的api/index，代表你的api文件下的index.py文件(因为我们需要运行这里的代码)，完整链接就是这样子：https://vercel-tg-xi.vercel.app/api/index?api=getMusicMain&key=许嵩&rn=60 ，这样子就可以有结果了

反正就是需要有api文件夹，然后要有index.py。具体为什么这样我还不太明白。
