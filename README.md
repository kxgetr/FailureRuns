# FailureRuns

Geçme-kalma geçmişindeki en uzun kesintisiz başarısızlığı ölçer.

## Girdi

Boolean dizisi; true geçiştir.

## Kullanım

Python 3.11+, standart kütüphane.

```sh
python failureruns.py input.json
python verify.py
```

Dosya verilmezse stdin okunur. Sonuç stdout üzerinde JSON olarak yazılır. Girdi hatası çıkış kodu 2 üretir.

Örnek sonuç:

```json
2
```
