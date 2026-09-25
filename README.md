# homebrew-tap

SodaM（汽水音乐桌面客户端）的 Homebrew tap。

## 安装（macOS · Apple Silicon）

不用手动添加 tap，直接装：

```bash
brew install --cask sodahub-org/tap/sodam
```

升级：

```bash
brew update
brew upgrade --cask sodam
```

说明：SodaM 当前只发布 Apple Silicon（arm64）的 macOS 包；应用为 ad-hoc 签名，
安装后如被 Gatekeeper 拦截，参考主仓库 README 的「首次启动」一节处理。
