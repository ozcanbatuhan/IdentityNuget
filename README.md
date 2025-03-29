# Kurulum Adımları

Bu doküman, IdentityServer4 ASP.NET Core şablonunu yüklemek için gerekli adımları içermektedir.

## 1. ZIP Dosyasını İndir ve Ayıkla
Öncelikle, gerekli paketleri içeren ZIP dosyasını indirin ve uygun bir dizine ayıklayın.

## 2. NuGet Kaynağını Ekle
Aşağıdaki komutu kullanarak ayıklanan dosyanın bulunduğu dizini NuGet kaynağı olarak ekleyin:
```sh
 dotnet nuget add source "<ayıklanan dosyanın yolu>"
```

## 3. Nesne Adını Kopyala
Ayıklanan dosyanın üzerine sağ tıklayın ve "Özellikler" bölümünü açın. Ardından "Güvenlik" sekmesine giderek "Nesne Adı" bilgisini kopyalayın.

## 4. Şablonu Yükle
Kopyaladığınız nesne adını aşağıdaki komutta kullanarak şablonu yükleyin:
```sh
 dotnet new install "<kopyalanan nesne adı>"
```

## 5. Yüklenen Şablonları Listele
Aşağıdaki komut ile yüklenen şablonları kontrol edebilirsiniz:
```sh
 dotnet new -l
```

## 6. Çalışma Dizini Değiştir
Ayıklanan dosyanın bulunduğu dizine geçin:
```sh
 cd <ayıklanan dosya yolu>
```

## 7. IdentityServer4 ASP.NET Core Şablonunu Oluştur
Şablonu oluşturmak için aşağıdaki komutu çalıştırın:
```sh
 dotnet new is4aspid
```

Bu adımları tamamladıktan sonra IdentityServer4 ASP.NET Core projeniz başarıyla oluşturulmuş olacaktır.
