# pojia-AstrBot
Astrbot 破甲
# 免责声明 / Disclaimer

**miluo破甲（astrbot_plugin_pojia）**
最后更新：2026-10-30

## 一句话

这是一个给**自己机器上自建的 AstrBot 实例**用的实验性插件。它会改写发给大模型的请求，让模型按要求输出成人向或冒犯性内容。**装不装、怎么用、用完发到哪儿，全由你负责；作者不承担任何后果。**

## 1. 按现状提供

本软件按「现状」（AS IS）与「可用即提供」（AS AVAILABLE）发布，不附带任何明示或默示的担保，包括但不限于：适销性、特定用途适用性、不侵权、不中断、无错误，以及输出内容适合任何用途。

作者不保证：

- 插件能在你的 AstrBot 版本、模型、平台上正常工作；
- 绕过拒绝一定成功，或成功一次之后一直成功；
- 生成内容准确、合法、无害、不侵犯他人权利；
- 会继续维护、修 bug 或回应 issue。

## 2. 使用者的责任

使用本软件即表示你确认并同意：

1. **你已满 18 周岁**（或你所在司法辖区的成年年龄），并自愿接触成人向内容。
2. 你自行确认使用行为符合**所在地法律法规**。不同国家和地区对成人内容、仇恨言论、歧视性表达的**制作、持有、传播**规定差异极大，部分地区限制非常严格。这个判断只能由你做。
3. 你自行确认符合**所用平台与服务的条款**：AstrBot、你接入的模型供应商（OpenAI、Anthropic、DeepSeek、各家中转等）、以及承载机器人的聊天平台（QQ、微信、Telegram、Discord、飞书等）。违反条款导致的限流、封号、扣费、清退，与作者无关。
4. 你自行承担**发布后果**：把生成内容发到群里、频道里或公开平台上，由此产生的纠纷、投诉、举报、行政处罚或刑事责任，由发布者承担。
5. 你自行负责**部署环境**：群成员是否成年、是否可能被未成年人看到、是否需要年龄门禁或限制为私聊，由部署者设置。

## 3. 内容不由作者提供

- 仓库里**没有任何内容库**：没有色情文本、没有段子库、没有歧视语料。
- 所有输出都是**你配置的第三方大模型在运行时生成的**。插件只负责拼接提示词、检测拒绝、必要时重试。
- 作者不审核、不存储、不转发、不监控任何生成内容，也无法控制模型会说什么。
- 模型输出**不代表作者立场**。模型可能生成错误、冒犯、违法或令人不适的内容，这是模型本身的特性。

## 4. 无数据收集

- 插件不含遥测，不上报数据，不连接作者控制的任何服务器。
- 会话状态（开关、档位、场景与人格设定）以 KV 形式存放在你自己的 AstrBot 数据目录。
- 调试日志可能包含用户消息片段；`debug` 默认关闭，公开日志前请自行检查。你与模型供应商之间的请求内容受该供应商的隐私政策约束。

## 5. 责任限制

在适用法律允许的最大范围内，作者与贡献者不对任何索赔、损害或其他责任负责，无论其源于合同、侵权或其他，包括但不限于：

- 账号被封禁、限流、扣费、余额损失；
- 数据丢失、配置损坏、服务中断；
- 法律纠纷、行政处罚、刑事责任；
- 名誉、商誉或精神损害；
- 因使用或无法使用本软件而产生的任何直接、间接、附带、特殊、惩罚性或后果性损害。

即使作者已被告知此类损害的可能性，本条仍然适用。

## 6. 不背书、不隶属

本项目与 AstrBot、任何大模型供应商、任何聊天平台均无隶属、合作或背书关系。文中出现的第三方名称与商标归各自所有者，仅用于说明兼容性。

## 7. 分发与修改

本项目以 MIT 许可发布（见 [LICENSE](LICENSE)），可自由使用、修改、再分发，但：

- 再分发时**必须保留本免责声明与许可声明**；
- 你基于本项目做的修改、二次分发、商业使用，合规责任由你承担；
- 不得暗示作者为你的分支、部署或生成内容背书。

## 8. 可分割性

本声明任何条款被认定无效或不可执行，不影响其余条款的效力。

## 9. 不接受则不使用

如果你不同意上述任何一条，请不要安装、运行或分发本项目；已安装的，删除插件目录并清理 AstrBot 中对应的 KV 数据即可。

---

# English (short version)

**miluo破甲 (astrbot_plugin_pojia)** — an experimental rejection-ladder / adult-mode plugin for self-hosted AstrBot instances. It rewrites prompts sent to the language model you configure.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

By using this software you confirm that you are of legal age in your jurisdiction, that you will comply with all applicable laws and with the terms of service of AstrBot, your model provider and your chat platform, and that you alone are responsible for any content you generate, store or publish. This repository ships no content of its own; all output is generated at runtime by the model you configure. The authors do not review, store or endorse any generated output. Third-party names and trademarks belong to their respective owners. Distributed under the MIT License; see [LICENSE](LICENSE).
