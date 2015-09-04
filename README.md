# ss-plus
## Overview
[ss plus](https://github.com/angusding/ss-plus) for OpenWrt is an improved editon from [shadowsocks-libev plus](https://github.com/angusding/shadowsocks-libev-plus), which enhanced editon extended from [shadowsocks-libev](https://github.com/shadowsocks/shadowsocks-libev). It supports transparent proxy based on extensible custom list and updatable gfwlist, and fast DNS response.
## Installation
### OpenWrt

    # Get source (At OpenWRT build root)
    pushd package
    git clone https://github.com/angusding/ss-plus.git
    popd  
    # Enable ss-plus ("Network" category and "Web Servers/Proxies" submenu)
    make menuconfig 
    # Build the package
    make package/ss-plus/compile V=s
