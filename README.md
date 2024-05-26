# 全体部位命名参照イメージ
![Test Image 1](https://developer.mozilla.org/ja/docs/Learn/CSS/CSS_layout/Flexbox/flex_terms.png)

## Flex Container Attribute（親に設定する属性）:

| No | Attribute       | Description                                         | Sample No                         |
|:--:|:----------------|:----------------------------------------------------|-----------------------------------|
| 1  | flex-direction  | 主軸の方向定義                                             | container_attribute/sample01.html |
| 2  | flex-wrap       | 単一行に収まらない時の定義                                       | container_attribute/sample02.html                     |
| 3  | flex-flow       | (flex-direction,flex-wrap)セット記載法,デフォルト:`row nowrap` | container_attribute/sample03.html                     |
| 4  | justify-content | 主軸の項目配置定義                                           | container_attribute/sample04.html                     |
| 5  | align-items     | 交差軸の項目配置定義                                          | container_attribute/sample05.html                     |
| 6  | align-content   | 主軸単一行に収まらなく、複数行になる場合の交差軸の項目配置定義      | container_attribute/sample06.html                     |

---

# Item Attribute（要素に設定する属性）
| No | Attribute   | Description                                                                                                                                                  | Sample No                    |
|----|-------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------|
| 1  | align-self  | 単一項目の交差軸定義,親の`align-items`上書き可能,デフォルトauto                                                                                                                    | item_attribute/sample01.html |
| 2  | order       | 単一項目の並べる順序を設定,`order`値の昇順に配置,デフォルト0                                                                                                                          | item_attribute/sample02.html |
| 3  | flex-grow   | 残りの空間を主軸に割り当てため拡大比例の定義,デフォルト0割り当てしない                                                                                                                         | item_attribute/sample03.html |
| 4  | flex-shrink | 余りの空間を主軸に当てはまるため縮小比例の定義,デフォルト0縮小しない                                                                                                                          | item_attribute/sample04.html |
| 5  | flex-basis  | 単一項目の初期の寸法定義,デフォルトauto,widthの定義利用<br/>(width<flex-basis<min-width)                                                                                           | item_attribute/sample05.html |
| 6  | flex        | flex-grow,flex-shrink,flex-basisセットの簡略記載法,デフォルト: 0 1 auto<br/>flex: 0 1 auto<br/>> 拡大しない、縮小可能、初期サイズ<br/>flex: 1 1 auto<br/>> 自動拡大縮小<br/>flex: 0 0 100px<br/>>　指定サイズで割り当て | item_attribute/sample06.html |

---