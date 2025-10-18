# mainobis

## Kısa Açıklama

`mainobis` projesi — (kısa ve öz açıklama: projenin amacı ne yapıyor, örn. "Basit bir Java uygulamasıyla veri işleme/arayüz/krivasyon" gibi). Bu README GitHub deposunda projenin kurulumu, çalıştırılması ve katkı kurallarını hızlıca gösterir.

## Özellikler

* Projenin temel işlevleri (ör. CLI/GUI, giriş/çıkış, dosya okuma-yazma)
* Kısa listede 2–4 önemli özellik

## Gereksinimler

* Java 8+ veya proje ile uyumlu JDK
* Maven veya Gradle (proje yapılandırmasına göre)
* (Opsiyonel) IDE: IntelliJ IDEA, Eclipse veya VS Code

## Kurulum (Yerel)

1. Depoyu klonlayın:

   ```bash
   git clone https://github.com/<kullanici-adiniz>/mainobis.git
   cd mainobis
   ```
2. Bağımlılıkları yükleyin ve projeyi derleyin:

   * Maven için:

     ```bash
     mvn clean install
     ```
   * Gradle için:

     ```bash
     ./gradlew build
     ```

## Çalıştırma

* Maven ile:

  ```bash
  mvn exec:java -Dexec.mainClass="com.yourpackage.Main"
  ```
* Jar dosyası ile:

  ```bash
  java -jar target/mainobis-1.0.jar
  ```

(Projede farklı bir `main` sınıfı
