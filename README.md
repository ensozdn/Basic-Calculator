neyi neden kullandım ?
matematiksel işlemler yapmak için int (tam sayı) türüne ihtiyacım vardı
int: Tam sayı türünde bir değişken tanımlıyordu ihtiyacım olan asıl şeydi
Integer.parseInt bir String ifadeyi int türüne çevirir.
neden kullandım ? Çünkü EditText'ten gelen veri her zaman String olur, ama toplama, çıkarma, çarpma , bölme gibi basic bir hesap makinesi için işlemlerine int gerekir. Integer.parseInt sayesinde metni sayıya çevirerek işlemleri gerçekleştirebiliriz.
protected: Bu metod, bu sınıfın alt sınıfları tarafından erişilebilir ama dışarıdan erişilemez.
void: Geriye bir değer döndürmeyen metot.
public: Bu sınıfın (MainActivity) diğer sınıflar tarafından erişilebilir olmasını sağlar.
private: sadece aynı sınıf içinde erişebilir bir değişken ihtiyaç duymadığım için kullanmadım
(View view): Buton tıklandığında çağrılan metotlar olduğu için, tıklanan View nesnesini parametre olarak alıyor.
