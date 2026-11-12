# UI 设计规范

适用于 Web 页面、管理后台与常用组件设计。先遵循项目已有的 Design System、组件库和主题变量；没有统一规范时，可以参考这里的建议建立一致性。

## 通用原则

1. [间距系统](principles/spacing.md)：8px 为主，4px 为辅，不强制一切尺寸都是 8 的倍数。
2. [字体与文字层级](principles/typography.md)：标题、正文与辅助信息的层次。
3. [颜色与对比度](principles/colors.md)：主色、语义色、对比度与状态表达。
4. [对齐与视觉层级](principles/alignment-and-hierarchy.md)：布局对齐、分组与信息密度。
5. [组件一致性](principles/components.md)：圆角、边框、阴影与交互状态。
6. [界面设计检查清单](principles/ui-review-checklist.md)：设计完成后逐项核查。

## 风格目录

`styles/` 预留给 iOS 风格、极简风格及其他具体视觉方案。**设计原则与风格偏好应分开管理**：统一间距属于通用原则，使用玻璃效果则属于风格选择。

## 使用建议

- 新页面：根据需求选择设计原则，同时遵循已有产品风格。
- 维护现有页面：优先保持与相邻页面一致，避免突然引入一套新风格。
- AI 生成页面：将相关规范作为任务上下文，并通过检查清单复核。
- 任何建议都可以因具体业务和无障碍需求调整，不应机械执行。

## 参考资源

- [Apple Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/)
- [Material Design](https://m3.material.io/)
- [WCAG 2.2](https://www.w3.org/TR/WCAG22/)

参考资料用于延伸学习；本仓库内容是独立整理的实践建议。
