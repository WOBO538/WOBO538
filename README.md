### 吴波 · 游戏技术美术（TA）· 2027 届

资产管线与工具链为主轴，AI 生成工作流为辅，渲染表现为纵深。

**作品集** → <https://www.shenqu.site>　·　**邮箱** → 3054930072@qq.com

---

### 精选项目

**[UE5-AI-Asset-Pipeline](https://github.com/WOBO538/UE5-AI-Asset-Pipeline)**
四层解耦的资产自动化管线：外部流转 EXE / UE 消费插件 / AI 语义层 / PCG 布景层，层间只走文件协议。

- 310 个资产的外部流转 **0.21 秒**出清单；规则校验 150 资产 **3 秒内**
- AI 语义层按 **20 资产/批**调用，单批约 ¥0.02，缓存命中时零 API 调用
- 提供可直接双击运行的 exe、4 篇设计文档、10 条已知问题清单

**[UE5-Asset-Compliance-Pipeline](https://github.com/WOBO538/UE5-Asset-Compliance-Pipeline)**
上面那条线的 V1（源码未保留）。留下的是当时真实跑出来的数据：310 个资产、发现并修复 15 处命名问题。

> 留档的原因：记下"没有版本管理，项目最后只剩下一个 exe"这次教训。

---

### 最近在做什么

- 把上面那条管线**用手重写一遍**（v4），目标是每一行都能讲清为什么这么写
- 补 C++ 与图形学基础（GAMES101 / GAMES104 路线），每周 8 小时

### 技术栈

`UE5` `Python` `Editor Scripting` `HLSL / 材质` `ComfyUI` `Git`

---

> 数字都来自实测，方法与原始数据写在对应仓库的 `docs/` 里。
