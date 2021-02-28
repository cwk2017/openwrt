<a href="#readme">
    <img src="https://img.vim-cn.com/db/018fac69e39167b5a6f692dfe5b715eccf2960.jpg" alt="图裂了😂" title="OpenWrt-DIY" align="right" height="180" />
</a>

OpenWrt DIY — 多设备固件云编译 <br/>
[这个是转载这位大佬](https://github.com/IvanSolis1989/OpenWrt-DIY) <br/>
https://github.com/IvanSolis1989/OpenWrt-DIY<br/>
======================

[![](https://img.shields.io/badge/-目录:-696969.svg)](#readme) [![](https://img.shields.io/badge/-固件下载-FFFFFF.svg)](#固件下载-) [![](https://img.shields.io/badge/-基本介绍-FFFFFF.svg)](#基本介绍-) [![](https://img.shields.io/badge/-近期更新-FFFFFF.svg)](#近期更新-)  [![](https://img.shields.io/badge/-鸣谢-FFFFFF.svg)](#鸣谢-)

请 `认真阅读完毕` 本页面，本页面包含如何提升固件下载及使用体验的内容。

如果您未阅读完本页面，可能会遇到 `固件下载问题` ，若遇到问题，请 `返回此页面，认真完整阅读一遍`~

## 固件下载 [![](https://img.shields.io/badge/-支持设备、编译状态及固件下载-FFFFFF.svg)](#固件下载-)
<details>
 <summary><b>&nbsp;&nbsp;&nbsp; X86  设备编译状态及固件下载</b></summary>
    
<br/>
 
**点击下表中 [![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/cwk2017/openwrt/actions) 即可跳转到该设备固件下载页面** 
|   序号    |     X86设备  |   X86设备编译状态及下载链接 |   插件配置   | 备注说明   |
| :-----------------: | :-------------: |:-----------------: | :-----------------: |  :-----------------: | 
| 1 |   [![](https://img.shields.io/badge/OpenWrt-x86_(64位)-FFFFFF.svg)](https://github.com/cwk2017/openwrt/blob/main/.github/workflows/x86_64.yml)    | [![](https://github.com/cwk2017/openwrt/workflows/Build%20X86(64bit)%20OpenWrt/badge.svg)](https://github.com/cwk2017/openwrt/actions/workflows/x86_64.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/cwk2017/openwrt/blob/main/config/X86/x86-extra.config) |  |  
| 2 |    [![](https://img.shields.io/badge/OpenWrt-x86_(32位)-FFFFFF.svg)](https://github.com/cwk2017/openwrt/blob/main/.github/workflows/x86.yml)     |[![](https://github.com/cwk2017/openwrt/workflows/Build%20X86(32bit)%20OpenWrt/badge.svg)](https://github.com/cwk2017/openwrt/actions/workflows/x86.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/cwk2017/openwrt/blob/main/config/X86/x86-extra.config) | | 

**提示：**[![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/cwk2017/openwrt/actions) 标志为正常，[![](https://img.shields.io/badge/设备-failing-DC143C.svg)](https://github.com/cwk2017/openwrt/actions) 或 [![](https://img.shields.io/badge/设备-no_status-A9A9A9.svg)](https://github.com/cwk2017/openwrt/actions) 不代表所有编译均失败。请点击 [![](https://img.shields.io/badge/设备-状态-32CD32.svg)](https://github.com/cwk2017/openwrt/actions) 到 **Actions** 进一步查看。

</details>

<details>
 <summary><b>&nbsp;&nbsp;&nbsp; ARM 设备编译状态及固件下载</b></summary>
    
<br/>
 
**点击下表中 [![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/cwk2017/openwrt/actions) 即可跳转到该设备固件下载页面** 
|    序号   |     ARM设备    |   ARM设备编译状态及下载链接 |   插件配置   | 备注说明   |
| :-----------------: | :-------------: |:-----------------: | :-----------------: |  :-----------------: | 
| 1 |       [![](https://img.shields.io/badge/OpenWrt-N1_盒子-FFFFFF.svg)](https://github.com/cwk2017/openwrt/blob/main/.github/workflows/N1.yml)         |[![](https://github.com/cwk2017/openwrt/workflows/Build%20N1%20OpenWrt/badge.svg)](https://github.com/cwk2017/openwrt/actions/workflows/N1.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/cwk2017/openwrt/blob/main/config/ARM/arm-mini-extra.config)  | | 
| 2 |    [![](https://img.shields.io/badge/OpenWrt-树莓派_3B/3B+-FFFFFF.svg)](https://github.com/cwk2017/openwrt/blob/main/.github/workflows/raspberrypi3.yml)   | [![](https://github.com/cwk2017/openwrt/workflows/Build%20RaspBerryPi3%20OpenWrt/badge.svg)](https://github.com/cwk2017/openwrt/actions/workflows/raspberrypi3.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/cwk2017/openwrt/blob/main/config/ARM/arm-extra.config) | 含 USB 网卡驱动 |
| 3 |    [![](https://img.shields.io/badge/OpenWrt-树莓派_4B-FFFFFF.svg)](https://github.com/cwk2017/openwrt/blob/main/.github/workflows/raspberrypi4.yml)    | [![](https://github.com/cwk2017/openwrt/workflows/Build%20RaspBerryPi4%20OpenWrt/badge.svg)](https://github.com/cwk2017/openwrt/actions/workflows/raspberrypi4.yml)  |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/cwk2017/openwrt/blob/main/config/ARM/arm-extra.config)  | 含 USB 网卡驱动 |
|4|      [![](https://img.shields.io/badge/OpenWrt-NanoPi_R2S-FFFFFF.svg)](https://github.com/cwk2017/openwrt/blob/main/.github/workflows/r2s.yml)     |  [![](https://github.com/cwk2017/openwrt/workflows/Build%20NanoPi%20R2S%20OpenWrt/badge.svg)](https://github.com/cwk2017/openwrt/actions/workflows/r2s.yml)  |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/cwk2017/openwrt/blob/main/config/ARM/arm-extra.config)  | ZIP 解压后刷写 |
| 5|      [![](https://img.shields.io/badge/OpenWrt-NanoPi_R4S_1G-FFFFFF.svg)](https://github.com/cwk2017/openwrt/blob/main/.github/workflows/r4s-1g.yml)<br/>[![](https://img.shields.io/badge/OpenWrt-NanoPi_R4S_4G-FFFFFF.svg)](https://github.com/cwk2017/openwrt/blob/main/.github/workflows/r4s-4g.yml)       |  [![](https://github.com/cwk2017/openwrt/workflows/Build%20NanoPi%20R4S%201Gb%20OpenWrt/badge.svg)](https://github.com/cwk2017/openwrt/actions/workflows/r4s-1g.yml)<br/>[![](https://github.com/cwk2017/openwrt/workflows/Build%20NanoPi%20R4S%204Gb%20OpenWrt/badge.svg)](https://github.com/cwk2017/openwrt/actions/workflows/r4s-4g.yml)  |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/cwk2017/openwrt/blob/main/config/ARM/arm-extra.config)<br/>[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/cwk2017/openwrt/blob/main/config/ARM/arm-extra.config)  | ZIP 解压后刷写 |
| 6|     [![](https://img.shields.io/badge/OpenWrt-Amlogic_S905X3-FFFFFF.svg)](https://github.com/cwk2017/openwrt/blob/main/.github/workflows/S905x3.yml)   | [![](https://github.com/cwk2017/openwrt/workflows/Build%20Amlogic%20S905X3%20OpenWrt/badge.svg)](https://github.com/cwk2017/openwrt/actions/workflows/S905x3.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/cwk2017/openwrt/blob/main/config/ARM/arm-extra.config) |   |
| 7|     [![](https://img.shields.io/badge/OpenWrt-香橙派_Zero_Plus-FFFFFF.svg)](https://github.com/cwk2017/openwrt/blob/main/.github/workflows/opzp.yml)   | [![](https://github.com/cwk2017/openwrt/workflows/Build%20Orange%20Pi%20Zero%20Plus%20OpenWrt/badge.svg)](https://github.com/cwk2017/openwrt/actions/workflows/opzp.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/cwk2017/openwrt/blob/main/config/ARM/arm-acme-mini-extra.config) |   |
|8|       [![](https://img.shields.io/badge/OpenWrt-斐讯_K3-FFFFFF.svg)](https://github.com/cwk2017/openwrt/blob/main/.github/workflows/K3.yml)           |[![](https://github.com/cwk2017/openwrt/workflows/Build%20PHICOMM%20K3%20OpenWrt/badge.svg)](https://github.com/cwk2017/openwrt/actions/workflows/K3.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/cwk2017/openwrt/blob/main/config/ARM/k3.config)  |  | 
|9|       [![](https://img.shields.io/badge/OpenWrt-Linksys_Wrt1900acs-FFFFFF.svg)](https://github.com/cwk2017/openwrt/blob/main/.github/workflows/linksys_wrt1900acs.yml)           |[![](https://github.com/cwk2017/openwrt/workflows/Build%20Linksys%20Wrt1900acs%20OpenWrt/badge.svg)](https://github.com/cwk2017/openwrt/actions/workflows/linksys_wrt1900acs.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/cwk2017/openwrt/blob/main/config/ARM/linksys-extra.config)  |  | 
|10|       [![](https://img.shields.io/badge/OpenWrt-Linksys_Wrt3200acm-FFFFFF.svg)](https://github.com/cwk2017/openwrt/blob/main/.github/workflows/linksys_wrt3200acm.yml)           |[![](https://github.com/cwk2017/openwrt/workflows/Build%20Linksys%20Wrt3200acm%20OpenWrt/badge.svg)](https://github.com/cwk2017/openwrt/actions/workflows/linksys_wrt3200acm.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/cwk2017/openwrt/blob/main/config/ARM/linksys-extra.config)  |  | 
|11|       [![](https://img.shields.io/badge/OpenWrt-Linksys_Wrt32x-FFFFFF.svg)](https://github.com/cwk2017/openwrt/blob/main/.github/workflows/linksys_wrt32x.yml)           |[![](https://github.com/cwk2017/openwrt/workflows/Build%20Linksys%20Wrt32x%20OpenWrt/badge.svg)](https://github.com/cwk2017/openwrt/actions/workflows/linksys_wrt32x.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/cwk2017/openwrt/blob/main/config/ARM/linksys-extra.config)  |  | 

**提示：**[![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/cwk2017/openwrt/actions) 标志为正常，[![](https://img.shields.io/badge/设备-failing-DC143C.svg)](https://github.com/cwk2017/openwrt/actions) 或 [![](https://img.shields.io/badge/设备-no_status-A9A9A9.svg)](https://github.com/cwk2017/openwrt/actions) 不代表所有编译均失败。请点击 [![](https://img.shields.io/badge/设备-状态-32CD32.svg)](https://github.com/cwk2017/openwrt/actions) 到 **Actions** 进一步查看。

</details>

<details>
 <summary><b>&nbsp;&nbsp;&nbsp; 高通 设备编译状态及固件下载</b></summary>
    
<br/>

**点击下表中 [![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/cwk2017/openwrt/actions) 即可跳转到该设备固件下载页面** 
|    序号   |     高通平台     |   高通设备编译状态及下载链接 |   插件配置   | 备注说明   |
| :-----------------: | :-------------: |:-----------------: | :-----------------: |  :-----------------: | 
| 1 |        [![](https://img.shields.io/badge/OpenWrt-竞斗云-FFFFFF.svg)](https://github.com/cwk2017/openwrt/blob/main/.github/workflows/gdock.yml)         |[![](https://github.com/cwk2017/openwrt/workflows/Build%20G-Dock%20OpenWrt/badge.svg)](https://github.com/cwk2017/openwrt/actions/workflows/gdock.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/cwk2017/openwrt/blob/main/config/Qualcomm/Qualcomm-extra.config)  | | 
| 2|     [![](https://img.shields.io/badge/OpenWrt-网件_R7800-FFFFFF.svg)](https://github.com/cwk2017/openwrt/blob/main/.github/workflows/R7800.yml)   | [![](https://github.com/cwk2017/openwrt/workflows/Build%20Netgear%20R7800%20OpenWrt/badge.svg)](https://github.com/cwk2017/openwrt/actions/workflows/R7800.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/cwk2017/openwrt/blob/main/config/Qualcomm/Qualcomm-mini-extra.config) |   | 
| 3|     [![](https://img.shields.io/badge/OpenWrt-星际宝盒_CM520-FFFFFF.svg)](https://github.com/cwk2017/openwrt/blob/main/.github/workflows/CM520.yml)   | [![](https://github.com/cwk2017/openwrt/workflows/Build%20MobiPromo%20CM520%20OpenWrt/badge.svg)](https://github.com/cwk2017/openwrt/actions/workflows/CM520.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/cwk2017/openwrt/blob/main/config/Qualcomm/Qualcomm-extra.config) |   |
| 4 |        [![](https://img.shields.io/badge/OpenWrt-斐讯_K2T-FFFFFF.svg)](https://github.com/cwk2017/openwrt/blob/main/.github/workflows/K2T.yml)           | [![](https://github.com/cwk2017/openwrt/workflows/Build%20PHICOMM%20K2T%20OpenWrt/badge.svg)](https://github.com/cwk2017/openwrt/actions/workflows/K2T.yml)|[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/cwk2017/openwrt/blob/main/config/Qualcomm/Qualcomm-mini-extra.config) | |

**提示：**[![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/cwk2017/openwrt/actions) 标志为正常，[![](https://img.shields.io/badge/设备-failing-DC143C.svg)](https://github.com/cwk2017/openwrt/actions) 或 [![](https://img.shields.io/badge/设备-no_status-A9A9A9.svg)](https://github.com/cwk2017/openwrt/actions) 不代表所有编译均失败。请点击 [![](https://img.shields.io/badge/设备-状态-32CD32.svg)](https://github.com/cwk2017/openwrt/actions) 到 **Actions** 进一步查看。

</details>

<details>
 <summary><b>&nbsp;&nbsp;&nbsp; MIPS 设备编译状态及固件下载</b></summary>
    
<br/>

**注意：考虑到 MIPS 设备的 CPU 性能及 RAM/ROM 量配置，功能较其他设备做了很大范围的删减。**

**MIPS 设备推荐使用 Padavan 固件：**  [![](https://img.shields.io/badge/-Padavan_固件仓库_1-FFFFFF.svg)](https://github.com/hanwckf/rt-n56u) [![](https://img.shields.io/badge/-Padavan_固件仓库_2-FFFFFF.svg)](https://opt.cn2qq.com/padavan/) [![](https://img.shields.io/badge/-Padavan_固件仓库_3-FFFFFF.svg)](https://github.com/gorden5566/padavan)

**点击下表中 [![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/cwk2017/openwrt/actions) 即可跳转到该设备固件下载页面** 
|    序号   |     MIPS设备     |   MIPS设备编译状态及下载链接 |   插件配置   | 备注说明   |
| :-----------------: | :-------------: |:-----------------: | :-----------------: |  :-----------------: | 
| 1 |        [![](https://img.shields.io/badge/OpenWrt-极路由_B70-FFFFFF.svg)](https://github.com/cwk2017/openwrt/blob/main/.github/workflows/B70.yml)        |[![](https://github.com/cwk2017/openwrt/workflows/Build%20HiWiFi%20B70%20OpenWrt/badge.svg)](https://github.com/cwk2017/openwrt/actions/workflows/B70.yml)|[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/cwk2017/openwrt/blob/main/config/MIPS/MIPS-extra.config) | |
|2|        [![](https://img.shields.io/badge/OpenWrt-斐讯_K2P-FFFFFF.svg)](https://github.com/cwk2017/openwrt/blob/main/.github/workflows/K2P.yml)           |[![](https://github.com/cwk2017/openwrt/workflows/Build%20PHICOMM%20K2P%20OpenWrt/badge.svg)](https://github.com/cwk2017/openwrt/actions/workflows/K2P.yml)|[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/cwk2017/openwrt/blob/main/config/MIPS/MIPS-extra.config) | |
| 3|    [![](https://img.shields.io/badge/OpenWrt-红米_AC2100-FFFFFF.svg)](https://github.com/cwk2017/openwrt/blob/main/.github/workflows/redmi_ac2100.yml)     | [![](https://github.com/cwk2017/openwrt/workflows/Build%20Redmi%20AC2100%20OpenWrt/badge.svg)](https://github.com/cwk2017/openwrt/actions/workflows/redmi_ac2100.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/cwk2017/openwrt/blob/main/config/MIPS/MIPS-extra.config) | | 
| 4 |    [![](https://img.shields.io/badge/OpenWrt-Newifi3_D2-FFFFFF.svg)](https://github.com/cwk2017/openwrt/blob/main/.github/workflows/Newifi_D2.yml)      |  [![](https://github.com/cwk2017/openwrt/workflows/Build%20Newifi%20D2%20OpenWrt/badge.svg)](https://github.com/cwk2017/openwrt/actions/workflows/Newifi_D2.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/cwk2017/openwrt/blob/main/config/MIPS/MIPS-extra.config)  | | 
|5|     [![](https://img.shields.io/badge/OpenWrt-小娱_C5-FFFFFF.svg)](https://github.com/cwk2017/openwrt/blob/main/.github/workflows/xiaoyu_xy-c5.yml)        | [![](https://github.com/cwk2017/openwrt/workflows/Build%20XiaoYu%20XY-C5%20OpenWrt/badge.svg)](https://github.com/cwk2017/openwrt/actions/workflows/xiaoyu_xy-c5.yml)   |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/cwk2017/openwrt/blob/main/config/MIPS/MIPS-extra.config)  |  |
| 6|     [![](https://img.shields.io/badge/OpenWrt-小米_R3G-FFFFFF.svg)](https://github.com/cwk2017/openwrt/blob/main/.github/workflows/R3G.yml)   | [![](https://github.com/cwk2017/openwrt/workflows/Build%20Mi%20R3G%20OpenWrt/badge.svg)](https://github.com/cwk2017/openwrt/actions/workflows/R3G.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/cwk2017/openwrt/blob/main/config/MIPS/MIPS-extra.config) |   |
| 8|     [![](https://img.shields.io/badge/OpenWrt-小米_R3P-FFFFFF.svg)](https://github.com/cwk2017/openwrt/blob/main/.github/workflows/R3P.yml)   | [![](https://github.com/cwk2017/openwrt/workflows/Build%20Mi%20R3P%20OpenWrt/badge.svg)](https://github.com/cwk2017/openwrt/actions/workflows/R3P.yml) |[![](https://img.shields.io/badge/编译-配置-orange.svg)](https://github.com/cwk2017/openwrt/blob/main/config/MIPS/MIPS-extra.config) |   |

**提示：**[![](https://img.shields.io/badge/设备-passing-32CD32.svg)](https://github.com/cwk2017/openwrt/actions) 标志为正常，[![](https://img.shields.io/badge/设备-failing-DC143C.svg)](https://github.com/cwk2017/openwrt/actions) 或 [![](https://img.shields.io/badge/设备-no_status-A9A9A9.svg)](https://github.com/cwk2017/openwrt/actions) 不代表所有编译均失败。请点击 [![](https://img.shields.io/badge/设备-状态-32CD32.svg)](https://github.com/cwk2017/openwrt/actions) 到 **Actions** 进一步查看。

</details>

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-FFFFFF.svg" alt="图裂了😂" title="返回顶部" align="right"/>
</a>

## 基本介绍 [![](https://img.shields.io/badge/-项目基本介绍-FFFFFF.svg)](#基本介绍-)

1. 默认引用[ Lean 的 OpenWrt 库](https://github.com/coolsnowwolf/lede)（部分设备整合[ Lienol 的 Packages 库](https://github.com/Lienol/openwrt-packages)），因为他的 [README](https://github.com/coolsnowwolf/lede/blob/master/README.md) 影响了我开始学习编译；Github Actions 自动云编译代码采用 [P3TERX 的 Actions-OpenWrt 库 ](https://github.com/P3TERX/Actions-OpenWrt)。

2. [插件及功能预览 请点击查看](https://github.com/cwk2017/openwrt/wiki/OpenWrt-DIY%E6%8F%92%E4%BB%B6%E9%A2%84%E8%A7%88)

3. `每周五查询大雕源码是否有更新`，如有更新自动拉取最新源码和第三方软件包项目自动编译（根据设备不同编译时间在1~5个小时），`固件包含必要驱动及常用插件`（各设备的 config 借鉴大雕设置及根据网友需求调整），未逐一经过实机测试，故 `不保证 100% 可靠性`；

4. 如有什么问题、需要增加编译设备或者编译文件配置需要调整的，**可以直接在 [Issues](https://github.com/cwk2017/openwrt/issues) 内留言**。 我会不定时的根据大家的要求修改`编译配置，插件选项，增加编译设备`等；

5. 为了让更多朋友的设备能用上稳定且功能强大的 OpenWrt 固件，并保持持续更新。也希望动手能力强的朋友去学习编译[（后文有教程）](#小贴士-)，然后根据你自己的需要配置 menuconfig，把配置好的 config 文件提交到本项目，可以根据使用者的需求扩充更多设备。

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-FFFFFF.svg" alt="图裂了😂" title="返回顶部" align="right"/>
</a>

## 近期更新 [![](https://img.shields.io/badge/-近期固件更新-FFFFFF.svg)](#近期更新-)

1. 采用 [Argon 主题](https://github.com/jerrykuku/luci-theme-argon)，界面更美丽。

<details>
 <summary>&nbsp;&nbsp;&nbsp; Argon 主题效果图</summary>
   
<br/>
    
<img src="https://raw.githubusercontent.com/jerrykuku/staff/master/argon2.gif" alt="图裂了😂需要机场才能正常显示"/><br/>
<img src="https://img.vim-cn.com/65/37b71b446767d67c388b9507fb9cbf2f1d4462.jpg" alt="图裂了😂需要机场才能正常显示"/><br/> 
</details>

2. **不再定时编译**，所有设备改为每周五查询大雕源码是否有更新，有更新就自动编译，无更新编译就会自动延迟到下周五。

3. **默认 IP 调整为：192.168.10.1，默认密码：password。**

<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-FFFFFF.svg" alt="图裂了😂" title="返回顶部" align="right"/>
</a>

<br>

## 鸣谢 [![](https://img.shields.io/badge/-跪谢各大佬-FFFFFF.svg)](#鸣谢-)
 
[OpenWrt 官方库](https://github.com/openwrt/openwrt)

[P3TERX 的 Action 库](https://github.com/P3TERX/Actions-OpenWrt)

[Lean 的 OpenWrt 库](https://github.com/coolsnowwolf/lede)

[Lienol 的 Packages 库](https://github.com/Lienol/openwrt-packages)

[SuLingGG 的 OpenWrt-Rpi 库](https://github.com/SuLingGG/OpenWrt-Rpi)

###### [解决 Github 网页上图片显示失败的问题](https://blog.csdn.net/qq_38232598/article/details/91346392)


<a href="#readme">
    <img src="https://img.shields.io/badge/-返回顶部-FFFFFF.svg" alt="图裂了😂" title="返回顶部" align="right"/>
</a>
