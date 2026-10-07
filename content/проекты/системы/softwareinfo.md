# Инвентаризация программного обеспечения — сетевой ресурс `Work.Drive`

Источник: `/data/net/Work.Drive/` на `aster.leargun.site` (общий сетевой диск).
Снимок: 2026-08-20. Метод: `find -printf` по всем файлам/каталогам (без распаковки архивов и образов, без чтения содержимого).
Всего: **43 021 файл**, **3 689 каталогов**, суммарный объём ~**190 ГБ**.

Основная масса файлов — внутренности распакованных сборок/драйверпаков и шрифты, поэтому
крупные распакованные коллекции описаны сводно (счётчик файлов + ключевые установщики),
а дистрибутивы, установщики, образы и архивы перечислены явно.

---

## Структура верхнего уровня

| Каталог | Файлов | Объём |
|---|---|---|
| `01 Программы для Менеджеровского компа` | 41 433 | 162.3 ГБ |
| `Windows 10 x64 Lite 1709 (16299.125) for SSD v4 xlx` | 517 | 5.8 ГБ |
| `Win 7 устанавливаем` | 14 | 7.1 ГБ |
| `Windows 10 Enterprise 2016 LTSB 14393 Version 1607 RU 16.08.2018` | 3 | 5.1 ГБ |
| `PROMT Professional v 9.0.443 Giant Portable` | 573 | 485 МБ |
| `Ace Utilities` | 267 | 4.1 МБ |
| `Bandicam v4.5.8.1673 Portable by CheshireCat Ml_Rus` | 94 | 67 МБ |
| `Activators` | 36 | 5.2 МБ |
| `CorelLaser` | 31 | 33.7 МБ |
| `Xilisoft DVD Ripper Ultimate v7.5.0 ...` | 20 | 36 МБ |
| `Movavi Video Editor Plus 2020 v20.3.0 ...` | 14 | 143 МБ |
| `Xilisoft_MKV_Converter_5.1.20.0121_Rus` | 3 | 16 МБ |
| `Acronis Disk Director 12 Build 12.0.96 RePack by KpoJIuK [Ru]` | 2 | 239 МБ |
| корневые файлы | 10 | 1.4 ГБ |
| `System Volume Information` | 4 | 709 КБ |

В корне диска: `MACChange.exe`, `Yandex_Music_x64_5.0.6.exe` (71 МБ),
`Автореферат.rar`, `Заказ Ломонд Назметдинов РР.xls`, `Ломонд 28.10 Заказ Назметдинов РР (1).xls`,
`Инструкции по настройке.docx`, `Назначение Программы.xps`, `Тест для принтера A4.jpg`,
`новая музыка с рекламой.mp3` (1.4 ГБ), `packer.ps1`.

---

## 1. Бесплатное ПО

