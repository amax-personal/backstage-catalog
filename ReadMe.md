backstage-catalog/
├── org/
│   └── amax-org.yaml         # 用户和团队定义
├── templates/
│   └── python-app/           # Python 模板目录
│       ├── template.yaml     # 模板逻辑
│       └── skeleton/         # 自动生成的代码架子
│           ├── src/
│           │   └── app.py
│           ├── Dockerfile
│           ├── helm/       # 用于 ArgoCD 的 Helm 定义
│           │   
│           ├── .github/
│           │   └── workflows/
│           │     
│           └── catalog-info.yaml # 新生成的 App 在 Backstage 里的身份证