# chatgpt_qq
Applying GPT to wechat
chatgpt_wechat的docker部署，支持最新的gpt3.5_turbo
该项目是@zhayujie大佬的项目，但是其docker部署中并不支持gpt3.5_turbo(截至3.4)，
所以对其进行了修改，以支持gpt3.5_turbo的部署。
非常简单：
git clone https://github.com/Creazygao/chatgpt_wechat.git 
cd chatgpt_wechat
chmod +x build.alpine.sh           # 构建脚本添加执行权限
./build.alpine.sh  
docker run -it --name sample-chatgpt-on-wechat --env-file=.env zhayujie/chatgpt-on-wechat 
