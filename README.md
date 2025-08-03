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
高速节点数量: `87`
<details>
  <summary>展开复制节点</summary>

    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozNjBlMjFkMjE5NzdkYzEx@45.144.49.140:57456#03-0010-PL
    ss://YWVzLTI1Ni1jZmI6WG44aktkbURNMDBJZU8lMjUyNSUyNTIzJTI1MjQlMjUyM2ZKQU10c0VBRVVPcEgvWVdZdFlxREZuVDBTVg@103.186.155.19:38388#03-0012-VN
    ss://YWVzLTI1Ni1jZmI6WG44aktkbURNMDBJZU8lMjUyNSUyNTIzJTI1MjQlMjUyM2ZKQU10c0VBRVVPcEgvWVdZdFlxREZuVDBTVg@103.186.154.22:38388#03-0013-VN
    vmess://eyJ2IjoiMiIsInBzIjoiMDUtMDAzMC1DTiIsImFkZCI6InY1LmhlZHVpYW4ubGluayIsInBvcnQiOiIzMDgwNSIsInR5cGUiOiJub25lIiwiaWQiOiJjYmIzZjg3Ny1kMWZiLTM0NGMtODdhOS1kMTUzYmZmZDU0ODQiLCJhaWQiOiIyIiwibmV0Ijoid3MiLCJwYXRoIjoiL29vb28iLCJob3N0IjoidjUuaGVkdWlhbi5saW5rIiwidGxzIjoiIn0=
    trojan://Aimer@47.239.125.132:443?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#05-0237-HK
    trojan://tg-fq521free@45.67.215.95:443?allowInsecure=1&sni=torjan.xn--xhq44j.eu.org&ws=1&wspath=%2525252F#05-0248-RU
    vmess://eyJ2IjoiMiIsInBzIjoiMDUtMDI2My1SRUxBWSIsImFkZCI6InJycnJycnJycnQuMTE4OTA2MDQueHl6IiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJmODk4ZmZjYi02NDE3LTQzNzMtOTY0MC0wYjY2MDkxZTgyMDYiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL0duSjNiQnhWOTF1RmtZdHV6WHlKNVhOZUgxUjEiLCJob3N0IjoicnJycnJycnJydC4xMTg5MDYwNC54eXoiLCJ0bHMiOiJ0bHMifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiMDUtMDI2Ni1SRUxBWSIsImFkZCI6IkRkRERkZGRkZERGcnJycnJyUlJ5LklSYW4yMDM1LmRQRG5zLk9SRyIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYTk0ZmFmZGItMTBkNi00NmMyLWJlOGEtNWMyZTgzNThmYmIwIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9Dako5QTQ2WlJIdmdXdlZjbWp5aUtWYnkyTHAiLCJob3N0IjoiRGRERGRkZGRkREZycnJycnJSUnkuSVJhbjIwMzUuZFBEbnMuT1JHIiwidGxzIjoidGxzIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiMDUtMDI2Ny1SRUxBWSIsImFkZCI6Imtsby45ODY5ODYuc2hvcCIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiYjc1Yzk3MzEtNDA4ZC00YWE2LThhZTktMzg1NzIwNTExM2ExIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9udmp4Nmo3a2JEUUlRTVp2YmVWQTkiLCJob3N0Ijoia2xvLjk4Njk4Ni5zaG9wIiwidGxzIjoidGxzIn0=
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@104.192.226.106:989#05-0302-UStrojan%2F%2FAimer%4092.243.74.2398443%3FallowInsecure%3D1%26sni%3Depga.aimercc.dpdns.org%26ws%3D1%26wspath%3D%25252F%25253Fed%25253D2560%2309-0136-RELAY
    trojan://Aimer@103.116.7.103:2083?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F%2525253Fed%2525253D2560#09-0111-RELAY
    trojan://Aimer@103.116.7.220:2096?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F%2525253Fed%2525253D2560#09-0112-RELAY
    trojan://Aimer@103.116.7.100:2087?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F%2525253Fed%2525253D2560#09-0113-RELAY
    trojan://Aimer@31.43.179.27:443?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0117-RELAY
    trojan://Aimer@154.83.2.88:2083?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F%2525253Fed%2525253D2560#09-0132-RELAY
    trojan://Aimer@92.243.74.180:8443?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F%2525253Fed%2525253D2560#09-0135-RELAY
    trojan://Aimer@167.68.4.199:2053?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F%2525253Fed%2525253D2560#09-0190-RELAY
    trojan://tg-fq521free@198.62.62.67:443?allowInsecure=1&sni=torjan.xn--xhq44j.eu.org&ws=1&wspath=%2525252F#09-0191-US
    trojan://Aimer@160.79.105.156:2083?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F%2525253Fed%2525253D2560#09-0192-US
    trojan://Aimer@198.62.62.192:2083?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0193-US
    trojan://Aimer@192.200.160.15:8443?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F%2525253Fed%2525253D2560#09-0194-US
    trojan://Aimer@192.0.54.7:443?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F%2525253Fed%2525253D2560#09-0195-US
    trojan://Aimer@161.145.150.29:2083?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F%2525253Fed%2525253D2560#09-0196-US
    trojan://Aimer@160.79.105.160:8443?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F%2525253Fed%2525253D2560#09-0197-US
    trojan://Aimer@167.68.5.248:2087?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F%2525253Fed%2525253D2560#09-0198-RELAY
    trojan://Aimer@130.250.137.63:2083?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F%2525253Fed%2525253D2560#09-0199-US
    trojan://Aimer@167.68.4.131:8443?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F%2525253Fed%2525253D2560#09-0200-RELAY
    trojan://Aimer@66.81.247.230:2096?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F%2525253Fed%2525253D2560#09-0201-RELAY
    trojan://Aimer@192.200.160.35:2083?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F%2525253Fed%2525253D2560#09-0202-US
    trojan://tg-fq521free@216.24.57.30:443?allowInsecure=1&sni=torjan.xn--xhq44j.eu.org&ws=1&wspath=%2525252F#09-0203-US
    trojan://Aimer@167.68.4.7:2053?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F%2525253Fed%2525253D2560#09-0204-RELAY
    trojan://Aimer@161.145.150.26:2087?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F%2525253Fed%2525253D2560#09-0205-US
    trojan://Aimer@135.84.64.77:2096?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F%2525253Fed%2525253D2560#09-0206-US
    trojan://Aimer@188.164.159.107:2096?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0335-RELAY
    trojan://Aimer@188.164.159.241:2096?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0336-RELAY
    trojan://Aimer@188.164.159.18:443?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0337-RELAY
    trojan://Aimer@188.164.159.55:2096?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0338-RELAY
    trojan://Aimer@188.164.159.171:443?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0339-RELAY
    trojan://Aimer@154.211.8.240:443?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0340-RELAY
    trojan://Aimer@154.211.8.227:2087?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0341-RELAY
    trojan://Aimer@154.211.8.12:2096?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0342-RELAY
    trojan://Aimer@154.197.64.189:2087?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0343-RELAY
    trojan://Aimer@154.197.64.252:443?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0344-RELAY
    trojan://Aimer@154.197.64.62:2083?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0345-RELAY
    trojan://Aimer@154.197.64.219:2083?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0346-RELAY
    trojan://Aimer@154.197.64.196:2087?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0347-RELAY
    trojan://Aimer@27.50.49.136:443?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0348-RELAY
    trojan://Aimer@27.50.49.47:2083?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0349-RELAY
    trojan://Aimer@27.50.48.115:2087?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0350-RELAY
    trojan://Aimer@27.50.49.251:2083?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0351-RELAY
    trojan://Aimer@27.50.49.209:2087?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0352-RELAY
    trojan://Aimer@27.50.49.177:8443?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0353-RELAY
    trojan://Aimer@27.50.49.242:8443?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0354-RELAY
    trojan://Aimer@144.34.231.211:443?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0355-US
    trojan://Aimer@154.21.82.84:54626?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0356-US
    trojan://Aimer@154.17.12.30:7000?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0357-US
    trojan://Aimer@154.17.29.47:37802?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0358-US
    trojan://Aimer@154.17.228.19:24869?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0359-US
    trojan://Aimer@154.26.182.37:443?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0360-US
    trojan://Aimer@108.165.152.241:2053?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0361-RELAY
    trojan://Aimer@199.34.228.50:2053?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0362-US
    trojan://Aimer@23.106.155.178:802?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0363-US
    trojan://Aimer@108.165.152.92:2053?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0364-RELAY
    trojan://Aimer@192.9.139.160:443?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0365-US
    trojan://Aimer@108.165.152.59:2087?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0366-RELAY
    trojan://Aimer@108.165.152.239:8443?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0367-RELAY
    trojan://Aimer@108.165.152.78:2083?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0368-RELAY
    trojan://Aimer@199.34.228.71:8443?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0369-US
    trojan://Aimer@108.165.152.18:2087?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0370-RELAY
    trojan://Aimer@108.165.152.202:2083?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0371-RELAY
    trojan://Aimer@199.34.228.191:2096?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0372-US
    trojan://Aimer@108.165.152.252:2096?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0373-RELAY
    trojan://Aimer@156.225.72.246:2087?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0374-RELAY
    trojan://Aimer@108.165.152.14:2096?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0375-RELAY
    trojan://Aimer@108.165.152.225:2083?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0376-RELAY
    trojan://Aimer@192.3.155.203:995?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F#09-0377-US
    vmess://eyJ2IjoiMiIsInBzIjoiMTQtMDIwOC1DTiIsImFkZCI6IjUxZTQ4YzA0LXQwZmRzMC10M2ZqcDctY2Rmbi44Mi5pd3Nrd2FpLmNvbSIsInBvcnQiOiIzNjgzIiwidHlwZSI6Im5vbmUiLCJpZCI6Ijk0OTMxODYyLTE0ODQtMTFmMC05YWI3LWYyM2M5NWI2ZjUxZCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IjUxZTQ4YzA0LXQwZmRzMC10M2ZqcDctY2Rmbi44Mi5pd3Nrd2FpLmNvbSIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiMTQtMDIwOS1SRUxBWSIsImFkZCI6IjE5MC45My4yNDYuMTUxIiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjJmMzhmODQ4LWE4OTktNGM4Ny05ODA3LTIwN2E0MTYxNWUzYyIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvcm9uZ3NldmVuIiwiaG9zdCI6IiIsInRscyI6IiJ9
    ss://YWVzLTI1Ni1nY206aVVCMDkyM1JCQQ@154.3.8.151:30067#14-0211-US
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@51.15.23.63:989#14-0213-NL
    vmess://eyJ2IjoiMiIsInBzIjoiMTQtMDM4MS1SRUxBWSIsImFkZCI6IkZGZmZmZmZGZmZGRmtrS2trS0wuNDQ0NDkyNi54WVoiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiZGM1MGViMWQtMjQ0ZC00NzExLWIxNjgtYTEwMWE1ZTZmYjFiIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9hd21xcTc5QjE3cmZucFhpTmFXYiIsImhvc3QiOiJGRmZmZmZmRmZmRkZra0tra0tMLjQ0NDQ5MjYueFlaIiwidGxzIjoiIn0=
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowWXRWTjFLNE0zODhxUlJKd3FHMXVO@178.208.91.118:19805#23-0384-NL
    ss://YWVzLTEyOC1nY206c2hhZG93c29ja3M@141.98.101.178:443#23-0387-GB
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpjajJsM3pXdmVnWmV4QW1IN3k4MlNP@81.19.141.45:443#23-0399-DE
    ss://YWVzLTEyOC1nY206c2hhZG93c29ja3M@141.98.101.179:443#23-0407-GB
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo0YTJyZml4b3BoZGpmZmE4S1ZBNEFh@151.242.251.144:8080#23-0412-AE
    


</details>

### 所有节点
合并节点总数: `95`
[节点链接](https://raw.githubusercontent.com/caijh/TopFreeProxies/master/sub/sub_merge_base64.txt)

### 节点来源
- [clashnode](https://github.com/imyaoxp/clashnode), 节点数量: `95`


## 仓库声明
订阅节点仅作学习交流使用，只是对网络上节点的优选排序，用于查找资料，学习知识，不做任何违法行为。所有资源均来自互联网，仅供大家交流学习使用，出现违法问题概不负责。

