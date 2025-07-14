# ○○の通学経路

[メンバー表に戻る](member.md#メンバー表)

```graphviz
digraph {
    edge [dir=both]

    // 例
    八王子国際キャンパス -> 高尾駅 [label=バス]
    高尾駅 -> 国立駅 [label=中央線]
    国立駅 -> 仁藤自宅 [label=自転車]
}
```