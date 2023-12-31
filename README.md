![ADb Command](https://raw.githubusercontent.com/ebubekirbastama/EBS-ADB-slemleri/main/ebsadb.png)

# Nuget Adresi
 https://www.nuget.org/packages/EbubekirBastama.bastama_mobil_data_islemleri
# ADB Controller

Bu C# sınıfı, Android Debug Bridge (ADB) kullanarak mobil veri ve Wi-Fi bağlantılarını kontrol etmek için oluşturulmuştur.

## Kullanım

AdbController sınıfını kullanarak mobil veri ve Wi-Fi bağlantılarını kontrol edebilirsiniz.

Örnek kullanım:

```csharp
using BastamaMobilDataIslemleri;

class Program
{
    static void Main(string[] args)
    {
        AdbController adbController = new AdbController();

        // Mobil veri bağlantısını kapatma
        adbController.InternetKapat();

        // Mobil veri bağlantısını açma
        adbController.InternetAc();

        // Wi-Fi bağlantısını kapatma
        adbController.WifiKapat();

        // Wi-Fi bağlantısını açma
        adbController.WifiAc();

        // Uçak Modu Aç
        adbController.UcakModeAc();

        // Uçak Modu Kapat
        adbController.UcakModeKapa();

    }
}
````
# ADB Controller

Bu C# sınıfı, mobil veri ve Wi-Fi bağlantılarını kontrol etmek için ADB (Android Debug Bridge) kullanmaktadır.

## Kullanım

AdbController sınıfı, aşağıdaki işlevleri kullanarak bağlantı işlemlerini gerçekleştirebilir:

- InternetKapat
- InternetAc
- WifiKapat
- WifiAc

## Gereksinimler

Bu kodun çalışması için aşağıdaki gereksinimleri sağlamalısınız:

- .NET Framework veya .NET Core yüklü olmalıdır.
- ADB (Android Debug Bridge) kurulu olmalıdır.
