# TemizMesaj resmi kural listesi

`v1.json` dosyası uygulama tarafından günde en fazla iki kez indirilir ve **ücretsiz dahil tüm kullanıcılara** uygulanır.

Yeni bir bahis markası veya dolandırıcılık terimi eklemek için:

1. `keywords` listesine küçük harfle, Türkçe karakter kullanmadan ekle (ör. `yenibet`). En az 3 harf.
2. Terim kelime başı olarak eşleşir: `yenibet` → "YENIBET10" yakalanır, "butceyenibetle" yakalanmaz.
3. Boşluklu terimler tam ifade olarak eşleşir (ör. `deneme bonusu`).
4. Günlük dilde geçen kelimeleri ekleme (ör. `stake`, `dede`, `sans`); gerçek mesajlar engellenir.
5. `version` alanını artır (ör. `2026-11-23.1`) ve kaydet. GitHub Pages birkaç dakikada yayınlar.

Sınırlar: en fazla 5.000 terim, terim başına 80 karakter, dosya 1 MB.
