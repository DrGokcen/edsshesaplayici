# EDSS Hesaplayıcı

Multipl Skleroz (MS) hastalarında kullanılan **Kurtzke Genişletilmiş Engellilik Durumu Ölçeği (EDSS)** ve **Fonksiyonel Sistem Puanlaması (FSS)** için geliştirilmiş, Türkçe ve mobil öncelikli bir klinik hesaplama aracıdır.

🔗 **Canlı uygulama:** https://drgokcen.github.io/edsshesaplayici/

---

## Amaç

Nöroloji kliniklerinde EDSS skorlamasını günlük pratikte hızlandırmak, standardize etmek ve Türkçe klinik açıklamalarla daha anlaşılır hale getirmek amacıyla geliştirilmiştir. Şu an ilk (MVP) sürümdür ve klinik kullanıcılardan geri bildirim toplanarak geliştirilmeye devam edilmektedir.

## Özellikler

- Yürüme durumu ve 7 fonksiyonel sistemin (piramidal, serebellar, beyin sapı, duyusal, bağırsak/mesane, görme, serebral) ayrı ayrı değerlendirilmesi
- Her derece için Türkçe klinik açıklama ve günlük hayattan somut örnekler
- Tamamlanma durumu takibi ve skora göre renklenen sonuç çubuğu
- **Hiçbir hasta verisi toplanmaz** — ad, TC kimlik no, protokol no gibi bir alan yoktur; hesaplama tamamen cihaz üzerinde (client-side) yapılır, sunucuya hiçbir veri gönderilmez

## Metodoloji

Bu araç, Kurtzke'nin (1983) tanımladığı EDSS/FSS ölçeğinin kural tabanlı bir uygulamasıdır. Sınırda (borderline) FS kombinasyonlarında nihai puanlama her zaman klinik değerlendirme gerektirir. Hesaplama mantığı, gerçek klinik senaryolarla karşılaştırılarak sürekli doğrulanmaktadır; algoritmada bir hata fark ederseniz lütfen bir Issue açın.

## Kaynak

> Kurtzke JF. Rating neurologic impairment in multiple sclerosis: an expanded disability status scale (EDSS). *Neurology.* 1983;33(11):1444–1452.

EDSS/FSS ölçeğinin kendisi kamuya açık (public domain) bilimsel bir standarttır. Bu proje, söz konusu yayındaki tanımlardan yola çıkılarak bağımsız olarak geliştirilmiştir; herhangi bir ticari hesaplayıcı ile bağlantılı değildir ve onların metin, tasarım ya da kodunu kullanmaz.

## Sorumluluk Reddi

Bu araç, Kurtzke EDSS/FSS ölçeğinin kural tabanlı bir yaklaşımıdır; sınırda kalan kombinasyonlarda nihai puanlama klinik değerlendirme gerektirir. Resmi bir tıbbi cihaz ya da onaylı/sertifikalı bir hesaplayıcının birebir kopyası değildir. Sonuçlar, tedavi kararlarında tek başına kullanılmamalıdır.


## Sürüm

- **v1.2** (2026-09) — Zaman çizelgesi ikonları özel görsellerle güncellendi, sonuç çubuğuna skora göre renklenme ve yumuşak geçiş animasyonları eklendi, EDSS/FSS hesaplama mantığında iki hata düzeltildi (serebral derece-1'in hesaba katılmaması, derece 3 + derece 2 kombinasyonunun 3.5 olarak düzeltilmesi), kaynak atfı eklendi.
- **v1.0** — İlk yayın: 8 alanlı değerlendirme, Türkçe açıklamalar, temel EDSS/FSS hesaplama mantığı.

## Geliştirici

Dr. Gökçen — nöroloji kliniğinde günlük ihtiyaçtan yola çıkarak geliştirilmiştir. Geri bildirim ve öneriler için lütfen bu depoda bir **Issue** açın.

## Lisans

Lisans şartları henüz belirlenmemiştir; şimdilik tüm hakları saklıdır. Kaynak kodun açık kaynak olarak yayınlanıp yayınlanmayacağına ilerleyen sürümlerde karar verilecektir.
