# キャラクター&世界観バイブル — むぎの夜屋台 / Mugi's Night Stall

全動画でこのファイルの設定を固定する。キャラと世界観の一貫性が「続きが見たい=登録」と「量産AIではない=審査通過」の両方の土台になる。

## コンセプト(1行)
ミニチュアの世界。雨上がりの昭和の路地裏で、三毛猫の「むぎ」が夜だけ開く小さな屋台。腹を空かせた動物たちが来て、一杯で少しだけ救われる。**セリフなし**(鳴き声・調理音・環境音・音楽のみ)で全世界に届ける。

## なぜこの形か
- 言語不要 → 日本だけでなく全世界のショートフィードに乗る
- 猫 × 料理ASMR × 日本の夜景、という伸びやすい3要素の掛け合わせ
- 固定キャラ+人間が書いた脚本 → テンプレ量産判定を避けやすい
- **各話は単体で完結させる**。前の話を見ていなくても分かること(ショートは文脈なしでフィードから見られる)。続きものの要素は「同じキャラが出る」程度に留める

## 画風(STYLEブロックは2種類。台本の `[STYLE]` をどちらかに置き換える)

画風は台本側に書かず、このブロックだけで決める。最初の3日間は同じ台本で両方を投稿して数字で決める(`README.md` の「検証結果」参照)。

**STYLE A(標準。実績のある型: かわいいAI猫 × 本物に見えるミニチュア料理)**
```
STYLE: cute fluffy cat characters with soft detailed fur and slightly oversized expressive eyes, semi-realistic 3D look,
tiny real-looking miniature kitchen and miniature real food, macro lens, shallow depth of field,
warm paper-lantern light against cool blue night, wet cobblestone reflections, gentle steam,
cozy nostalgic 1960s Japanese back-alley, crisp realistic cooking sounds, vertical 9:16,
no text, no subtitles, no watermark, no humans
```

**STYLE B(比較用。未実証の差別化案: 羊毛フェルトのストップモーション風)**
```
STYLE: handmade wool stop-motion animation, miniature diorama set, visible wool fiber texture,
tiny handcrafted props, shallow depth of field, macro lens look, warm paper-lantern light against cool blue night,
wet cobblestone reflections, gentle steam, slightly stuttered stop-motion movement (12fps feel),
cozy nostalgic 1960s Japanese back-alley, vertical 9:16, no text, no subtitles, no watermark, no humans
```

## 舞台
- **屋台**: 木製の引き屋台。赤い提灯(無地、文字なし)、藍色ののれん(肉球の白抜きマーク1つ)、カウンター席は丸椅子3つ。寸胴鍋、まな板、小さな七輪。屋根の端に風鈴。
- **路地**: 濡れた石畳、木の電柱、遠くに銭湯の煙突、奥に小さな鳥居。常に夜。天気は回ごとに変える(雨上がり/霧/雪/満月)。
- 文字は画面に出さない(AIの文字崩れ防止と言語非依存のため)。

## キャラクター(参照画像を最初に1枚ずつ作り、以後は必ず参照として使う)

| 名前 | 外見プロンプト(英語・固定) | 性格/役割 |
|---|---|---|
| **むぎ (Mugi)** 主人公 | `Mugi: a small calico cat (white, orange and black patches), a tiny notch on the left ear, round amber eyes, wearing a navy blue apron and a white twisted towel headband, stands on hind legs` | 無口な屋台の主人。表情は控えめ、耳としっぽで感情を出す。客の事情を察して黙って一品出す。 |
| **すず (Suzu)** | `Suzu: a tiny pure white kitten, half the size of Mugi, big pale-blue eyes, a small brass bell on a red string collar` | 1話で現れる迷子の子猫。やがて見習いに。失敗担当で視聴者の感情移入先。 |
| **しばさん (Shiba-san)** | `Shiba-san: a shiba inu office worker, loosened red necktie, rumpled white shirt, carrying a worn brown briefcase, tired droopy eyes` | 常連の疲れた会社員。毎回くたびれて来て、食べると尻尾が上がる。 |
| **げんさん (Gen-san)** | `Gen-san: a plump elderly tanuki, straw hat on his back, a green leaf on his head, round belly, rosy cheeks` | 酔いどれ常連。葉っぱで支払おうとする。コメディ担当。 |
| **こん (Kon)** | `Kon: a small skinny fox child, oversized patched yellow raincoat, holding three acorns` | お金のない子ぎつね。どんぐりで払う。泣かせ回担当。 |
| **くろ (Kuro)** | `Kuro: a sleek black cat, sharp green eyes, wearing a white chef jacket with gold buttons and a tall chef hat` | 2週目に登場するライバル。向かいにネオンぎらぎらのキッチンカーを出す。最後は和解。 |
| **カー (Kaa)** | `Kaa: a scruffy crow with one shiny button eye, a red thread tied on one leg` | なるとを盗むカラス。ギャグ回の常連。 |
| **しろ (Shiro)** | `Shiro: a slender adult pure white cat, big pale-blue eyes, a small brass bell on a red string collar identical to Suzu's` | EP14の最後に現れる白い大人の猫。第3章「すずの母編」の中心。 |

補足: すずはEP6以降、外見文の後ろに `, now also wearing a tiny navy apron with one white paw-print mark` を足す。こんは女の子として書く。

## 1本の基本構成(ショート 24〜40秒)
1. **0〜2秒 フック**: 感情の落差か「何が起きる?」を絵だけで見せる(泣いている子、空の財布、盗まれるなると)。屋台の全景から始めない。
2. **問題**: 客が何に困っているかを1カットで。
3. **調理(ASMR)**: 手元のマクロ。湯気、包丁、麺の湯切り、出汁を注ぐ音。ここが視聴維持の核。
4. **オチ/救い**: 食べた後の変化。小さなひねりを必ず入れる。
5. **引き**: 次回が気になる1カット(1秒)で終わる。最後のカットを最初のカットに絵的に近づけ、ループ再生を誘う。

## 音
- セリフ・ナレーションなし。猫の「にゃ」、麺をすする音、雨、風鈴、遠くの電車。
- BGMは同じテーマ曲を使い続ける(チャンネルの音の看板)。Sunoの有料プランで1曲作るか、YouTubeオーディオライブラリから固定で1曲選ぶ。他人の曲・流行曲は使わない。

## やらないこと
- 実在作品・実在キャラ・既存スタジオ名を画風指定に使わない
- 動物がひどく傷つく、虐待される描写(「不快・苦痛を与える内容」は収益化対象外)
- 同じ構図・同じ展開の使い回し(テンプレ反復判定の原因)
- 動物を危険な目に遭わせて救出する演出
