# Openfly

开放词库的小鹤音形 Rime 配置

## 小鹤音形

[官网](https://flypy.com/)

## 安装方法

1. 将所需文件复制（或软链）到 Rime 的用户目录
```shell
$ git clone https://github.com/amorphobia/openfly
$ cp *.yaml *.lua <Rime 用户目录>
```

2. 根据需要新建用户词典 `openfly.user.dict.yaml` 和 `openfly.user.top.dict.yaml` 或者在 `openfly.dict.yaml` 里删除相应行

3. 根据需要新建自定义设置 `openfly.custom.yaml`

4. 在 `defult.custom.yaml` 里启用此方案，然后重新部署

## 词典分类

- **首选字词** openfly.primary.dict.yaml
- **次选字** openfly.secondary.char.dict.yaml
- **次选词** openfly.secondary.word.dict.yaml
- **表外字** openfly.off-table.dict.yaml
- **符号编码** openfly.symbols.dict.yaml
- **快符号** openfly.fast.symbols.dict.yaml
- **直通车** 尚未实现，三个网址放在 openfly.web.dict.yaml 里
- **随心所欲** openfly.whimsicality.dict.yaml
- **隐藏全码** 未收录
- **二重简码** openfly.secondary.short.code.dict.yaml
- **内嵌提示** 官方未单独显示此词库 openfly.embedded.hint.dict.yaml

## 已知问题

1. 缺少部分内嵌编码 [#3](https://github.com/amorphobia/openfly/issues/3)
2. 暂时无法经部署生成反查文件 [#4](https://github.com/amorphobia/openfly/issues/4)
3. 部分编码可更优化 [#6](https://github.com/amorphobia/openfly/issues/6)
