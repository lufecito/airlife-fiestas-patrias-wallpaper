# Fondo de pantalla Airlife — Fiestas Patrias

Fondo corporativo de Airlife inspirado en las Fiestas Patrias de Chile, preparado para su distribución y uso automatizado en equipos Windows.

![Vista previa del fondo de pantalla](airlife-fiestas-patrias.png)

## Descarga directa

La imagen está disponible como `airlife-fiestas-patrias.png`.

```powershell
$url = 'https://raw.githubusercontent.com/lufecito/airlife-fiestas-patrias-wallpaper/main/airlife-fiestas-patrias.png'
$destino = Join-Path $env:TEMP 'airlife-fiestas-patrias.png'
Invoke-WebRequest -Uri $url -OutFile $destino
```

> El nombre del archivo y la URL se mantienen simples para facilitar su uso en scripts de despliegue.
