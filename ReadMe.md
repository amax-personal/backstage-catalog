### 项目目录结构

```text
backstage-catalog/
├── org/
│   └── amax-org.yaml          # 用户和团队定义
├── templates/
│   └── python-app/            # Python 模板目录
│       ├── template.yaml      # 模板逻辑
│       └── skeleton/          # 自动生成的代码架子
│           ├── src/
│           │   └── app.py
│           ├── Dockerfile
│           ├── helm/          # 用于 ArgoCD 的 Helm 定义
│           │   ├── Chart.yaml
│           │   └── values.yaml
│           ├── .github/
│           │   └── workflows/
│           │       └── deploy.yml
│           └── catalog-info.yaml