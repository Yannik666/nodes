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
高速节点数量: `45`
<details>
  <summary>展开复制节点</summary>

    trojan://Aimer@176.124.223.40:2053?allowInsecure=1&sni=epga.aimercc.dpdns.org&ws=1&wspath=%2525252F%2525253Fed%2525253D2560#05-0026-RELAY
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo5UnZpTmE0dHNjamNtQ0I0MDh2TFNn@46.101.245.131:44354#06-0048-DE
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo5SmVZeThTa1ZpWHVTSFZzOUdGZVNl@77.110.110.117:443#06-0051-AT
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTozNjBlMjFkMjE5NzdkYzEx@103.111.114.29:57456#06-0056-IN
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTphNThmYTYyYjQ5NDRkZGJm@216.173.70.187:57456#06-0059-LV
    trojan://NISHIKUITAN111@190.93.247.175:443?allowInsecure=1#06-0060-RELAY
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTowWXRWTjFLNE0zODhxUlJKd3FHMXVO@178.208.91.118:19805#06-0062-NL
    trojan://Aimer@14.37.56.164:50000?allowInsecure=1&sni=agepw.ambercc.filegear-sg.me#06-0069-KR
    ss://YWVzLTEyOC1nY206c2hhZG93c29ja3M@212.102.53.194:443#06-0071-GB
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTo1MXlsb1FDOEQ5dzFXYWU3Rkh0STY1@4.223.106.151:48172#06-0072-SE
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNToyNFdrMk5Tc3pyZkhuMjJ6ZW0xbFlW@188.166.220.70:37708#06-0080-SGtrojan%2F%2Ftg-fq521free%40198.62.62.67443%3FallowInsecure%3D1%26sni%3Dtorjan.xn--xhq44j.eu.org%26ws%3D1%26wspath%3D%25252F%2305-0008-US
    ss://Y2hhY2hhMjAtaWV0Zi1wb2x5MTMwNTpvWklvQTY5UTh5aGNRVjhrYTNQYTNB@193.29.139.240:8080#06-0084-NL
    ss://MjAyMi1ibGFrZTMtYWVzLTI1Ni1nY206bXRNa3AlMjUyQjFGdHRrU0xtRE9GOWJsbk5NTGlnY0NSYWNwclFTM3J5MG5mM28lMjUzRCUyNTNBSkIxdWVUQ0tOSUdNYmh6V05qcyUyNTJCMEZuWmpaWE8zVXlYY1poSUoyOHZpZkElMjUzRA@pop.plus.3123.0tk8a3a1q4t94dler.com:4059#09-0093-CN
    vmess://eyJ2IjoiMiIsInBzIjoiMTQtMDEzNy1DTiIsImFkZCI6IjQ3LjEwNC4xODYuMTMzIiwicG9ydCI6IjUwMDAyIiwidHlwZSI6Im5vbmUiLCJpZCI6IjQxODA0OGFmLWEyOTMtNGI5OS05YjBjLTk4Y2EzNTgwZGQyNCIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiMTQtMDIzMi1ISyIsImFkZCI6IjVhZWU1ZWQzLXN6Zzc0MC10NDFwNHktMWhwbzAuaGt0LnRjcGJici5uZXQiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiYzNkYzhkMjYtYWIyYi0xMWVjLWE4YmYtZjIzYzkxY2ZiYmM5IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiNWFlZTVlZDMtc3pnNzQwLXQ0MXA0eS0xaHBvMC5oa3QudGNwYmJyLm5ldCIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiMTQtMDIzMy1ISyIsImFkZCI6IjUwMTlhMzQ1LXQwNDlzMC10MWttZWctbXY3bS5oa3QudGNwYmJyLm5ldCIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiI5NGQ0MDcwOC04MjczLTExZWEtOGZjOS1mMjNjOTEzYzhkMmIiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiI1MDE5YTM0NS10MDQ5czAtdDFrbWVnLW12N20uaGt0LnRjcGJici5uZXQiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiMTQtMDIzNC1ISyIsImFkZCI6ImE2MDBmODE3LXN6dDVzMC10MTY3ZDAtZ2d3dy5oa3QudGNwYmJyLm5ldCIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiJiY2M1OGU4OC1lMTQ3LTExZWMtYjI4Ni1mMjNjOTFjZmJiYzkiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiJhNjAwZjgxNy1zenQ1czAtdDE2N2QwLWdnd3cuaGt0LnRjcGJici5uZXQiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiMTQtMDIzNS1ISyIsImFkZCI6ImMxODAwYzE5LXQwN3o0MC10ZXFxY3YtMXJjNm4uaGt0LnRjcGJici5uZXQiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiMzJiZDk2ZDYtMTg2Yi0xMWYwLTlhNjUtZjIzYzkxNjRjYTVkIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiYzE4MDBjMTktdDA3ejQwLXRlcXFjdi0xcmM2bi5oa3QudGNwYmJyLm5ldCIsInRscyI6IiJ9
    trojan://tg-fq521free@216.24.57.30:443?allowInsecure=1&sni=torjan.xn--xhq44j.eu.org&ws=1&wspath=%2525252F#14-0236-US
    vmess://eyJ2IjoiMiIsInBzIjoiMTYtMDEzOC1SRUxBWSIsImFkZCI6IjIwNS4yMzMuMTgxLjI0MSIsInBvcnQiOiI4ODgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjI0OGJlNTJiLTM1ZDktMzRjYi05YjczLWUxMmI3OGJjMTMwMSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvZGFiYWkuaW4iLCJob3N0IjoiIiwidGxzIjoiIn0=
    vmess://eyJ2IjoiMiIsInBzIjoiMTYtMDEzOS1OT1dIRVJFIiwiYWRkIjoiMTAzLjE2MC4yMDQuMjQxIiwicG9ydCI6Ijg4ODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiMjQ4YmU1MmItMzVkOS0zNGNiLTliNzMtZTEyYjc4YmMxMzAxIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii9kYWJhaS5pbiIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiMTYtMDE0MC1SRUxBWSIsImFkZCI6IjE5OS4xODEuMTk3LjYwIiwicG9ydCI6IjQ0MyIsInR5cGUiOiJub25lIiwiaWQiOiJkZTk0Y2MwYS0wNTkyLTQ5NjktYjFmYy05N2VhOGYwZWEwYjMiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL3VzLmtrcC5tZS5ldS5vcmcvYWEiLCJob3N0IjoiIiwidGxzIjoiIn0=
    trojan://7248e825-887c-48b9-83bc-c26bc6392bf8@172.67.214.21:443?allowInsecure=1&sni=xXcdvFgt.191268.XYz&ws=1&wspath=%2525252FctdmgeIg3NII3ibrzzKXJGy3S1#16-0142-RELAY
    vmess://eyJ2IjoiMiIsInBzIjoiMTYtMDE0My1SRUxBWSIsImFkZCI6IjEwMy4xMTYuNy4yNDEiLCJwb3J0IjoiODg4MCIsInR5cGUiOiJub25lIiwiaWQiOiIyNDhiZTUyYi0zNWQ5LTM0Y2ItOWI3My1lMTJiNzhiYzEzMDEiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiL2RhYmFpLmluIiwiaG9zdCI6IiIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiMTYtMDE0NC1SRUxBWSIsImFkZCI6IjE0MS4xMDEuMTE1LjY1IiwicG9ydCI6IjgwIiwidHlwZSI6Im5vbmUiLCJpZCI6IjVmNzUxYzZlLTUwYjEtNDc5Ny1iYThlLTZmZmUzMjRhMGJjZSIsImFpZCI6IjAiLCJuZXQiOiJ3cyIsInBhdGgiOiIvc2hpcmtlciIsImhvc3QiOiIiLCJ0bHMiOiIifQ==
    trojan://d0d08cddacc3190ea81b1b792e1b5fde@143.110.155.169:443?allowInsecure=1&sni=www.baidu.com#16-0145-US
    ss://YWVzLTI1Ni1jZmI6ZjhmN2FDemNQS2JzRjhwMw@156.146.40.194:989#16-0146-SK
    ss://YWVzLTI1Ni1nY206ODIzZTEzNWVkMTAz@137.220.191.40:636#16-0147-JP
    ss://YWVzLTI1Ni1jZmI6YW1hem9uc2tyMDU@13.234.32.160:443#16-0148-IN
    trojan://d0d08cddacc3190ea81b1b792e1b5fde@58.152.30.37:443?allowInsecure=1&sni=www.baidu.com#16-0149-HK
    ss://Y2hhY2hhMjAtaWV0Zjphc2QxMjM0NTY@103.149.183.154:8388#16-0150-HK
    ss://YWVzLTI1Ni1nY206OWJmZGRlNzFiNGMw@103.103.245.158:636#16-0151-HK
    vmess://eyJ2IjoiMiIsInBzIjoiMTYtMDE1Mi1ISyIsImFkZCI6IjIxMmY4Y2QwLXQwYm9nMC10MW53c24tMWxhMnEuaGt0LnRjcGJici5uZXQiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiNDMxMDI2YzgtNzM5Ny0xMWVkLWE4YmYtZjIzYzkxY2ZiYmM5IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiMjEyZjhjZDAtdDBib2cwLXQxbndzbi0xbGEycS5oa3QudGNwYmJyLm5ldCIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiMTYtMDE1My1ISyIsImFkZCI6ImVkOTdhZThlLXQwNDlzMC10NG54dmMtMXAxYi5oa3QudGNwYmJyLm5ldCIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiIyNzliODU4OC02MTZiLTExZWQtYThiZi1mMjNjOTFjZmJiYzkiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiJlZDk3YWU4ZS10MDQ5czAtdDRueHZjLTFwMWIuaGt0LnRjcGJici5uZXQiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiMTYtMDE1NC1ISyIsImFkZCI6ImhrdC5nb3RvY2hpbmF0b3duLm5ldCIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiI3MTVhMjU3NC05YzI1LTExZWItODY3My1mMjNjOTE2NGNhNWQiLCJhaWQiOiIyIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiJoa3QuZ290b2NoaW5hdG93bi5uZXQiLCJ0bHMiOiIifQ==
    ss://cmM0LW1kNTplZmFuY2N5dW4@cn01.efan8867801.xyz:8766#16-0155-CN
    vmess://eyJ2IjoiMiIsInBzIjoiMTYtMDE1Ni1ISyIsImFkZCI6IjkxYzg1YTI3LXQwN3o0MC10MHI3bDQtMXJ1aWguaGt0LnRjcGJici5uZXQiLCJwb3J0IjoiODAiLCJ0eXBlIjoibm9uZSIsImlkIjoiMzU0OWFiZGEtMzg1NC0xMWVmLWI3MWUtZjIzYzkxNjRjYTVkIiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8iLCJob3N0IjoiOTFjODVhMjctdDA3ejQwLXQwcjdsNC0xcnVpaC5oa3QudGNwYmJyLm5ldCIsInRscyI6IiJ9
    vmess://eyJ2IjoiMiIsInBzIjoiMTYtMDE1Ny1SRUxBWSIsImFkZCI6ImJsdWVob3N0LmNvbSIsInBvcnQiOiI0NDMiLCJ0eXBlIjoibm9uZSIsImlkIjoiMTJlZWQ1MDctOWE1OC00Y2E1LWY3YWYtMjg3MWU5YWFlNjg0IiwiYWlkIjoiMCIsIm5ldCI6IndzIiwicGF0aCI6Ii8xOTU0NCIsImhvc3QiOiJibHVlaG9zdC5jb20iLCJ0bHMiOiIifQ==
    ss://cmM0LW1kNTplZmFuY2N5dW4@cn01.efan8867801.xyz:8774#16-0158-CN
    trojan://92435aa8-f3b6-466a-ad58-c55cbb6d2acf@sg.mjt000.com:443?allowInsecure=1&sni=sg.mjt000.com#16-0159-HK
    vmess://eyJ2IjoiMiIsInBzIjoiMTYtMDE2MC1ISyIsImFkZCI6ImhrdC5nb3RvY2hpbmF0b3duLm5ldCIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiI2ZTMxMzU5OC1hMDg4LTExZWEtYTIyZS1mMjNjOTFjZmJiYzkiLCJhaWQiOiIyIiwibmV0Ijoid3MiLCJwYXRoIjoiLyIsImhvc3QiOiJoa3QuZ290b2NoaW5hdG93bi5uZXQiLCJ0bHMiOiIifQ==
    trojan://d0d08cddacc3190ea81b1b792e1b5fde@157.230.32.243:443?allowInsecure=1&sni=www.baidu.com#16-0237-SG
    vmess://eyJ2IjoiMiIsInBzIjoiMTktMDIyOS1SRUxBWSIsImFkZCI6InRlc3QuZmxoYS5ydSIsInBvcnQiOiI4MCIsInR5cGUiOiJub25lIiwiaWQiOiIyYmFiNmI4Zi04ZDZlLTQ2M2EtODMzMS1iOWRlM2Q1NjkyMWQiLCJhaWQiOiIwIiwibmV0Ijoid3MiLCJwYXRoIjoiLzJiYWI2YjhmLThkNmUtNDYzYS04MzMxLWI5ZGUzZDU2OTIxZC12bWVzcyIsImhvc3QiOiJ0ZXN0LmZsaGEucnUiLCJ0bHMiOiIifQ==
    vmess://eyJ2IjoiMiIsInBzIjoiMTktMDIzMC1DTiIsImFkZCI6InY4LmhlZHVpYW4ubGluayIsInBvcnQiOiIzMDgwOCIsInR5cGUiOiJub25lIiwiaWQiOiJjYmIzZjg3Ny1kMWZiLTM0NGMtODdhOS1kMTUzYmZmZDU0ODQiLCJhaWQiOiIyIiwibmV0Ijoid3MiLCJwYXRoIjoiL29vb28iLCJob3N0IjoidjguaGVkdWlhbi5saW5rIiwidGxzIjoiIn0=
    


</details>

### 所有节点
合并节点总数: `118`
[节点链接](https://raw.githubusercontent.com/caijh/TopFreeProxies/master/sub/sub_merge_base64.txt)

### 节点来源
- [clashnode](https://github.com/imyaoxp/clashnode), 节点数量: `118`


## 仓库声明
订阅节点仅作学习交流使用，只是对网络上节点的优选排序，用于查找资料，学习知识，不做任何违法行为。所有资源均来自互联网，仅供大家交流学习使用，出现违法问题概不负责。

