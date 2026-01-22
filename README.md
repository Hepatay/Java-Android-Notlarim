# Java-Android-Notlarim
Bölüm 1: Java Temelleri & Değişkenler
int yas = 22;
long dunyaNufusu = 800000000L;
float fiyat =19.99f;
double pi= 3.14;
String isim = "Java";
//Bir değişkenin başına final kelimesini eklersen, o değişkenin değeri bir daha değiştirilemez.
final double PI_SAYISI = 3.14; 
// PI_SAYISI = 3.15; -> HATA VERİR!

// Değişken Tanımlama
int puan = 100;
double oran = 0.5;
String mesaj = "Hoşgeldiniz";

// Konsola Yazdırma
System.out.println(mesaj);
System.out.println("Puanınız: " + (puan * oran));

String[] meyveler = {"Elma", "Muz", "Çilek"};
//Metotlar: .add() ile ekle, .get() ile oku, .size() ile kaç eleman olduğunu gör.
ArrayList<String> isimler = new ArrayList<>();
isimler.add("Ahmet");
isimler.add("Zeynep");
Kullanım: HashMap<String, Integer> yaslar = new HashMap<>();
yaslar.put("Ahmet", 25); -> Ahmet anahtarına 25 değerini atar.

int yas = 20;

// If-Else Örneği
if (yas >= 18) {
    System.out.println("Ehliyet alabilirsin.");
} else {
    System.out.println("Yaşın henüz küçük.");
}

// For Döngüsü Örneği (0'dan 4'e kadar sayar)
for (int i = 0; i < 5; i++) {
    System.out.println("Döngü sayısı: " + i);
}

// While Döngüsü Örneği
int sayac = 0;
while (sayac < 3) {
    System.out.println("Çalışıyor...");
    sayac++;
}

onCreate(): Uygulama ilk açıldığında bir kez çalışır. (Kurulum burada yapılır).
onStart() / onResume(): Uygulama görünür hale geldiğinde çalışır.
onPause() / onStop(): Başka bir uygulamaya geçtiğinde çalışır.
onDestroy(): Uygulama tamamen kapatıldığında çalışır.

public: Her yerden ulaşılabilir.
private: Sadece tanımlandığı sınıf içinden ulaşılabilir (Güvenlik için çok önemlidir).
getter-setter private olarak tanımladığımız (sakladığımız) verilere güvenli bir şekilde ulaşmak ve onları değiştirmek için kullandığımız metotlardır.
Getter: Veriyi getirir.
Setter: Veriyi günceller/kurar.





Android Studio ile beraber java öğreniyorum bu yolda öğrendiklerimi not alıp kalıcı hale getirmek istedim.
