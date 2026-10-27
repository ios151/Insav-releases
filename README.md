# INSAV · 安装包

这个仓库只用来发布 **INSAV** 的未签名 IPA，**不含源码**。

## 下载与安装

1. 打开 [Releases](https://github.com/ios151/Insav-releases/releases/latest)，下载最新的 `Insav-unsigned.ipa`
2. 安装包是**未签名**的，不能直接装：**推荐用 [LCSign](https://www.sign.lc) 签名安装**；也可以用自己的证书，或者 SideStore / AltStore 这类工具自签
3. 装好之后 App 会每天自动检查一次新版本，进站后有新版会提示：
   - 装了 LCSign 的：点「用 LCSign 更新」，新版安装包会直接导入 LCSign，签名安装即可
   - 没装 LCSign 的：点「去下载」回到这里，下载新的安装包重新安装

## 说明

- 最低系统：iOS 16；iPhone / iPad 通用
- 每个版本的更新内容见对应 Release 的说明，也会显示在 App 的更新提示里
- 安装包由 CI 构建后自动发布到这里