| Пакет                                                     | Файлов | Ключевые установщики                                                                                                                   |
| --------------------------------------------------------- | ------ | -------------------------------------------------------------------------------------------------------------------------------------- |
| **7-Zip**                                                 | —      | `7z2201-x64.exe`, `7z2301-x64.exe`, `7z2409-x64.exe`                                                                                   |
| **AnyDesk** (`19. AnyDesk`)                               | 10     | `AnyDesk.exe`, `12. AnyDesk1.exe`, `AnyDesk (1).exe`                                                                                   |
| **TeamViewer**                                            | —      | `TeamViewer 10.0.43174.exe`, `TeamViewer_Setup.exe`                                                                                    |
| **Open Office** (`11. Open Office`)                       | 2      | `Apache_OpenOffice_4.1.11_Win_x86_install_ru.exe`, `OOo_2.3.1_Win32Intel_install_wJRE_ru.exe`                                          |
| **PDF24 Creator** (`Pdf24 Creator`)                       | 1 227  | `pdf24-creator-9.0.4.exe`, `pdf24-creator-9.2.1.exe`, `pdf24-creator-9.4.0-x64.exe`, `pdf24-creator-11.18.0-x64.exe`, `gswin64c.exe`   |
| **Adobe Reader** (`08. AdobeReader`)                      | 13     | `AdbeRdr810_ru_RU.exe`, `AdobeReader.exe`                                                                                              |
| **AIMP** (`AIMP v4.51.2070 RePack+Portable by Dodakaedr`) | 3      | `AIMP_v4.51.2070.exe`                                                                                                                  |
| **PotPlayer** (`PotPlayer 1.5.29590`)                     | 9      | `pot1.7.12845.x86.exe`, `pot1.7.12845.x64.exe` (в Win 10 tools; распакованная сборка)                                                  |
| **Daum PotPlayer** (в Win 10 Lite)                        | —      | `pot1.7.12845.x64.exe`, `pot1.7.12845.x86.exe` (RePack by 7sh3)                                                                        |
| **uTorrent** (`uTorrent`, в ДрайверПаки, в Win 10 Lite)   | 17     | `uTorrent.exe`, `utorrent.exe`, `µTorrent Stable (1.0.3).dmg`, `Beta-Version µTorrent (1.5.6).dmg`, `utorrent-server-3.0-25053.tar.gz` |
| **Yandex** (`Yandex`)                                     | 46     | `Yandex.exe`, `Yandex.Corporate.exe`, `Yandex_Music_x64_5.0.6.exe`                                                                     |
| **Скриншот** (`Skrinshot`)                                | 2      | `SkrinshoterSetup_4.0.0.59.exe`, `setup-lightshot.exe`                                                                                 |
| **Speedtest**                                             | —      | `speedtestbyookla_x64.msi`                                                                                                             |
| **Syncthing**                                             | —      | `syncthing-windows-setup.exe` (в корне папки `01 Программы...`)                                                                        |
| **Win 10 tools** (`29. Win 10 tools`)                     | 13     | `EdgeBlock.exe`, `EdgeBlock_x64.exe`, `Win 10 Tweaker.exe`, `OOSU10.exe`, `ndp48-x86-x64-allos-enu.exe`, `tweak-ssd-v2-setup.exe`      |
| **WindowsLoader / активация** — см. раздел «Активаторы»   |        |                                                                                                                                        |
| **WinRAR** (`14. WinRar`)                                 | 29     | `winrar-x64-711ru.exe`, `wrar380ru.exe` (shareware; ключи в папке)                                                                     |
| **Kaspersky Free** (бесплатная версия)                    | —      | `Kaspersky Free Antivirus 19.0.0.1088 (a) Repack by LcHNextGen (19.07.2018).exe`, `Скин для KFA, KAV, KIS, KTS 19.0.0.1088.exe`        |

Различные runtime и компоненты (бесплатные, входят в состав сборок): `vc_redist.x86/x64.exe`,
`vcredist_x86/x64.exe`, `ndp47/ndp48-x86-x64-allos-enu.exe`, `dxwebsetup.exe`,
`msxml6_x64.msi`, `WindowsInstaller-KB893803-x86.exe`.

---

## 2. Лицензионное ПО (дистрибутивы + кряки/ключи)

> Отдельные `Crack`/`Keygen`/`RePack`-папки выделены в разделе «Активаторы».

### 2.1. Офисные пакеты и редакторы

