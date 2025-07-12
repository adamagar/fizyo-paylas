# Ana Sayfa

Her Perşembe 21:00 (Türkiye Saati)

---

FizyoPaylaş, fizyoterapistler için haftalık çevrim içi bir buluşma ortamıdır.  
Gündemimiz serbesttir; her hafta bir konu belirlenir, ama sohbetin akışına göre bu konu değişebilir.  
Vaka paylaşımları, klinik tecrübeler, hasta iletişimi, özel sektör deneyimleri, yurtdışı süreçleri ve daha fazlası...

---

## FizyoPaylaş nedir?

- Her hafta düzenlenen 1 saatlik samimi bir Google Meet toplantısıdır.
- Fizik tedavi alanında çalışan ya da bu alana ilgi duyan herkese açıktır.
- Soru sorabilir, farklı bakış açıları duyabilir ve diğer fizyoterapistlerle tanışabilirsin.
- Katılım ücretsizdir.

---

## Toplantı bağlantısı nereden paylaşılır?

👉 [WhatsApp duyuru grubumuza katılmak için tıklayın](https://chat.whatsapp.com/DoQDwhhGB1N18IXJ8aJgsZ)  
(Toplantı linkleri toplantı günü bu gruptan paylaşılır)

---

## Kimler katılabilir?

- Aktif olarak çalışan fizyoterapistler
- Öğrenciler ve yeni mezunlar
- Kendi kliniğini açmak isteyenler
- Kamuda ya da özelde çalışanlar
- Yurtdışında fizyoterapi yapmak isteyenler

---

## Katılım şartı:

Sadece **nazik**, **destekleyici** ve **saygılı** olman yeterli.

---

Birlikte öğrenelim, paylaşalım ve güçlenelim.  
**#FizyoPaylaş**

---

## 📝 Son Blog Yazıları

{% raw %}
{% for post in blog.posts[:5] %}
### [{{ post.title }}]({{ post.url }})
📅 {{ post.date.strftime('%d %B %Y') }}

{{ post.description }}

{% endfor %}

{% if blog.pages > 1 %}
**Sayfalar:**  
{% for i in range(1, blog.pages + 1) %}
[{{ i }}](/page/{{ i }}/) 
{% endfor %}
{% endif %}
{% endraw %}