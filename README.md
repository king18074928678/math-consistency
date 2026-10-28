# 试题与课程标准的一致性研究 — 官网

## 网站内容
- 课题：试题与课程标准一致性研究（SEC / Webb / Achieve 三模型）
- 负责人：卢水杰团队
- 主页面：`index.html`（单文件自包含，已内嵌样式与脚本、内置整卷自动编码与一致性分析工具）
- 课标编码表：`assets/kebiao-2022.doc`、`assets/kebiao-2011.doc`

## 本地预览
任意静态服务器均可，也可直接双击 `index.html` 打开：

```bash
python3 -m http.server 8000
# 浏览器访问 http://localhost:8000
```

## GitHub Pages 部署
1. 登录 GitHub，新建一个 Public 仓库（建议命名 `math-consistency`）。
2. 把本文件夹里的所有文件（`index.html` + `assets/` 目录 + 本 README）上传到仓库根目录。
3. 进入仓库 → **Settings → Pages**：
   - Source 选 **Deploy from a branch**
   - Branch 选 **main**，文件夹选 **/(root)**
   - 点击 **Save**
4. 等待 1~2 分钟，绿色提示出现后，即可通过以下地址访问：

   ```
   https://<你的GitHub用户名>.github.io/math-consistency/
   ```

> 提示：如果把仓库名直接命名为 `<你的GitHub用户名>.github.io`，则访问地址为 `https://<你的GitHub用户名>.github.io/`（无需带仓库名）。

## 文件结构
```
.
├── index.html                # 官网首页（已内嵌在线一致性分析工具）
├── assets/
│   ├── kebiao-2022.doc       # 2022版课标初中学段编码表
│   └── kebiao-2011.doc       # 2011版课标初中学段编码表
└── README.md                 # 本说明文件
```
