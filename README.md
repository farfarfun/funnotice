# funnotice

微信通知发送工具包，依赖 [wechatpy](https://github.com/wechatpy/wechatpy) 提供的企业微信/公众号消息能力。当前仓库尚为占位阶段，只声明了 `wechatpy` 依赖，还未提供自有的封装 API。

## 安装

```bash
pip install funnotice
# 或
uv add funnotice
```

## 最小示例

```python
import funnotice  # 确认包可正常导入

from wechatpy.enterprise import WeChatClient

client = WeChatClient(corp_id="your-corp-id", secret="your-secret")
client.message.send_text(agent_id=1000001, user_ids="@all", content="Hello from funnotice")
```

---

## 关于 farfarfun

[farfarfun](https://github.com/farfarfun) 是一个专注于实用工具库的开源组织，
涵盖云存储、数据处理、AI、多媒体与开发工具链等方向。

- 🏠 组织主页：<https://github.com/farfarfun>
- 📦 PyPI：<https://pypi.org/user/niuliangtao/>
- 📧 联系：farfarfun@qq.com

本项目基于 [MIT](LICENSE) 协议开源。
