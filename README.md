# phplint

## 用法

### 使用

`.gitlab-ci.yml` 增加如下配置即可使用

```yaml

test:app:
  image: stenote/phplint
  script:
  - phplint
```