| Пакет                                    | Папка                                                                                      | Файлов | Ключевые файлы                                                                                                                                                                                                                                                                                                                                                                                          |
| ---------------------------------------- | ------------------------------------------------------------------------------------------ | ------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Microsoft Office 2010 SP2 VL**         | `08. Microsoft Office/08. Microsoft Office 2010 with SP2 VL [SELECT] Russian`              | 13     | `KMS.rar` (активация)                                                                                                                                                                                                                                                                                                                                                                                   |
| **Microsoft Office 2016 Standard**       | `08. Microsoft Office`                                                                     | —      | `Microsoft.Office.2016x64.Standard.v2017.02.exe` (1.9 ГБ, RePack by KpoJIuK)                                                                                                                                                                                                                                                                                                                            |
| **Microsoft Office 2019 Pro Plus**       | `08. Microsoft Office/Microsoft Office 2019 Professional Plus 16.0.10730.20102 RTM-Retail` | 115    | `Microsoft Office 2019 Pro_@SoftFULL.rar` (2.3 ГБ), `Setup.exe`                                                                                                                                                                                                                                                                                                                                         |
| **1C Предприятие**                       | `03. 1C Предприятие`                                                                       | 205    | `8.3.8.2322_windows/`, `windows64full_8_3_23_1912.rar`, `windows64full_8_3_23_1912/setup.exe`, `1CBarCode_8.0.16.4.exe`, `CEL_2.0.6.14_setup1c.zip`                                                                                                                                                                                                                                                     |
| **Open Office** (бесплатно, см. разд. 1) | `11. Open Office`                                                                          | 2      |                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Total Commander**                      | `03. Total Commander 7.50a ExtremePack 2010.1`                                             | 7      | `Total Commander 7.50a ExtremePack 2010.1 Rus.exe`, `.rar`                                                                                                                                                                                                                                                                                                                                              |
| **ABBYY FineReader 11/12/14**            | `07. ABBYY Fine Reader`                                                                    | 2 533  | `ABBYY.FineReader.v11.0.102.583.exe` (216 МБ, RePack by KpoJIuK), `ABBYY.FineReader.v12.0.101.388.exe` (RePack by KpoJIuK), `ABBYY FineReader 14 v14.0.105.234 Enterprise Editions/FR14_ENTMULTI/` (распакованная сборка, `Setup.exe`)                                                                                                                                                                  |
| **Adobe Reader Pro DC**                  | `08. AdobeReader`                                                                          | 13     | `Adobe Acrobat Pro DC v2019.010.20099 RePack by KpoJIuK` (с `activation/Keygen.exe`)                                                                                                                                                                                                                                                                                                                    |
| **Adobe Photoshop CS2/CS6/CC2018**       | `05. Adobe Photoshop`                                                                      | 428    | `Adobe Photoshop CS 2 v.9.0/`, `Adobe Photoshop CS6 (13.1.2) x64 .exe` (336 МБ), `Adobe Photoshop CC 2018 v19.1.8.442 RePack by m0nkrus x86/Adobe.Photoshop.CC.2018.u1.x86.Multilingual.iso` (1.5 ГБ), `Adobe Photoshop 2020 21.2.12.215 (Win7) RePack by KpoJIuK.exe`, `readmecd_cs2tda_and_keygen.zip` (кряк), `PhotoShop 9.0 Rus.zip`                                                                |
| **Adobe Illustrator CC 2019**            | `16. Adobe Illustrator`                                                                    | 231    | `Adobe.Illustrator.2019.u2.x64.Multilingual.iso` (2.0 ГБ, 3 копии x86/x64), `Adobe Illustrator CC 2019 v23.0.3.585 RePack by m0nkrus (x86/x64)`                                                                                                                                                                                                                                                         |
| **CorelDRAW X7/2019–2022**               | `09. CorelDRAW`                                                                            | 23     | `CorelDRAW.GraphicsSuite.2019.en-ru.iso` (1.8 ГБ), `CorelDRAW.GraphicsSuite.2019.x64.en-ru.UP.3.exe` (922 МБ), `CorelDRAW.GraphicsSuite.2020.x64.en-ru.exe` (598 МБ), `CorelDRAW.Graphics.Suite.2021.v23.5.0.506.exe` (671 МБ), `CorelDRAW.Graphics.Suite.2022.v24.2.1.446.exe` (779 МБ), `CorelDRAW Graphics Suite 2020 ... KeyGen by tisn05.exe`, `CorelDRAW Graphics Suite X7 17.1.0.572 Retail.iso` |
| **PROMT Professional 9.0**               | `PROMT Professional v 9.0.443 Giant Portable`                                              | 573    | `PROMT Professional 9.0.exe` (Portable Giant)                                                                                                                                                                                                                                                                                                                                                           |
| **Фото на документы Профи**              | `21. Фото на документы Профи 6.0`                                                          | 7      | `Фото на документы Профи 6.0 [Rus] Portable by Strelec.exe`, `Фото на документы Профи 8.0 Repack by KaktusTV.exe`, `Фото на документы Профи 8.15 RePack by KaktusTV.exe`                                                                                                                                                                                                                                |

### 2.2. САПР и инженерное ПО

| Пакет                                         | Папка         | Файлов | Ключевые файлы                                                                                                                                                                                                                                                                          |
| --------------------------------------------- | ------------- | ------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **AutoCAD 2010/2020/2025, Architecture 2014** | `08. AutoCAD` | 6 198  | `Autodesk_AutoCAD_2010_ru_x86_x64.iso` (2.8 ГБ), `Autodesk.AutoCAD.2020.ru-en.iso` (3.8 ГБ), `10. Autodesk_AutoCAD/` (распакованная сборка 2020), `08. AutoCAD 2020/` (распакованная сборка), `AutoCad 2025/`, `10. Autodesk_AutoCAD_Architecture_2014_SP1/` (с `xf-adsk32.exe` — кряк) |
| **КОМПАС-3D v20/v21/v22/v24**                 | `12. Компас`  | 162    | `KOMPAS-3D_v20_Study_x86.zip` (1.6 ГБ), `KOMPAS-3D v20/` (x32+x64, распаковано, `Setup.exe`, `Setup.msi`, CNC-модули, `! Crack !/`), `KOMPAS-3D v21 x64/`, `KOMPAS-3D_v22_Study_x64/`, `KOMPAS-3D_v24_Study_x64.iso`                                                                    |

### 2.3. Мультимедиа, утилиты, прочее

