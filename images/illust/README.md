# おたより/タイムライン用イラスト素材（自作SVG・架空）

`otayori-newsletter.png` / `otayori-timeline.png` の写真枠に使用しているイラストの元データ。

再生成手順:
1. `daycare-timeline/web/newsletter-preview.html` をコピーし、6つの `nl-photo` の img src をこのSVGに差し替え、`.preview-note,.seasons{display:none}` をCSSに追加
2. ヘッドレスChromeで `--window-size=860,1610 --force-device-scale-factor=2 --hide-scrollbars --screenshot` で撮影 → `images/otayori-newsletter.png`
3. タイムラインは daycare-timeline のエミュレータ＋seedに本SVGを投稿画像として投入し、390x844(dpr2)でスクショ → `images/otayori-timeline.png`
