# ssr搭建和bbr加速
自家备份防和谐比较放心
## ssr.sh
chmod +x ssr.sh && bash ssr.sh

## bbr.sh
chmod +x bbr.sh && bash bbr.sh

之后sysctl net.ipv4.tcp_congestion_control输入若显示net.ipv4.tcp_congestion_control = bbr则证明安装成功
