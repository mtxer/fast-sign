#此站点为简易快速搭建实现app分发，不维护，有需要自取。
#站点配置
    1 推荐使用宝塔一键安装站点
    2 推荐使用非国内服务器(域名无需备案)
    3 使用宝塔生成域名ssl证书(ios分发必须使用https协议)

#index.html配置
    var appUrls = {
        ios: 'https://www.test.com/demo.plist',   //ios plist文件 当前域名站点 例如 https://www.test.com/demo.plist
        android: 'https://www.test.com/demo.apk',  //如果没有 则不填
    }

#demo.ipa
    替换成自己的ipa文件

#demo.apk
    替换成自己的apk文件
    
#icon.png
    替换为自己的png文件

#demo.plist配置
    查找字符串'https://www.test.com/demo.ipa' 替换为自己的 ipa 网络路径
    查找字符串'https://www.test.com/icon.png' 替换为自己的 图标 网络路径
    查找字符串'com.test.bundleID' 替换为自己的 ipa bundle ID(可不替换)
    查找字符串'这是你的应用名称' 替换为自己的 ipa 应用名称
