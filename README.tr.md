# Awesome Turkish MCP [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Türkçe veri ve alanlar için derlenmiş [Model Context Protocol](https://modelcontextprotocol.io) sunucuları — bir AI ajanının Türk hukuk, finans, kamu, akademik ve iş kaynaklarına tipli, denetlenebilir araçlarla erişebilmesi için.

🇬🇧 English: [README.md](README.md)

Dünyadaki MCP sunucularının çoğu İngilizce, küresel kaynakları sarmalar. Oysa Türk kurumları — mahkemeler, `mevzuat.gov.tr`, Borsa İstanbul, EKAP, TÜRKPATENT, YÖK — bir ajanın gerçekten kullanabileceği veriyi yayımlıyor; yeter ki biri onu araçlara eşlesin. Bu liste, bunu yapan sunucuları tek yerde toplar; her seferinde tek tek aramak yerine buradan bul.

Tüm girişler açık kaynaktır ve aksi belirtilmedikçe yerel (stdio) çalışır. Katkılar memnuniyetle — bkz. [Katkı](#katkı).

## İçindekiler

- [Hukuk & Mevzuat](#hukuk--mevzuat)
- [Kamu & Resmî Kayıtlar](#kamu--resmî-kayıtlar)
- [Finans & Piyasalar](#finans--piyasalar)
- [Akademik & Araştırma](#akademik--araştırma)
- [İş & ERP](#i̇ş--erp)
- [Hava Durumu](#hava-durumu)
- [İlgili Araçlar & Kütüphaneler](#i̇lgili-araçlar--kütüphaneler)
- [Katkı](#katkı)

## Hukuk & Mevzuat

- [yargi-mcp](https://github.com/saidsurucu/yargi-mcp) - Türk mahkemeleri ve hukuk veritabanlarında arama — Yargıtay, Danıştay, Anayasa Mahkemesi, Sayıştay, KVKK ve daha fazlası — yapılandırılmış araçlar olarak.
- [mevzuat-mcp](https://github.com/saidsurucu/mevzuat-mcp) - `mevzuat.gov.tr` üzerinden güncel Türk mevzuatını arama ve okuma.

## Kamu & Resmî Kayıtlar

- [ihale-mcp](https://github.com/saidsurucu/ihale-mcp) - EKAP portalından Türk kamu ihalelerini sorgulama.
- [markapatent-mcp](https://github.com/saidsurucu/markapatent-mcp) - TÜRKPATENT marka, patent ve endüstriyel tasarım araması.

## Finans & Piyasalar

- [borsa-mcp](https://github.com/saidsurucu/borsa-mcp) - Borsa İstanbul (BIST) hisseleri, yatırım fonları, döviz ve makro verisi; ABD piyasaları ve kripto ile birlikte.

## Akademik & Araştırma

- [yokatlas-mcp](https://github.com/saidsurucu/yokatlas-mcp) - YÖK Atlas sorgulama — Türk üniversite programları, yerleşme puanları ve kontenjanları.
- [yoktez-mcp](https://github.com/saidsurucu/yoktez-mcp) - Ulusal Tez Merkezi (YÖK Tez) araması.
- [literatur-mcp](https://github.com/saidsurucu/literatur-mcp) - DergiPark'tan Türk akademik dergi makalelerini arama ve analiz.

## İş & ERP

- [erp-report-engine](https://github.com/gulmezeren2-byte/erp-report-engine) - ERP'nin arkasındaki SQL veritabanına salt-okunur erişim (Logo Tiger, Netsis, Mikro): ajan, kanonik varlıkları ifadeyi denetleyen bir bekçi üzerinden sorgular; halka açık 28-saldırı benchmark'ıyla ölçülür.

## Hava Durumu

- [MCP-Turkey-Weather](https://github.com/emredeveloper/MCP-Turkey-Weather) - Türkiye'deki konumlar için hava durumu verisi.

## İlgili Araçlar & Kütüphaneler

Aynı ekosistemdeki ajan-odaklı CLI'lar, skill'ler ve kütüphaneler — MCP sunucusu değiller ama aynı iş için yapıldılar.

- [yargi-cli](https://github.com/saidsurucu/yargi-cli) - Türk hukuk veritabanlarına komut satırından erişim; AI ajanları için tasarlandı.
- [borsapy](https://github.com/saidsurucu/borsapy) - Türk finans piyasaları için Python kütüphanesi (BIST hisseleri, fonlar, döviz).
- [turkce-imla-skill](https://github.com/saidsurucu/turkce-imla-skill) - Türkçe imla ve dil bilgisi için Claude skill'i.
- [markapatent-skill](https://github.com/saidsurucu/markapatent-skill) - Claude-in-Chrome ile TÜRKPATENT araması için Claude skill'i.
- [trdizin-skill](https://github.com/saidsurucu/trdizin-skill) - TR Dizin akademik indeksinde arama için Claude skill'i.

## Katkı

Buraya ait bir Türkçe-alan MCP sunucusu buldun ya da geliştirdin mi? [Pull request aç](CONTRIBUTING.md). Ölçüt basit: açık kaynak olsun, çalışsın ve Türkçe veriye ya da bir Türk alanına hizmet etsin.

Yukarıdaki ekosistemin büyük kısmı [@saidsurucu](https://github.com/saidsurucu) tarafından geliştirildi — bu liste o emeğin üstünde duruyor.

## Lisans

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

Yasaların izin verdiği ölçüde, katkıda bulunanlar bu esere ilişkin tüm telif ve komşu haklarından feragat etmiştir.
