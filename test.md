# GitHub Writer 接入测试文档

这是一份用于验证 GitHub Markdown 导入、修改、资源读取和写回能力的测试文档。

## 第一节：保持不变

这一段用于确认未被指定修改的内容能够保持原样，包括段落结构、空行和 Markdown 格式。

## 第二节：待修改

这是第二节的初始内容，用于验证局部修改以及 GitHub PR 中的行级 diff。

## 第三节：图片资源

下面的图片使用相对路径引用，用于验证相关资源能够随文档一起导入和写回。

![GitHub Writer 测试图片](./test.png)

## 第四节：格式保留

- 列表项目 A
- 列表项目 B
- 列表项目 C

```text
GITHUB_WRITER_TEST_MARKER
```

