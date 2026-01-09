# `.gitignore` 在线获取工具

本项目支持通过 **简洁的 URL 规则**，快速获取常见语言或框架的 `.gitignore` 文件内容，方便直接使用或集成到自动化流程中。

## 使用方式

访问以下地址格式：
```
[使用https://llugaes.com/gitignore/{ignore文件名}
如https://llugaes.com/gitignore/python 对应 python.gitignore](https://llugaes.com/gitignore/{ignore文件名}
```

系统将返回对应的 `.gitignore` 内容。

## 示例

### Python

```
https://llugaes.com/gitignore/python
```

对应文件：`python.gitignore`

### Node.js

```
https://llugaes.com/gitignore/node
```

对应文件：`node.gitignore`

## 使用场景

- 快速初始化新项目的 `.gitignore`
- 自动化脚本中动态拉取 `.gitignore`
- 避免手动维护或复制粘贴错误
- 统一团队 `.gitignore` 规范

## 命名规则说明

- `{ignore文件名}` 与实际的 `{name}.gitignore` 一一对应  
- 不需要包含 `.gitignore` 后缀  
- 文件名大小写不敏感（建议使用小写）

## 备注

- 若请求的 `{ignore文件名}` 不存在，将返回错误提示  
- 可根据需要持续扩展支持的语言或框架列表  
