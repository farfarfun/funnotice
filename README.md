# funnotice

微信通知发送工具包，计划基于 [wechatpy](https://github.com/wechatpy/wechatpy) 提供企业微信/公众号消息能力。当前仓库仍处于开发占位阶段，尚未发布到 PyPI，也未提供自有的封装 API。

组织的 [funpush](https://github.com/farfarfun/funpush) 当前仅支持钉钉机器人；其企业微信支持仍在规划中，因此暂不能替代本项目预期的企业微信能力。

## 安装

```bash
uv pip install -e .
```

## 最小示例

```python
import funnotice

print("funnotice is installed")
```

该示例仅验证开发中的包可导入；企业微信通知 API 尚未实现。

---

## 关于 farfarfun

[farfarfun](https://github.com/farfarfun) 是一个专注于实用工具库的开源组织，
涵盖云存储、数据处理、AI、多媒体与开发工具链等方向。

- 🏠 组织主页：<https://github.com/farfarfun>
- 📦 PyPI：<https://pypi.org/user/niuliangtao/>
- 📧 联系：farfarfun@qq.com

本项目基于 [MIT](LICENSE) 协议开源。