| Пакет                                            | Папка                                                                                                                        | Файлов | Ключевые файлы                                                                                                                                                                                                                                                                                                                                                                    |
| ------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------- | ------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Alcohol 120%**                                 | `01. Установка Виртуального привода`                                                                                         | 77     | `Alcohol 120% v2.0.3 Build 9902 Retail Ml_Rus/`, `Alcohol 120% v2.1.0 Build 30316 Retail Ml_Rus/`, `Alcohol120_retail_2.0.2.5830/` (RePack+Standalone, `SPTDinst-v186-x86/x64.exe`), `Alcohol120_retail_2.0.3.9902.exe` (в Win 10 Lite)                                                                                                                                           |
| **UltraISO**                                     | `01. Установка Виртуального привода`                                                                                         |        | `UltraISO Premium Edition v9.6.5.3237 Retail Ml_Rus (DC 22.07.2015)`, `v9.7.2.3561 Retail RePack by Trava79`, `9.7.5.3716 (RePack & Portable) by TryRooM` (+ `KeyGen.exe`)                                                                                                                                                                                                        |
| **Nero 7/8**                                     | `13. Nero`                                                                                                                   | 14     | `Nero 7/`, `Nero 8/`                                                                                                                                                                                                                                                                                                                                                              |
| **ACDSee**                                       | `06. ACDSee`                                                                                                                 | 40     | `06. ACDSee 5.0/` (с `Keygen/`), `ACDSee.v7.0.47/`, `acdsee-5.0-powerpack-rus-idion-ru`, `06. ACDSee Pro v8.2 Build 287 Lite RePack by MKN`                                                                                                                                                                                                                                       |
| **Movavi Video Editor/Converter**                | `Movavi Video Editor Plus 2020 ...` + `prg.win.movavi_video_converter.22-5-0.x64`                                            | 15     | `MovaviVideoEditorPlusSetup_x32.exe`, `MovaviVideoEditorPlusSetup_x64.exe`, `Movavi Video Converter Premium 22.5.0.exe`                                                                                                                                                                                                                                                           |
| **Xilisoft DVD Ripper / MKV Converter**          | `Xilisoft DVD Ripper Ultimate v7.5.0 ...`, `Xilisoft_MKV_Converter_5.1.20.0121_Rus`                                          | 23     | `x-dvd-ripper-ultimate7.exe`, `patch_BBB/`, `x-mkv-converter.exe`, `Crack.exe`, `rus.exe`                                                                                                                                                                                                                                                                                         |
| **Bandicam**                                     | `Bandicam v4.5.8.1673 Portable by CheshireCat Ml_Rus`, `Bandicam.7-RSLOAD.NET-`, `Bandicam.v8.2.2.2531`                      | ~120   | `Bandicam v4.5.8.1673 Portable by CheshireCat.exe`, `Bandicam_Portable.exe`, `Bandicam_Portable_NonAdmin.exe`                                                                                                                                                                                                                                                                     |
| **Acronis Disk Director 12**                     | `Acronis Disk Director 12 Build 12.0.96 RePack by KpoJIuK [Ru]`, `Acronis Disk Director 12 Build 12.5.163 RePack by KpoJIuK` | 7      | `Acronis.Disk.Director.v12.0.0.96.exe`, `AcronisDiskDirector12.5_163_ru-RU.exe`                                                                                                                                                                                                                                                                                                   |
| **CCleaner Professional Plus**                   | `CCleaner Professional Plus v5.55 Retail Ml_Rus`                                                                             | 7      | `CCleanerBundle-555-Setup.exe`                                                                                                                                                                                                                                                                                                                                                    |
| **Defraggler Professional**                      | `Defraggler Professional v2.15.742 Final Ml_Rus`                                                                             | 6      | `dfsetup215.exe` + `Crack/`                                                                                                                                                                                                                                                                                                                                                       |
| **Tweak-SSD**                                    | `28. Tweak-SSD v2.0.41Настройка SSD диска`                                                                                   | 9      | `tweak-ssd-v2-setup.exe` + `Crack/` (x86/x64)                                                                                                                                                                                                                                                                                                                                     |
| **Ace Utilities**                                | `Ace Utilities`                                                                                                              | 267    | `au.exe`, `da.exe`, `webupdate.exe`                                                                                                                                                                                                                                                                                                                                               |
| **USB Disk Security**                            | `04. USB Disk Security v6.4.0.1 Final Ml_Rus`                                                                                | 48     | `USB Disk Security 6.4.0.1 RePack by KpoJIuK/D!akov`, `USB Disk Security v6.6.0.0 RePack by wvxwxvw Ml_Rus`, `USB Disk Security 6.4.0.1 Rus Portable by Valx`, `USB Disk Security v6.4.0.200 Final Ml_Rus`, `USBGuard6.4.0.1.exe`                                                                                                                                                 |
| **MailboxScan**                                  | `MailboxScan`                                                                                                                | 22     | `WFSS v1.5.3.4/`                                                                                                                                                                                                                                                                                                                                                                  |
| **Kaspersky Anti-Virus** (коммерч.)              | `Kaspersky Anti-Virus`                                                                                                       | 12 961 | `KAV/kav6.0.3.837_winwksru.exe`, `KAV/kav6.0.4.1424_winwksru.exe`, `KAV/setup_9.0.0.722_30.04.2010_11-21.exe`, `Антивирус Касперского 2013/kav13.0.1.4190ru-ru.exe`, `Kaspersky Anti-Virus 2016, Kaspersky Internet Security 2016/startup.exe` + `Сброс активации/` (`KRT.sfx.exe`, `Kaspersky Reset Trial.sfx.exe`); большая часть — базы обновлений (`KAV/обновление каспера/`) |
| **Epson adjustment program** (сервисная утилита) | `Epson adjustment program`                                                                                                   | 10     | `Epson adjustment program L800 сброс.rar`, `Epson p50-adjustment`                                                                                                                                                                                                                                                                                                                 |
| **Datacolor Spyder** (калибровка цвета)          | `Коллибровка цвета` (также в `Драйвера на принтер/`)                                                                         | 77+    | `Datacolor Монитор 302730-140180-153832.iso`, `Datacolor.iso`, `spyderprint 890710-937300-211232.rar` (176 МБ), `spyderprint/`                                                                                                                                                                                                                                                    |
| **Xerox MailBox Scan**                           | `MailboxScan`, `Xerox 6204/Xerox 6204 MailBox Skan`                                                                          | 22     | `WFSS v1.5.3.4/setup.exe`                                                                                                                                                                                                                                                                                                                                                         |
| **Шрифты**                                       | `Шрифт`                                                                                                                      | 3 122  | набор TTF/OTF (2 242 ttf, 875+ otf)                                                                                                                                                                                                                                                                                                                                               |

