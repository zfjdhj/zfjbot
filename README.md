# zfjbot

backup

## 说明

自用的qq机器人备份，大概会改为Linux方法部署。

## 插件列表(不定期更新)

``` python
# _bot_.py
# 启用的模块
# 初次尝试部署时请先保持默认
# 如欲启用新模块，请认真阅读部署说明，逐个启用逐个配置
# 切忌一次性开启多个
MODULES_ON = {
# ============Start=============
# ============会战============
    'yobot',
    #'clanbattle_info',
    'filter_knife',
    '合刀',
    'groupmaster',
    'botmanage', # bot管理
    'bot_manager_web',
    'YoCool-Console',
# ============查询============
    'priconne',
    'epck',
    'clanbattle_report',
    'pcr_calendar',
    'pcrjjc',
    'zfjbot-jjc-finder',
    'birthday',
    'zfjbot-help-search',
    'zfjbot-yobotdb',
# ============娱乐============
    'eqa',
    'memegenerator',# 表情包生成器
    'snitchgenerator',# 内鬼表情生成器
    'shitu',
    'music',
    'portune',
    'fgoavatarguess',
    'arkavatarguess',
    'voiceguess',
    'russian',
    'translate',
    'pcr-record',
    'pokemanpcr',
    'pcrsealkiller',
    'rss',
    'NGWordGame',
    'generator',
    'hiumsentences',
    'nowtime',
    'zfjbot-ascii_art',
    'pcravatarfind',
    'pcr_duel',
# =========实验性功能=========
    'zfjbot',
    'zfjbot-mimikko',
    'check',
    'zfjbot-arena',
# ==========关于涩图==========
    'shebot',
    'setu_mix',
# ============End=============
    }
 ```

## 插件帮助页面

<https://zfjdhj.github.io/zfjbot-helpWebsite/>