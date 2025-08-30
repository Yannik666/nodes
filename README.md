# FreeProxiesScraper

Fork from TopFreeProxies.

## 仓库介绍
本仓库自动化功能全部基于 `GitHub Actions` 实现，如有需要可以自行 Fork 实现个性化需求，功能配置在 `./utils/config.ini` 配置文件中。

对网络上各免费节点池及博主分享的节点进行测速筛选出较为稳定高速的节点，再导入到仓库中进行分享记录。所筛选的节点链接在仓库 `./sub/sub_list.json` 文件中，其中大部分为其他 `GitHub` 仓库链接，如果大家有好的订阅链接欢迎提交 PR ，这些链接包含的所有节点会合并在仓库 `./sub/sub_merge.txt` 中。

测速筛选后的节点订阅文件在仓库根目录 `Eterniy`(Base64) 和 `Eternity.yaml`(Clash)。同时在仓库的 `./update` 中保留了原始节点链接的的记录。

订阅转换使用 [subconverter](https://github.com/tindy2013/subconverter) 实现，测速功能使用 [LiteSpeedTest](https://github.com/xxf098/LiteSpeedTest) 在 `GitHub Actions` 环境下实现，所以美国节点较多，不能很好代表国内网络环境下节点可用性，目前正在解决这一问题。

虽然是测速筛选过后的节点，但仍然会出现部分节点不可用的情况，遇到这种情况建议选择`Clash`, `Shadowrocket`之类能自动切换低延迟节点的客户端。

## 使用方法
将以下订阅链接导入相应客户端即可。链接中大部分为 SS 协议节点，少量 Vmess, Trojan ,SSR 协议节点，建议选择协议支持完整的客户端。

- [多协议Base64编码](https://raw.githubusercontent.com/caijh/FreeProxiesScraper/master/Eternity)
- [Clash](https://raw.githubusercontent.com/caijh/FreeProxiesScraper/master/Eternity.yaml)

>`Clash`链接所使用的配置在仓库`./update/provider/`中，有相应配置文件和以国家分类的`proxy-provider`。
>
>需要其它配置可使用订阅转换工具自行转换。
>自用在线订阅转换网址：[sub-web-modify](https://sub.v1.mk/)

## 节点信息
### 高速节点
高速节点数量: `35`
<details>
  <summary>展开复制节点</summary>

    trojan://ttfang@193.9.49.194:2096?allowInsecure=1&sni=ttfang.fange.me&ws=1&wspath=%2525252FTelegram%252525F0%2525259F%25252587%252525A8%252525F0%2525259F%25252587%252525B3#05-0002-RELAY
    trojan://ttfang@185.193.30.194:2096?allowInsecure=1&sni=ttfang.fange.me&ws=1&wspath=%2525252FTelegram%252525F0%2525259F%25252587%252525A8%252525F0%2525259F%25252587%252525B3#05-0003-RELAY
    vmess://eyJ2IjoiMiIsInBzIjoiMDUtMDAwNC1SRUxBWSIsImFkZCI6ImxpbnV4LmRvIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiIyZmJlNDFkYi0wNzk3LTQ0ZjYtYTNlYi05YzY4MGU1ZjA5Y2UiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzJmYmU0MWRiLTA3OTctNDRmNi1hM2ViLTljNjgwZTVmMDljZS12bSIsImhvc3QiOiJsaW51eC5kbyIsInRscyI6InRscyJ9
    trojan://ttfang@86.38.214.216:2096?allowInsecure=1&sni=ttfang.fange.me&ws=1&wspath=%2525252F%2525252FTelegram#05-0005-RELAY
    vmess://eyJ2IjoiMiIsInBzIjoiMDUtMDAyMS1FUyIsImFkZCI6IjE4NS4yMzYuMjYuMTExIiwicG9ydCI6IjMyMDIwIiwidHlwZSI6Im5vbmUiLCJpZCI6Ijc4YjRmYjU3LTM5ZDctNGU5ZC1kZDM4LWM5YTM4MzIyYmNiMiIsImFpZCI6IjAiLCJuZXQiOiJ0Y3AiLCJwYXRoIjoiJTI1MjUyRiUyNTI1MkZUZWxlZ3JhbSIsImhvc3QiOiJ0dGZhbmcuZmFuZ2UubWUiLCJ0bHMiOiIifQ==
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpxc2NhdkY1VXZpSUwtOFYtRTRyYUJB@91.84.104.133:2222#05-0024-NL
    trojan://tg-fq521free@194.76.18.129:443?allowInsecure=1&sni=torjan.xn--xhq44j.eu.org&ws=1&wspath=%2525252F#06-0032-KZ
    trojan://ttfang@86.38.214.194:2096?allowInsecure=1&sni=ttfang.fange.me&ws=1&wspath=%2525252FTelegramU0001F1E8U0001F1F3#06-0035-RELAY
    trojan://tg-fq521free@45.67.215.95:443?allowInsecure=1&sni=torjan.xn--xhq44j.eu.org&ws=1&wspath=%2525252F#06-0048-RU
    trojan://tg-fq521free@216.24.57.30:443?allowInsecure=1&sni=torjan.xn--xhq44j.eu.org&ws=1&wspath=%2525252F#06-0058-US
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpOazlhc2dsRHpIemprdFZ6VGt2aGFB@arxfw2b78fi2q9hzylhn.freesocks.work:443#08-0062-VN
    vmess://eyJ2IjoiMiIsInBzIjoiMDgtMDA2My1DTiIsImFkZCI6InY0LmhlZHVpYW4ubGluayIsInBvcnQiOiIzMDgwNCIsInR5cGUiOiJub25lIiwiaWQiOiJjYmIzZjg3Ny1kMWZiLTM0NGMtODdhOS1kMTUzYmZmZDU0ODQiLCJhaWQiOiIyIiwibmV0Ijoid3MiLCJwYXRoIjoiL29vb28iLCJob3N0IjoidjQuaGVkdWlhbi5saW5rIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiMDgtMDA2NC1SRUxBWSIsImFkZCI6ImI2MmE5NDhjLWZhYTItNGU4YS1iZjhhLTNmZjMxMjFjODc1YS5hc291bC1hdmEudG9wIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiI1ZjcyNmZlMy1kODJlLTRkYTUtYTcxMS04YWYwY2JiMmI2ODIiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2F6dW1hc2UucmVuIiwiaG9zdCI6ImI2MmE5NDhjLWZhYTItNGU4YS1iZjhhLTNmZjMxMjFjODc1YS5hc291bC1hdmEudG9wIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiMDgtMDA2Ni1DTiIsImFkZCI6InY4LmhlZHVpYW4ubGluayIsInBvcnQiOiIzMDgwOCIsInR5cGUiOiJub25lIiwiaWQiOiJjYmIzZjg3Ny1kMWZiLTM0NGMtODdhOS1kMTUzYmZmZDU0ODQiLCJhaWQiOiIyIiwibmV0Ijoid3MiLCJwYXRoIjoiL29vb28iLCJob3N0IjoidjguaGVkdWlhbi5saW5rIiwidGxzIjoiIn0=
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@46.183.184.60:989#08-0067-HR
    vmess://eyJ2IjoiMiIsInBzIjoiMDgtMDA2OC1DTiIsImFkZCI6InYyNC5oZWR1aWFuLmxpbmsiLCJwb3J0IjoiMzA4MjQiLCJ0eXBlIjoibm9uZSIsImlkIjoiY2JiM2Y4NzctZDFmYi0zNDRjLTg3YTktZDE1M2JmZmQ1NDg0IiwiYWlkIjoiMiIsIm5ldCI6IndzIiwicGF0aCI6Ii9vb29vIiwiaG9zdCI6InYyNC5oZWR1aWFuLmxpbmsiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiMDgtMDA2OS1DTiIsImFkZCI6IjQ3LjEwNC4xODYuMTMzIiwicG9ydCI6IjUwMDAyIiwidHlwZSI6Im5vbmUiLCJpZCI6IjQxODA0OGFmLWEyOTMtNGI5OS05YjBjLTk4Y2EzNTgwZGQyNCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo5dHFoTWRJclRrZ1E0NlB2aHlBdE1I@switcher-nick-croquet.freesocks.work:443#08-0070-NL
    vmess://eyJ2IjoiMiIsInBzIjoiMDgtMDA3MS1DTiIsImFkZCI6InYzNi5oZWR1aWFuLmxpbmsiLCJwb3J0IjoiMzA4MzYiLCJ0eXBlIjoibm9uZSIsImlkIjoiY2JiM2Y4NzctZDFmYi0zNDRjLTg3YTktZDE1M2JmZmQ1NDg0IiwiYWlkIjoiMiIsIm5ldCI6IndzIiwicGF0aCI6Ii9vb29vIiwiaG9zdCI6InYzNi5oZWR1aWFuLmxpbmsiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiMDgtMDA3Mi1DTiIsImFkZCI6InYzNS5oZWR1aWFuLmxpbmsiLCJwb3J0IjoiMzA4MzUiLCJ0eXBlIjoibm9uZSIsImlkIjoiY2JiM2Y4NzctZDFmYi0zNDRjLTg3YTktZDE1M2JmZmQ1NDg0IiwiYWlkIjoiMiIsIm5ldCI6IndzIiwicGF0aCI6Ii9vb29vIiwiaG9zdCI6InYzNS5oZWR1aWFuLmxpbmsiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiMDgtMDA3My1SRUxBWSIsImFkZCI6InJhazFkaW5nLjg5MDYwMDA0Lnh5eiIsInBvcnQiOiIyMDgzIiwidHlwZSI6Im5vbmUiLCJpZCI6Ijc1ZDk2MzY1LTEyMjktNGZjNC1kYmRhLTg1NTcxN2Y4NzZjZiIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6InJhazFkaW5nLjg5MDYwMDA0Lnh5eiIsInRscyI6InRscyJ9
    ss://YWVzLTI1Ni1jZmI6cXdlclJFV1ElMjU0MCUyNTQw@p141.panda001.net:4652#08-0074-KR
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@38.165.233.93:989#08-0075-PY
    vmess://eyJ2IjoiMiIsInBzIjoiMDgtMDA3Ni1DTiIsImFkZCI6InY5LmhlZHVpYW4ubGluayIsInBvcnQiOiIzMDgwOSIsInR5cGUiOiJub25lIiwiaWQiOiJjYmIzZjg3Ny1kMWZiLTM0NGMtODdhOS1kMTUzYmZmZDU0ODQiLCJhaWQiOiIyIiwibmV0Ijoid3MiLCJwYXRoIjoiL29vb28iLCJob3N0IjoidjkuaGVkdWlhbi5saW5rIiwidGxzIjoiIn0=
    ss://cmM0LW1kNToxNGZGUHJiZXpFM0hEWnpzTU9yNg@23.251.121.242:8080#08-0077-UStrojan%2F%2Fttfang%40185.207.197.1942096%3FallowInsecure%3D1%26sni%3Dttfang.fange.me%26ws%3D1%26wspath%3DTelegram%2525F0%25259F%252587%2525A8%2525F0%25259F%252587%2525B3%2308-0090-RELAY
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpKSWhONnJCS2thRWJvTE5YVlN2NXJx@ca225.vpnbook.com:80#08-0078-CA
    vmess://eyJ2IjoiMiIsInBzIjoiMDgtMDA3OS1SRUxBWSIsImFkZCI6IjEwNC4xNi40MC4xNTQiLCJwb3J0IjoiMjA4MiIsInR5cGUiOiJub25lIiwiaWQiOiIzN2Q4Yzk5Mi02MTcwLTQwZTktODlkZC1lOWEyNjQ3MjIzZjgiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3dzP2VkPTIwNDgiLCJob3N0IjoiIiwidGxzIjoiIn0=
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@43.201.24.53:443#08-0080-KR
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@43.201.56.52:443#08-0081-KR
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpiYTg5YjEyYS1iNTBiLTQ1YTEtYmE2Yi0wMTgxZjI0ZmQ2OGI@shct.pkyun.xyz:51706#08-0082-US
    trojan://ttfang@199.34.228.194:2096?allowInsecure=1&sni=ttfang.fange.me&ws=1&wspath=Telegram%252525F0%2525259F%25252587%252525A8%252525F0%2525259F%25252587%252525B3#08-0084-US
    vmess://eyJ2IjoiMiIsInBzIjoiMDgtMDA4NS1SRUxBWSIsImFkZCI6IjE3Mi42Ni40NS4zNCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzJlN2EwYzYtNjAzNC00OWMyLThlMjUtNGFhNTkyYWZkNzE5IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii85aXF2eTRhMGJaIiwiaG9zdCI6IiIsInRscyI6InRscyJ9
    vmess://eyJ2IjoiMiIsInBzIjoiMDgtMDA4Ny1SRUxBWSIsImFkZCI6IjEwNC4yMS4yMjUuMTkzIiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjcwMjI5ODJmLWRhNGMtNDhjOS1jNjYwLWIyMzE1YWJkY2Y3ZSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiMDgtMDA4OS1SRUxBWSIsImFkZCI6IjEwNC4xNi42MC44IiwicG9ydCI6IjIwOTUiLCJ0eXBlIjoibm9uZSIsImlkIjoiMDU2NDFjZjUtNThkMi00YmE0LWE5ZjEtYjNjZGEwYjFmYjFkIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9vYmRpaS5jZmQvbGlua3dzIiwiaG9zdCI6IiIsInRscyI6IiJ9
    


</details>

### 所有节点
合并节点总数: `36`
[节点链接](https://raw.githubusercontent.com/caijh/TopFreeProxies/master/sub/sub_merge_base64.txt)

### 节点来源
- [clashnode](https://github.com/imyaoxp/clashnode), 节点数量: `36`


## 仓库声明
订阅节点仅作学习交流使用，只是对网络上节点的优选排序，用于查找资料，学习知识，不做任何违法行为。所有资源均来自互联网，仅供大家交流学习使用，出现违法问题概不负责。

