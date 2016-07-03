# jscript9.dll TypedArray/DataView 内存漏洞分析
MS16-063 PoC

已于 Windows 7 IE11 测试 (modern.ie).

### 分析
https://www.deamwork.com/archives/patch-analysis-of-ms16-063.orz6

### 部署
1. 下载 exploit/jscript\_win7.html 到本地文件夹
2. 创建本地服务器指向上述文件夹
3. 使用未修复漏洞的IE访问 `jscript_win7.html`.
4. (刷新和重新打开页面存在一定概率无法成功)
