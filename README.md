# Blog Studio

面向人类读者的技术与科技博客技能。从主题、笔记、链接、代码资料或半稿出发，研究、起草和定点编辑，兼顾技术深度与阅读体验。

## 使用

在支持 `SKILL.md` 的宿主中加载 `blog-studio/`，然后例如：

- “使用 blog-studio，面向有基础的开发者，依据这些资料解释……，写一篇中文博客。”
- “根据实验记录续写，区分已验证结果与未完成实验。”
- “标题和正文已锁定，只规划图位与排版。”

提供目标读者、资料和期望长度有助于写作。资料充分时可直接生成初稿；默认保留 Markdown 母稿。图按解释需要规划，并非每篇必配。远程上传、公开发布和付费生成需要分别授权；没有适用工具时交付明确标注的图位或提示词。

来源与许可边界见 [来源说明](blog-studio/SOURCES.md)。实际联网、图片、导出和平台能力取决于宿主工具与授权。

## 方法来源

Blog Studio 以原创文字融合三个开源项目中适合深度博客的方法：

- [Composio content-research-writer](https://github.com/ComposioHQ/awesome-claude-skills/blob/be2a406907dbc61b73e6827ded415c96139d13a2/content-research-writer/SKILL.md)：识别研究缺口、用例子支撑论点，并结合作者声音做结构与整稿编辑。
- [JimLiu baoyu-skills](https://github.com/JimLiu/baoyu-skills/tree/1567581c26ec29f4216c6e6835415bf30343b0e3)：按内容规划解释图和封面，保留 Markdown 母稿，检查导出，并在翻译中核对语境与含义。
- [SpaceZephyr creator-buddy](https://github.com/SpaceZephyr/creator-buddy/tree/edf46c567ff54b72ee2157d06f3a02dbd67aaa9c)：从素材、半稿和定点重写等入口出发，比较材料对主线的贡献，诊断结构、证据与论点问题。

自然表达还参考 [Humanizer](https://github.com/blader/humanizer)、Humanizer-zh 和 compound-engineering 的 ce-noslop：根据上下文处理套话，保留技术限定、事实和作者声音。这里是方法融合，**没有整套移植上游代码、模板或个人文风**。各来源的版本、归属和许可边界见 [来源说明](blog-studio/SOURCES.md)；技能本身不依赖安装这些项目。
