# 简化字八股文

配方： ℞ **essay-simp**

[Rime](https://rime.im) 词汇表的简化字版本，可用于简化字为主的输入方案。

需要算法库版本 `librime>=1.5`。

## 用法

在韵书（`*.dict.yaml`）的YAML配置部分定义：

```yaml
vocabulary: essay-zh-hans
```

可以省略 `use_preset_vocabulary: true` 配置项。

---


例如在 `pinyin_simp.dict.yaml` 中:
```yaml
#pinyin_simp.dict.yaml
---
vocabulary: essay-zh-hans # <== 这一行
name: pinyin_simp
version: "0.1"
sort: by_weight
...
鼥	ba	0
釛	ba	0
# ......
```


## 安装

[东风破](https://github.com/rime/plum) 安装口令： `bash rime-install essay-simp`

授权条款：见 [LICENSE](LICENSE)
