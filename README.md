# Docker Synchronous
Docker Sync 是一个使用 GitHub Actions 和 Skopeo 工具将 Docker Hub 上的镜像同步到阿里云容器镜像服务的自动化工作流。

## 功能
- 在 `main` 分支有 push 或 pull request 操作时自动触发镜像同步
- 手动从 GitHub Actions 选项卡触发工作流
- 使用 Skopeo 工具同步多个常用的 Docker 镜像，包括 Nginx、PHP、Composer、MySQL、Redis、Golang、Alpine 和 Node.js 等等
- 支持同步特定版本和最新版本的镜像
- 登录阿里云镜像仓库进行镜像推送

## License
This library is licensed under the MIT. See the LICENSE file for details.