---

## 3. Драйверы принтеров

Общая папка **`Драйвера на принтер`** — 10 469 файлов, 5.4 ГБ. Внутри — распакованные дистрибутивы
драйверов и утилит печати:

| Производитель / модель | Папки / файлы |
|---|---|
| **Epson (плоттер)** | `EPSON 1410/` (распакованный дистрибутив, драйверы WIN9X/WINXP_2K/WINXP64 + `EasyPhotoPrint`, `Printcd`, `EasyPrintModule`, `CameraRAWPlugin`, руководства `MANUAL/` на 10 языках), `Образ Epson L805.iso` (276 МБ), `Epson L800.iso` (261 МБ), `epson_l1110.exe`, `epson661623eu.exe`, `epson627849eu.exe`, `epson373667eu.exe`, `epson374885eu.exe`, `epson630288eu.exe`, `3110197-00_L805_EA_Vol11.zip` |
| **Epson (T50/T59/R290)** | `утилиты epson t50/`, `SPT50_T59_Win32_661ERU.zip`, `SPR290_Win32_653ERU.zip`, `др epson r290/`, `SPR270_Win32_611ERU.zip`, `Epson Print CD.exe`, `EPSON Easy Photo Print (v2.83.00).exe`, `epson-easyprint-module.rar`, `EasyPhotoPrint/`, `L800_PRTDRV_x32_6.72_Home_Export` |
| **HP** | `Образ Принтерп 2055/` (образ `HP_P2050.iso`, 657 МБ), `hp_dj_430.zip`, `hpdj510wx64glen.exe`, `hpdjt1100serieswumgl.exe`, `HP T1100/`, `P2055_default_install_v6.1_ww.exe` |
| **Xerox WorkCentre m24** | `дрова Xerox WorkCentre m24/` (`M24_64bits_English.zip`, `x64-M24-Mini_PCL.zip`, `XCWC-Eng-Win2k-15Feb2007.zip`, `WC_7132_Scan/Disk1/Setup.exe`) |
| **Xerox DC 252** | `Xerox DC 252 PS Driver`, `Драйвер для Xerox DC252 пробный` |
| **Xerox 6204 / Wide Format** | `Xerox 6204/` (4 МБ; + в Драйвера на принтер 428 МБ), `Xerox_Wide_Format_with_FreeFlow_Accxes_Print_Drivers_15_0_5_SIGNED/` (1 077 файлов), `Xerox 6204.zip`, `01 Программы.../Xerox 6204.zip` (23 МБ) |
| **Kyocera** | `GX_4.4.3004_KM-1635-2035.zip` (КМ-1635/2035), `km1635Win2KXP/`, `ScannerTASKalfa...0_2200_v1.5.zip` |
| **Canon** | `Драйвера Canon Lide 110/` (сканер), `mpnx_4_0-win-4_03-ea23_2.exe` (также в `P7760_PS_x64_Driver`) |
| **Другие** | `KelvenBox/` (распакованная сборка `KelvenBox.part1-4.rar`, `KelvenBox.exe`), `AntipampersProf_2.0.6_Setup.exe`, `Boxster_Drivers_v1.1.5.zip`, `P7760_PS_x64_Driver/`, `DRIVER 500 PLUS/`, `Arcus 29 + driver + ini/`, `SPUA_1541/` (`printhelp.exe`) |
| **ПО для печати** | `18. Printhelp/` (`printhelp.exe`), `Print CD` (утилиты печати на дисках), `EasyPhotoPrint` |

