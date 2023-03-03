# chatgpt wechat
## Applying GPT to wechat
<br>chatgpt_wechat的docker部署，支持最新的gpt3.5_turbo
<br>该项目是@zhayujie大佬的项目，但是其docker部署中并不支持gpt3.5_turbo(截至3.4)，
<br>所以对其进行了修改，以支持gpt3.5_turbo的部署。
<br>非常简单：
<br>
>git clone https://github.com/Creazygao/chatgpt_wechat.git 
<br>cd chatgpt_wechat
<br>chmod +x build.alpine.sh    
<br>./build.alpine.sh  
<br>docker run -it --name sample-chatgpt-on-wechat --env-file=.env zhayujie/chatgpt-on-wechat 
