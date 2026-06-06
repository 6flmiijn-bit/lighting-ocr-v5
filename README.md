# OCR照会 V3.5.1

Vercel用の全部入りファイルです。

## ファイル
- index.html
- package.json
- vercel.json
- sample_data.csv
- README.md

## Vercel
Build Command:
npm run build

Output Directory:
dist

## 内容
- V3.5 safe2ベース
- CSV書き出し時、チェックリスト0件ならCSV作成せず自動削除
- 1件以上ならCSV保存後に削除するか確認
- Vite不要
