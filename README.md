# address_into_postcode
Code for converting an address into a postcode.

- 住所から郵便番号を検索する。
- 東京都港区白金1-3-4なども対応

```python:main.py
raku_df = post_code().run('東京都港区白金')
print(raku_df)
```
