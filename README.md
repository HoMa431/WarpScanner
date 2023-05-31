### CFwarp For script related instructions, please check [Yong Ge Blog](https://ygkkk.blogspot.com/2022/09/cfwarp-script.html)
### For relevant instructions and points of attention, please refer to [warp series video instructions](https://www.youtube.com/playlist?list=PLMgly2AulGG-WqPXPkHlqWVSfQ3XjHNw8)
------------------------------------------------------------------------------------------------------------------------------
#### vps one key script :
```
bash <(wget -qO- https://gitlab.com/rwkgyg/CFwarp/raw/main/CFwarp.sh 2> /dev/null)
```
or
```
bash <(curl -Ls https://gitlab.com/rwkgyg/CFwarp/raw/main/CFwarp.sh)
```
----------------------------------------------------------------------------------------------------------------------

### Multi-platform preferred WARP peer IP + unlimited generation of WARP-Wireguard configuration scripts
```
curl -sSL https://raw.githubusercontent.com/HoMa431/WarpScanner/main/point/endip.sh -o endip.sh && chmod +x endip.sh && ./endip.sh
```
-------------------------------------------------------------------------------------------------------------------------

#### 感谢WGCF源项目代码地址：https://github.com/ViRb3/wgcf
#### 感谢CoiaPrant，WARP-GO源项目代码地址：https://gitlab.com/ProjectWARP/warp-go
#### 相关功能参考来源： [P3terx](https://github.com/P3TERX/warp.sh)、[fscarmen](https://github.com/fscarmen/warp)、[热心的CF网友](https://github.com/badafans)提供的warp endpoint优选IP脚本及注册程序
