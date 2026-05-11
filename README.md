# Selective Freedom License (SFL) v1.0

[English](#english) | [中文](#中文) | [中文版许可证](./LICENSE-CN.md)

---

<a name="english"></a>
## English

### Overview

**Selective Freedom License (SFL)** is an open-source software license derived from the MIT License. It retains the permissive nature of MIT — allowing free use, modification, and distribution — while explicitly excluding a specific restricted entity from receiving any license rights.

The name "Selective Freedom" reflects the core philosophy: **freedom is extended to all, except those who are explicitly and deliberately excluded.**

### How is SFL Different from MIT?

| Feature | MIT License | SFL |
|---|---|---|
| Free to use, modify, distribute | Yes | Yes |
| Commercial use allowed | Yes | Yes |
| Sublicensing allowed | Yes | Yes |
| Warranty disclaimer | Yes | Yes |
| Entity exclusion clause | No | Yes |
| Legal enforcement provisions | No | Yes |
| Survivability after termination | No | Yes |
| Export control obligation | No | Yes |

### Key Provisions Explained

**Section 1 - Definitions**
Defines the key terms used throughout the license, including what constitutes "Huawei", "Restricted Entity", and "Licensee". The definition of Restricted Entity is deliberately broad to cover subsidiaries, affiliates, employees, contractors, and agents.

**Section 2 - Grant of License**
Grants the same broad permissions as MIT, but explicitly conditions them on the licensee NOT being a Restricted Entity.

**Section 3 - Exclusion of Restricted Entities**
This is the heart of the license. It states that no rights of any kind are granted to any Restricted Entity. Any use by a Restricted Entity is treated as direct copyright infringement. This provision survives termination.

**Section 4 - Conditions and Obligations**
Requires inclusion of the license notice in all copies, and obligates licensees to take reasonable measures to prevent the software from reaching Restricted Entities.

**Section 5 - Intellectual Property**
Standard IP provisions protecting the copyright holder's trademarks and trade names.

**Section 6 - Termination**
Automatic termination upon breach, with key provisions (exclusion, warranty disclaimer, liability limitation, legal remedies) surviving termination.

**Section 7-8 - Warranty Disclaimer & Liability Limitation**
Standard MIT-style warranty disclaimer and liability limitation. The software is provided "as is".

**Section 9 - Legal Remedies and Enforcement**
Provides the copyright holder with specific legal remedies in case of breach, including injunctive relief, damages recovery, profit disgorgement, and attorney's fees. This section gives the license real teeth.

**Section 10 - Governing Law**
Establishes the jurisdiction for disputes based on the copyright holder's location.

**Section 11-13 - Severability, Entire Agreement, Amendment**
Standard boilerplate provisions for legal robustness.

### How to Use This License

#### Step 1: Copy the License File

Copy the [`LICENSE`](./LICENSE) file into the root directory of your project.

> A Chinese reference translation is available at [`LICENSE-CN.md`](./LICENSE-CN.md) for convenience. The English version is the legally binding version.

#### Step 2: Update the Copyright Notice

In the `LICENSE` file, replace:
```
Copyright (c) 2026 [COPYRIGHT HOLDER]
```
with your actual name or organization name, for example:
```
Copyright (c) 2026 John Doe
```

#### Step 3: Add License Notice to Your Project

Add the following to your README or a prominent location in your project:

```
This project is licensed under the Selective Freedom License (SFL) v1.0.
See the [LICENSE](./LICENSE) file for full terms.
```

#### Step 4 (Optional): Add Header to Source Files

You may add the following header to each source file:

```
Copyright (c) 2026 [YOUR NAME]
Licensed under the Selective Freedom License (SFL) v1.0.
See LICENSE file for details.
```

### FAQ

**Q: Can I fork a project using SFL and change the exclusion target?**
A: No. You may not modify the license terms when redistributing. The original copyright holder's exclusion clause must be preserved.

**Q: Does this license violate anti-discrimination principles in open source?**
A: This is a debated topic. SFL deliberately departs from the Open Source Initiative (OSI) definition of "open source" by introducing entity-specific restrictions. It is a custom license designed for specific use cases.

**Q: Is this license legally enforceable?**
A: SFL is drafted to be as legally enforceable as possible, but its enforceability depends on the applicable jurisdiction. Consult a legal professional for advice specific to your situation.

**Q: Can I use SFL for my own project and exclude a different entity?**
A: The current version of SFL is specifically drafted for excluding Huawei. If you need to exclude a different entity, you would need to modify the definitions section accordingly, which would create a derivative license.

---

<a name="中文"></a>
## 中文

### 概述

**选择性自由许可证 (Selective Freedom License, SFL)** 是一个基于 MIT 许可证的开源软件许可证。它保留了 MIT 的宽松特性——允许自由使用、修改和分发——同时明确排除特定限制实体获得任何许可权利。

"选择性自由"这个名称反映了其核心理念：**自由向所有人开放，但明确且刻意排除的实体除外。**

### SFL 与 MIT 的区别

| 特性 | MIT 许可证 | SFL |
|---|---|---|
| 免费使用、修改、分发 | 是 | 是 |
| 允许商业使用 | 是 | 是 |
| 允许再许可 | 是 | 是 |
| 免责声明 | 是 | 是 |
| 实体排除条款 | 无 | 有 |
| 法律追责条款 | 无 | 有 |
| 终止后存续条款 | 无 | 有 |
| 出口管制义务 | 无 | 有 |

### 核心条款解读

**第 1 节 - 定义**
定义了许可证中使用的关键术语，包括"华为"、"限制实体"和"被许可人"的含义。限制实体的定义刻意宽泛，涵盖子公司、关联公司、员工、承包商和代理人。

**第 2 节 - 许可授权**
授予与 MIT 相同的广泛权限，但明确以被许可人不是限制实体为前提条件。

**第 3 节 - 限制实体排除**
这是本许可证的核心条款。明确规定不向任何限制实体授予任何形式的权利。限制实体的任何使用行为均被视为直接侵犯版权。此条款在许可证终止后仍然有效。

**第 4 节 - 条件与义务**
要求在所有副本中包含许可证声明，并要求被许可人采取合理措施防止软件流入限制实体手中。

**第 5 节 - 知识产权**
保护版权所有者的商标和商号的标准知识产权条款。

**第 6 节 - 终止**
违反条款时自动终止，但关键条款（排除条款、免责声明、责任限制、法律救济）在终止后继续有效。

**第 7-8 节 - 免责声明与责任限制**
标准的 MIT 风格免责声明和责任限制。软件按"原样"提供。

**第 9 节 - 法律救济与执行**
为版权所有者在违约情况下提供具体的法律救济手段，包括禁令救济、损害赔偿、利润返还和律师费。此条款赋予了许可证实际执行力。

**第 10 节 - 管辖法律**
根据版权所有者的所在地确定争议管辖权。

**第 11-13 节 - 可分割性、完整协议、修订**
标准的法律条款，确保许可证的法律健壮性。

### 使用方法

#### 第一步：复制许可证文件

将 [`LICENSE`](./LICENSE) 文件复制到你项目的根目录。

> 中文参考译本请见 [`LICENSE-CN.md`](./LICENSE-CN.md)，仅供参考，不具有法律约束力。具有法律约束力的为英文原版 LICENSE 文件。

#### 第二步：更新版权信息

在 `LICENSE` 文件中，将：
```
Copyright (c) 2026 [COPYRIGHT HOLDER]
```
替换为你的实际姓名或组织名称，例如：
```
Copyright (c) 2026 张三
```

#### 第三步：在项目中添加许可证声明

在你的 README 或项目显眼位置添加：

```
本项目采用选择性自由许可证 (SFL) v1.0 授权。
完整条款请参阅 [LICENSE](./LICENSE) 文件。
```

#### 第四步（可选）：在源代码文件中添加头部声明

你可以在每个源代码文件中添加以下头部：

```
Copyright (c) 2026 [你的名字]
采用选择性自由许可证 (SFL) v1.0 授权。
详见 LICENSE 文件。
```

### 常见问题

**问：我可以 fork 使用 SFL 的项目并更改排除目标吗？**
答：不可以。重新分发时不得修改许可证条款。原始版权所有者的排除条款必须保留。

**问：这个许可证是否违反开源的反歧视原则？**
答：这是一个有争议的话题。SFL 刻意偏离了开源倡议组织 (OSI) 对"开源"的定义，引入了针对特定实体的限制。它是为特定用例设计的自定义许可证。

**问：这个许可证有法律效力吗？**
答：SFL 的起草尽可能确保其法律效力，但其可执行性取决于适用的司法管辖区。建议就你的具体情况咨询法律专业人士。

**问：我可以用 SFL 来授权我自己的项目并排除不同的实体吗？**
答：当前版本的 SFL 是专门为排除华为而起草的。如果你需要排除不同的实体，你需要相应修改定义部分，这将产生一个衍生许可证。

---

### License

This project's license text ([LICENSE](./LICENSE)) is itself released under the
[Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/),
so you are free to adapt it for your own use with attribution.
