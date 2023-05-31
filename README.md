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

### Multi-platform preferred WARP peer IP + unlimited generation of WARP-Wireguard configuration scripts :
```
curl -sSL https://raw.githubusercontent.com/HoMa431/WarpScanner/main/point/endip.sh -o endip.sh && chmod +x endip.sh && ./endip.sh
```
-------------------------------------------------------------------------------------------------------------------------

#### Thanks to WGCF source project code address: https://github.com/ViRb3/wgcf
#### Thanks to CoiaPrant, WARP-GO source project code address: https://gitlab.com/ProjectWARP/warp-go
#### Related function reference sources: [P3terx](https://github.com/P3TERX/warp.sh), [fscarmen](https://github.com/fscarmen/warp), [enthusiastic CF netizens ](https://github.com/badafans) provides warp endpoint preferred IP script and registration procedure
