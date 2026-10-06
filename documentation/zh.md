<!-- ELUCENIA technical documentation · gravidade-da-anafilaxia · zh · no clinical/professional/rights approval -->

# 过敏性反应严重程度（Brown）

[条件、来源与许可](https://elucenia.org/zh/tools/gravidade-da-anafilaxia)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 皮肤及皮下：全身红斑、荨麻疹、眶周水肿或血管性水肿

`pele`

### 呼吸：呼吸困难、喉鸣、哮鸣、胸闷或咽喉紧缩

`resp`

### 胃肠：恶心、呕吐、腹痛

`gi`

### 晕厥前兆（头晕）或出汗

`cardio`

### 低氧血症（SpO₂ ≤ 92%）或发绀

`hipoxia`

### 低血压（成人收缩压 \< 90 mmHg）

`hipotensao`

### 神经异常：意识混乱、虚脱、意识丧失或失禁

`neuro`

## 方法版本

Brown 2004：3级，最严重表现；SpO₂≤92/收缩压\<90/神经

## 已记录的公式

按最严重表现确定分级：

1级（轻）：仅皮肤和皮下。

2级（中）：呼吸、心血管或消化道受累。

3级（重）：低氧（SpO₂ ≤ 92%或发绀）、低血压（收缩压\< 90 mmHg）或神经功能受损。

## 限制与适用人群

Brown分类在急诊全身性超敏反应中进行回顾性研究。严重程度并非完整的诊断定义，也不是独立的治疗规则。数值阈值及该版本的定义须核对完整方法；不能仅以总分代替体征和应用条件。

## 参考文献

- [Brown SGA. Clinical features and severity grading of anaphylaxis. J Allergy Clin Immunol, 2004.](https://doi.org/10.1016/j.jaci.2004.04.029)

- [Cardona V et al. World Allergy Organization Anaphylaxis Guidance 2020. World Allergy Organ J, 2020.](https://doi.org/10.1016/j.waojou.2020.100472)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

1级（轻度）：全身性反应仅限于皮肤和皮下组织

注意病情进展：皮肤症状可能先于其他系统受累。


### 2

2级（中度）：有呼吸、心血管或胃肠受累，但无低氧血症、低血压或神经功能受损

肌内肾上腺素 0,01 mg/kg（成人最大 0,5 mg，儿童 0,3 mg），注射于大腿前外侧，不得延误；如有必要，5 至 15 分钟后重复。


### 3

2级（中度）：有呼吸、心血管或胃肠受累，但无低氧血症、低血压或神经功能受损

肌内肾上腺素 0,01 mg/kg（成人最大 0,5 mg，儿童 0,3 mg），注射于大腿前外侧，不得延误；如有必要，5 至 15 分钟后重复。


### 4

3级（重度）：低氧血症、低血压或神经功能受损

肌内肾上腺素 0,01 mg/kg（成人最大 0,5 mg，儿童 0,3 mg），注射于大腿前外侧，不得延误；如有必要，5 至 15 分钟后重复。

