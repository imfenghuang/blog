# bug
### URL.createObjectUrl(file)
oppo r7 安卓5.1 使用上述命令生成 `blob url` 的时候，生成的链接有问题，会生成形如 `blob:https%3A//github.com/ssdkajsdakjsda-sadk` 的字符串，明显地， %3A 是有问题的
