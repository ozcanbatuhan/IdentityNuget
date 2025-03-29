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

## 6. IdentityServer4' ü ASP.NET Core Projesine Dahil Etmek
 * ASP.NET Core projenizi File in Explorer şeklinde açın.
 * Proje ana dizini içinde "IdentityServer" klasörü oluşturun.
 * Sonra IdentityServer klasörü dizinine geçin ve şu komutu çalıştırın:
```sh
 dotnet new is4aspid --name <belirleyeceğin identity server proje adı>
```
* IDE' de projenizi açın ve ana dizinde "IdentityServer" klasörü oluşturun.
* IdentityServer klasörü içine existing project olarak "MultiShop.IdentityServer.csproj' u ekleyin.

## 7. IdentityServer İçeriğinin Kodlanması
Sonrasında tabloların oluşturulması ve yetkilendirilmelerin oluşturulması gibi kodlama işlemleri ile tam bir IdentityServer oluşturabilirsiniz.

Bu adımları tamamladıktan sonra IdentityServer4 ASP.NET Core projeniz başarıyla oluşturulmuş olacaktır.