---

## 4. Прочие драйверы

| Драйвер | Папка / файлы |
|---|---|
| **Универсальные драйверпаки** | `02. ДрайверПаки/` (2 083 файла, 44.1 ГБ): `SamDrivers/` (распакованная сборка + `02. Установить после alcohol120 SamDrivers_15.6.10_Full.iso` — 11.3 ГБ), `02. SDI_RUS/` (Snappy Driver Installer, `DP_*.bin` пакеты), `SamDrivers_15.6.10_Full.iso` |
| **USB-COM (CH341 / PL2303)** | `Эмулятор USB_pl2303_usb_driver`, `CorelLaser/driver/` (`driver.zip`, `CorelLaser201302.zip`, `SETUP.EXE`) |
| **Сканеры штрих-кода** | `Cino_USB_VCOM_64_3.01.05.rar`, `Cino_USB_VCOM_64_3.0.1.5.exe`, `Драйвер_VCOM.zip`, `Устаовка Штрх считывателя Атол`, `ScanOPOS.exe` |
| **1C-оборудование** | `1CBarCode_8.0.16.4.exe`, `CEL_2.0.6.14_setup1c.zip` |
| **Лазерный гравер** | `CorelLaser/` (31 файл, 33.7 МБ, ПО+драйвер CH341) |
| **Прочее** | `Mimo-UniDll_v4.zip`, `EasyPrintModule`, `P7760_PS_x64_Driver` (RevoUninstaller в комплекте), `Xerox 6204 MailBox Skan` |

---

## 5. Операционные системы и образы

| Образ | Объём | Где |
|---|---|---|
| `ru-en_win7_sp1_ie11+_x86-x64_18in1_activated.iso` (Win 7 SP1 18in1, активированная) | 4.5 ГБ | `Win 7 устанавливаем/Win7.SP1.x86-x64.Rus-Eng.18in1.IE11+.Activated/` |
| `Win 8.1 Enter (x64) Update 3 (Delete MetroStroy) RU-EN-UK 29.6.15 by Bella Edition.iso` | 3.1 ГБ | `Win 7 устанавливаем/` **и** `Windows 10 x64 Lite .../` (дубликат) |
| `ru_windows_10_enterprise_2016_ltsb_x86_dvd_9058173.iso` / `..._x64_dvd_9057886.iso` (Win 10 Enterprise 2016 LTSB x86/x64, RU) | 5.1 ГБ суммарно | `Windows 10 Enterprise 2016 LTSB ...` |
| `Win10-x64-Lite-1709(16299.125)-for-SSD-v4_xlx.iso` | 2.6 ГБ | `Windows 10 x64 Lite 1709 (16299.125) for SSD v4 xlx/` |
| `WinPE-2017m_xlx.iso` | 183 МБ | там же |

Инструменты установки ОС: `rufus-3.17.exe`, `rufus-3.22.exe`, `WindowsLoader*` (активатор), `KMS Tools Portable`.

---

## 6. Активаторы, кряки, ключи

> Отдельно от дистрибутивов, т.к. потенциально содержат вредоносный код и не входят в лицензионный парк.

