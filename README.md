# frontend
connect to host github.com port 22

使用 ssh 443端口
测试：
ssh -T -p 443 git@ssh.github.com

配置：
~/.ssh/config
Host github.com
Hostname ssh.github.com
Port 443
