🔹 Afet Erken Uyarı Sistemi (LLM ile) → Sosyal Sinyal Algılama
1. Deprem Olduktan Sonra Erken Tespit (Early Detection)

Deprem anında insanlar Twitter’a ilk “deprem oldu mu?”, “hissedildi” gibi tweet’ler atıyor.

Resmî kurumlar (AFAD, Kandilli) açıklamadan dakikalar önce bu sinyaller toplanabilir.

LLM → bu paylaşımları filtreleyip, “gerçek deprem mi, şaka/yanlış alarm mı?” diye sınıflandırabilir.
👉 Böylece resmi açıklamadan daha erken erken algı yapılır.

2. Afet Sonrası İhtiyaç & Kriz Analizi

Deprem/sel/yangın sonrası sosyal medyada insanlar “su lazım, yardım yok, yol kapalı” gibi paylaşımlar yapıyor.

LLM → bu paylaşımları kategorize eder (yardım ihtiyacı, hasar bildirimi, panik, yanlış bilgi).

Bu sayede AFAD, belediye, STK’lar için kriz yönetimine destek sağlanır.

3. Kriz Öncesi Risk Sinyalleri (Preventive Insight)

Depremi önceden tahmin edemezsin ❌ ama sel/yangın/salgın gibi bazı krizlerin öncesinde sosyal medya sinyalleri çıkabiliyor:

“Baraj doldu, taşacak gibi”

“Yangın başladı ama kimse gelmedi”

“Grip salgını yayılıyor, okulda 10 kişi hasta”

LLM → bunları “potansiyel kriz sinyali” olarak işaretleyebilir.

🔹 Senin Çalışmanda Senaryolar

Teknik tarafı: Low-resource fine-tuning (LoRA, QLoRA, Adapter vs.) yöntemlerini Türkçe sosyal medya verisi üzerinde denersin.

Uygulama tarafı:

Senaryo A: Deprem olduktan sonra halkın tweetlerinden “resmî açıklamadan daha erken tespit”.

Senaryo B: Afet sonrası ihtiyaç kategorileri (yardım, sağlık, barınma).

Senaryo C: Sel/yangın/salgın gibi kriz öncesi sosyal medya sinyalleri.

👉 Böylece hem yayın değeri olan metodoloji çıkarırsın, hem de TÜBİTAK’a toplumsal fayda diye yazarsın.

📌 Kısacası:
“Deprem olacak hissediyorum” tweetleri tek başına bir şey ifade etmez, ama binlerce tweetin LLM ile sınıflandırılması ciddi bir erken sinyal oluşturur.