| Пакет                         | Файлы                                                                                                                                                                                                                                                                                                                                                  |
| ----------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **KMS-активаторы**            | `KMS/` (KMSAuto Lite Portable v1.2.5, v1.3.4; KMSAuto Net 2015/2016; `kmsautonet.zip`), `Activators/Activators.rar`, `AAct Portable 4.2.5.rar`, `AAct v3.8.5 Portable`, `MSAct Plus v1.0.6.zip`, `KMSAuto Net 2014 v1.2.3` (в папке Office 2010), `KMS Tools Portable 15.12.2017.7z` (в Win 10 Lite), `W10 Digital Activation Program v1.3.2 Portable` |
| **Windows Loader**            | `WindowsLoader.rar/.zip`, `WindowsLoaderСборка 7601.rar`, `windows_loader_v2_2_2 паполь winbit.rar`, `windows-loader-v2.2 Сборка 7601.zip` (в `Win 7 устанавливаем`)                                                                                                                                                                                   |
| **Кряки к пакетам**           | `Activators/`, папки `Crack/` (CorelDRAW, Tweak-SSD, Defraggler, Movavi, KOMPAS `! Crack !`, uTorrentPro), `readmecd_cs2tda_and_keygen` (Photoshop CS2), `Keygen` (UltraISO, ACDSee, Adobe Acrobat), `patch_BBB` (Xilisoft), `Crack.exe`/`Crack2.rar` (Xilisoft MKV)                                                                                   |
| **Сброс активации Kaspersky** | `KRT.sfx.exe`, `Kaspersky Reset Trial.sfx.exe`                                                                                                                                                                                                                                                                                                         |
| **Прочее**                    | `Crack2.rar`, `Microsoft Office 2019 Pro_@SoftFULL.rar` (содержит активатор), `kmsauto-lite-1-3-4-portable.zip`, `KMS.rar` (2 копии)                                                                                                                                                                                                                   |

---

## 7. Дубликаты

### 7.1. Полные дубликаты файлов (одинаковое имя и размер в разных местах)

| Файл | Размер | Расположение 1 | Расположение 2 |
|---|---|---|---|
| `HP_P2050.iso` | 657 МБ | `Драйвера на принтер/Образ Принтерп 2055/` | `Образ Принтерп 2055/` (копия папки целиком) |
| `Образ Epson L805.iso` | 276 МБ | `01 Программы.../` (корень) | `Драйвера на принтер/` |
| `Epson L800.iso` | 261 МБ | `01 Программы.../` (корень) | — (разные сборки: `Драйвера на принтер/Epson L800.iso`?) — проверено: только одна, см. 7.2 |
| `Win 8.1 Enter ... Bella Edition.iso` | 3.1 ГБ | `Win 7 устанавливаем/` | `Windows 10 x64 Lite 1709.../` |
| `spyderprint 890710-937300-211232.rar` | 176 МБ | `Драйвера на принтер/Коллибровка цвета/` | `Коллибровка цвета/` |
| `Фото на документы Профи 8.15 RePack by KaktusTV.exe` | 32 МБ | `01 Программы.../` (корень) | `21. Фото на документы Профи 6.0/` |
| `kms.rar` | 8.7/9.1 МБ | `08. Microsoft Office 2010 with SP2 VL .../KMS.rar` | `KMS/KMS.rar` (разные размеры — разные сборки) |
| `rufus-3.17.exe` | 1.4 МБ | `Win 7 устанавливаем/` | `Windows 10 x64 Lite .../` |
| `x64-M24-Mini_PCL.zip` | 79 КБ | `Драйвера на принтер/дрова Xerox WorkCentre m24/` | `.../Xerox Workcentre 24/` (внутри той же папки) |
| `mpnx_4_0-win-4_03-ea23_2.exe` | 49.8 МБ | `Драйвера на принтер/P7760_PS_x64_Driver/` | `Драйвера на принтер/Драйвера Canon Lide 110/` |
| `printhelp.exe` | 2.7 МБ (2 шт.) / 2.3 МБ | `18. Printhelp/` | `Драйвера на принтер/`, `Драйвера на принтер/SPUA_1541/` |
| `XFAInstaller.exe` | 741 КБ | `Xerox_Wide_Format...SIGNED/` | `Драйвера на принтер/Xerox 6204/` (2 копии) |
| `XFAPrintUIx64.exe` | 45 КБ | `Xerox_Wide_Format...SIGNED/` | `Драйвера на принтер/Xerox 6204/` (2 копии) |
| `utorrent.exe` / `uTorrent.exe` | разные | `uTorrent/`, `SamDrivers/soft/`, `Win10 Lite/` | 4–5 разных версий по каталогам |
| `setup.exe` / `setup.msi` | разные | в распакованных сборках (AutoCAD, KOMPAS, EPSON, ABBYY, Office, 1C) | до 68 копий `setup.exe` по сборкам |
| `kelvenbox.exe` | 22.9 МБ | `KelvenBox/KelvenBox1-4/` | 5 копий в одной папке |
| `spyderprint/setup/setup.exe` | 187 МБ | `Коллибровка цвета/spyderprint/setup/` | `Коллибровка цвета/spyderprint/spyderprint/setup/` |
| `sptdinst-v186-x86/x64.exe` | 0.5 МБ | `Alcohol120_retail_2.0.2.5830/RePack/SPTD 1.86/` | `.../Standalone/SPTD 1.86/` |
| `Alcohol 120% v2.0.3 ...` (папка) | 10.8 МБ | `01. Установка Виртуального привода/` | `Windows 10 x64 Lite .../` (папка целиком) |
| `EdgeBlock` (папка) | 1.9 МБ | `29. Win 10 tools/` | `Windows 10 x64 Lite .../` (папка целиком) |
| `Activators` (папка) | разные | `Activators/` | `Windows 10 x64 Lite .../Activators/` |

