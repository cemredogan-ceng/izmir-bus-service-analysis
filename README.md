# İzmir Otobüs Sefer Yoğunluğu – 757 & 619

Bu repo, 757 ve 619 için gün×saat sefer yoğunluğu, durakların harita üzerinde gösterimi (≤300 m erişim doğrulaması) ve opsiyonel K-Means kümelemeyi içerir.

## Veri Setleri
- eshot-otobus-hareketsaatleri.csv (ayraç `;`, TARIFE_ID→{Hafta içi, Cumartesi, Pazar} varsayımı)
- eshot-otobus-duraklari.csv (ENLEM/BOYLAM WGS84, DURAKTAN_GECEN_HATLAR token’lı)
> Not: Büyük/lisanslı verileri repo dışı tutuyorum; notebook `data/` altından okur.

## Çalıştırma
```bash
python -m venv .venv && source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```
