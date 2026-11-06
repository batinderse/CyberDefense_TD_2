# Mars Savunması

Bu depo, `MARS_SAVUNMASI.exe` adlı Windows oyun çalıştırılabilir dosyası ve Unity Player çalışma dosyalarını içerir. Depo içeriği, Unity Editor'da düzenlenebilir tam proje kaynakları yerine dağıtılabilir bir oyun derlemesidir.

## Çalıştırma

1. Depoyu Windows bilgisayara indirin veya klonlayın.
2. Depo kökündeki `MARS_SAVUNMASI.exe` dosyasını çalıştırın.
3. Oyun dosyalarını ve `MARS_SAVUNMASI_Data` klasörünü aynı dizinde tutun.

```powershell
.\MARS_SAVUNMASI.exe
```

Unity'nin gerekli çalışma zamanı dosyaları depoda `UnityPlayer.dll`, `UnityCrashHandler64.exe`, `D3D12`, `MonoBleedingEdge` ve `MARS_SAVUNMASI_Data` olarak bulunur. Bunları exe dosyasından ayrı taşımayın.

## Platform

Depodaki çalıştırılabilir dosya Windows içindir. Unity proje kaynakları depoda bulunmadığından bu içerikten oyunu Unity Editor ile yeniden derlemek mümkün değildir.