### 7.2. Дубликаты по имени внутри дистрибутивов (служебные, не для удаления)

- `instmsia.exe` / `instmsiw.exe` — 3 копии (Adobe CS2, ACDSee, EPSON 1410).
- `vcredist_x86.exe` / `vcredist_x64.exe` / `vc_redist.*` — по 3–5 копий (AutoCAD 2020, AdobeReader, 1C, EPSON, Win 10 Lite).
- `msxml6_x64.msi` — ABBYY 14 и AutoCAD 2020.
- `ndp47/ndp48-x86-x64-allos-enu.exe` — KOMPAS v20 (x32/x64), v21, v22, Win 10 tools (3 копии).
- `jun2010_d3d*.cab`, `windows*.kb3118401/4019990*.msu`, `WindowsInstaller-KB893803-x86.exe` — AutoCAD 2020 и 10. Autodesk_AutoCAD (10+ копий).
- `eval.msi`, `helpinstaller.msi`, `nlsdl.amd64/x86.exe`, `senddmp.exe`, `uninstalltool.exe`, `setup.exe` — внутренние копии AutoCAD 2020 (en/ru, x64).
- `epusbun.exe`, `refresh.exe`, `oeminf.exe`, `use_g.cab`, `setup.exe` — EPSON 1410 (по языковым каталогам, 3–10 копий).
- `kmpct2km.exe`, `kmstmnet.exe`, `kmstmnw.exe`, `kmstmvmt.exe` — Kyocera KM-1635/2035 (32/64-бит).
- `i320.cab`, `i640.cab` — Office 2019 (Data/ и Experiment/).
- `pspdfsaver5af.exe`, `prninstaller.exe`, `trigrammsinstaller.exe`, `networklicenseserver.exe` — ABBYY 14 (Module64/Module86, дубли лицензирования).
- `materials.exe` — KOMPAS v20/v21.
- `tweak-ssd.exe` — x86/x64/корень папки Crack.
- `usbguard.exe` — USB Disk Security (3 версии).
- `kmsauto.exe` — KMSAuto 1.2.5 (в KMS/) и 1.3.2 (в Win 10 Lite).
- `win 10 tweaker.exe` — пустой файл (0 байт) в `29. Win 10 tools/` и рабочий (548 КБ) в Win 10 Lite.
- Служебные: `settings.reg`, `тихая установка (RUS).cmd`, `unc23.webp`, `bg.webp`, `LICENSE.txt`, файлы `node_modules/` (SamDrivers catalog) — 2–3 копии.

### 7.3. Целые папки, повторяющиеся в двух местах

- `Xerox 6204` — корень `01 Программы.../` (4 МБ) и `Драйвера на принтер/` (428 МБ, расширенная).
- `Коллибровка цвета` — `Драйвера на принтер/` (753 МБ) и корень `01 Программы.../` (370 МБ) — пересечение `spyderprint`.
- `Образ Принтерп 2055` — `Драйвера на принтер/` и корень `01 Программы.../` — идентичны (657 МБ).
- `Alcohol 120% v2.0.3 ...` — `01. Установка Виртуального привода/` и `Windows 10 x64 Lite .../`.
- `Crack` — в Tweak-SSD, Defraggler, Movavi (разные пакеты, просто одинаковое имя папки).

---

## Примечания

- Файлы `kdc` (8 323 шт.) и `dll` (5 357 шт.) — базы обновлений Kaspersky и служебные библиотеки сборок; не являются отдельными дистрибутивами.
- `System Volume Information/` — служебный каталог (теневые копии), не ПО.
- `packer.ps1` в корне — скрипт упаковки (вероятно, сборки дистрибутивов).
- Крупные кандидаты на освобождение места при разборе: дубликаты ISO (см. 7.1, ~4.6 ГБ), `новая музыка с рекламой.mp3` (1.4 ГБ), распакованные сборки при наличии исходных архивов.