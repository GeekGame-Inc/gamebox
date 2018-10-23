
# 盒子技术规范

### 一、文件命名规范：

**1.使用方法:** 

> 唯一标识 + xxx

**2.使用范围:**
- 场景文件（强制）
- js或ts文件（强制）
- 图片文件
- 声音文件
- 字体文件
- 粒子文件
- 预制体文件


**3.使用示例：asset目录结构（唯一标识：abc）**

![](https://laixiao.github.io/gamebox/doc/gamebox.png)


### 二、接口命名规范（强制）:

- **使用说明：** 为了防止数据冲突，开发者必须集成并使用盒子SDK。

- **使用方法：** [盒子sdk集成文档](https://laixiao.github.io/gamebox/doc/sdk-doc "盒子sdk集成文档")

- **使用范围：** 开放数据、开放数据域、数据存储


### 三、其它规范（强制）：

- 禁止使用碰撞分组：您可以使用碰撞标签（tag）来区分碰撞体。

- 禁止使用常驻节点：为保证盒子性能，盒子内的所有子游戏不能设置常驻节点。

- cocos creator引擎版本要求：2.0.2及其以上。

- 统一设计分辨率： 750*1334

- 版本号规范（必须有两个点）：1.0.0

- 子域和主域都必须遵守本规范
