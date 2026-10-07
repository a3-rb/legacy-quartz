# Сверка ПО из `Work.Drive` с публичным репозиторием Chocolatey

Сверка проведена по каждому наименованию из `stage-3/softwareinfo.md` с каталогом
публичного репозитория Chocolatey (community.chocolatey.org) — снимок 2026-08-20.

**Условные обозначения:**
- ✅ **Есть пакет** — в репозитории существует пакет с тем же или близким именем (приводится `ID` и последняя версия).
- 🔄 **Аналог** — пакета с таким именем нет, но есть равноценный аналог.
- ❌ **Нет** — пакета нет и функционального аналога в Chocolatey не найдено.

---

## 1. Бесплатное ПО

| ПО из инвентаря                         | Пакет / версия                                                                                      | Статус                                      |
| --------------------------------------- | --------------------------------------------------------------------------------------------------- | ------------------------------------------- |
| **7-Zip**                               | `7zip` 26.2.0, `7zip.install`, `7zip.portable`, `7zip.commandline`, `7zip-zstd`                     | ✅                                           |
| **AnyDesk**                             | `anydesk` 9.7.15, `anydesk.install`, `anydesk.portable`                                             | ✅                                           |
| **TeamViewer**                          | `teamviewer` 15.80.6, `teamviewer.portable`, `teamviewer-qs`, `teamviewer.host`                     | ✅                                           |
| **Open Office**                         | `OpenOffice` 4.1.16                                                                                 | ✅                                           |
| **PDF24 Creator**                       | `pdf24` 11.30.1                                                                                     | ✅                                           |
| **Adobe Reader**                        | `adobereader` 2026.1.21662, `adobereader-update`                                                    | ✅                                           |
| **AIMP**                                | `aimp` 5.40.2716                                                                                    | ✅                                           |
| **PotPlayer / Daum PotPlayer**          | `potplayer` 26.8.19                                                                                 | ✅                                           |
| **uTorrent**                            | `uTorrent` 3.5.5.45271, `utorrent-webui`                                                            | ✅                                           |
| **BitTorrent**                          | `bittorrent` — нет; аналоги: `qbittorrent` 5.2.3, `transmission` 4.1.3, `tixati`, `deluge`, `aria2` | 🔄                                          |
| **Yandex (браузер)**                    | `Yandex-browser` 24.10.4.927, `yandexdisk` (диск)                                                   | ✅                                           |
| **Яндекс.Музыка**                       | нет пакета; аналог — встроена в браузер / веб-версия                                                | 🔄                                          |
| **Lightshot / скриншоты**               | `lightshot` 5.5.0.720221014, `lightshot.install`; аналог `greenshot` 1.3.315                        | ✅                                           |
| **Speedtest (Ookla)**                   | `speedtest-by-ookla` 1.15.200.1, `speedtest`; аналог `librespeed-cli`                               | ✅                                           |
| **Syncthing**                           | `syncthing` 2.1.3, `syncthingtray`, `synctrayzor`                                                   | ✅                                           |
| **Win 10 Tweaker / OOSU10 / EdgeBlock** | `shutup10` 3.4.1124 (O&O ShutUp10 — тот же класс «отключение слежки/настроек Win10»)                | 🔄 (для tweaker/edgeblock аналог частичный) |
| **WinRAR**                              | `winrar` 7.23.0                                                                                     | ✅                                           |
| **Kaspersky Free**                      | `kvrt` (утилита удаления), `kav`, `kis`, `kss` — коммерческие; отдельного пакета KFA нет            | 🔄                                          |

---

## 2. Лицензионное ПО

### 2.1. Офис и редакторы

| ПО из инвентаря                    | Пакет / версия                                                                                                                                 | Статус |
| ---------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- | ------ |
| **Microsoft Office 2010 SP2**      | нет пакета (не распространяется); аналог — `office365-2016-deployment-tool`, `office2019proplus`; свободные аналоги `libreoffice`/`onlyoffice` | 🔄     |
| **Microsoft Office 2016**          | `office365-2016-deployment-tool` (средство развёртывания); свободные аналоги `libreoffice` 5.4.4, `onlyoffice` 9.4.0                           | 🔄     |
| **Microsoft Office 2019 Pro Plus** | `office2019proplus` 2019.1808.0.20260812 (официальный пакет в Chocolatey)                                                                      | ✅      |
| **1C Предприятие**                 | `1cfresh-client` 8.5.1.989 (клиент 1С:Фреш); полноценного пакета платформы нет                                                                 | 🔄     |
| **1CBarCode / штрих-коды**         | `1c-barcode-scanner` 8.0.8.4, `1c-barcode-printing`, `atol-dto` 10.8.0.0, `barcode-to-pc-server`, `zbar` 0.10                                  | ✅      |
| **Total Commander**                | `TotalCommander` 11.58.0, `totalcmd`, `totalcommanderpowerpack`; аналог `doublecmd` 1.2.8                                                      | ✅      |
| **ABBYY FineReader**               | нет пакета (коммерческий OCR); свободный аналог OCR — `tesseract` 5.5.3.20260724 (+языковые пакеты)                                            | 🔄     |
| **Adobe Acrobat Pro DC**           | нет пакета Pro (платный); `adobereader` — только Reader; аналог просмотра — `sumatrapdf` 3.6.1, `PDFXChangeViewer`                             | 🔄     |
| **Adobe Photoshop**                | нет пакета; аналоги: `gimp` 3.2.4, `photogimp`, `paint.net` 5.1.12, `krita` 5.3.3                                                              | 🔄     |
| **Adobe Illustrator**              | нет пакета; аналог — `InkScape` 1.4.4                                                                                                          | 🔄     |
| **CorelDRAW**                      | нет пакета; аналог — `InkScape`, `gimp` (векторная графика), `libreoffice-draw`                                                                | 🔄     |
| **PROMT**                          | нет пакета; аналог в репозитории отсутствует                                                                                                   | ❌      |
| **Фото на документы Профи**        | нет пакета; аналог — утилиты печати фото отсутствуют в Chocolatey                                                                              | ❌      |
| **Adobe Illustrator (ISO-сборки)** | см. Illustrator — пакета нет, только аналог InkScape                                                                                           | 🔄     |

### 2.2. САПР и инженерное ПО

| ПО из инвентаря | Пакет / версия | Статус |
|---|---|---|
| **AutoCAD 2010/2020/2025** | `autocad` 2027.25.1.60, `autocadlt` 2027.26.0.60 (дистрибутив по лицензии Autodesk); просмотрщики `dwgtrueview` 2027.26.0.60, `designreview` | ✅ |
| **КОМПАС-3D v20–v24** | нет пакета (коммерческое, не в репозитории); свободные аналоги 3D-САПР — `freecad` 1.1.3.1, `openscad` | 🔄 |
| **Autodesk_AutoCAD_Architecture_2014** | нет отдельного пакета; аналог — `autocad` / `autocadlt` | 🔄 |

### 2.3. Мультимедиа и утилиты

| ПО из инвентаря                         | Пакет / версия                                                                                                                     | Статус |
| --------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------- | ------ |
| **Alcohol 120%**                        | нет пакета 120%; есть бесплатная младшая версия `alcohol52-free` 2.0.3.9326; аналог монтирования образов — `iso7z`                 | 🔄     |
| **UltraISO**                            | `ultraiso` 9.7.6.3829; аналог — `imgburn` 2.5.8.20210426, `iso7z`                                                                  | ✅      |
| **Nero**                                | нет пакета; аналоги записи дисков — `cdburnerxp` 4.5.8.712800, `imgburn`                                                           | 🔄     |
| **ACDSee**                              | нет пакета; аналог — `IrfanView` 4.75.0 (+`irfanviewplugins`), `XnView`                                                            | 🔄     |
| **Movavi Video Editor/Converter**       | `movavivideoeditorplus` 22.0.0, `movavivideoconverter` 22.1.0, `movaviscreenrecorder` 22.0.0, `movavislideshowmaker`               | ✅      |
| **Xilisoft DVD Ripper / MKV Converter** | нет пакета; аналоги конвертации/риппинга — `handbrake` 1.11.2, `avidemux`                                                          | 🔄     |
| **Bandicam**                            | нет пакета; аналог записи экрана — `obs-studio` 32.1.2, `fraps`                                                                    | 🔄     |
| **Acronis Disk Director**               | нет пакета (коммерческий); `acronis-drive-monitor` — только мониторинг дисков; аналог управления разделами в репозитории не найден | 🔄     |
| **CCleaner Professional**               | `ccleaner` 6.41.11567, `ccleaner.portable` (в репозитории бесплатная версия)                                                       | ✅      |
| **Defraggler**                          | `defraggler` 2.22.995.20200817                                                                                                     | ✅      |
| **Tweak-SSD**                           | нет пакета; аналог — средства оптимизации отсутствуют в Chocolatey                                                                 | ❌      |
| **Ace Utilities**                       | нет пакета; аналог — `ccenhancer` (расширение CCleaner)                                                                            | 🔄     |
| **USB Disk Security**                   | нет пакета; аналог ограничения запуска — `simple-software-restriction-policy`                                                      | 🔄     |
| **MailboxScan**                         | нет пакета; `ost2` — частичный аналог (конвертация OST/PST)                                                                        | 🔄     |
| **Datacolor Spyder (калибровка)**       | нет пакета (коммерч.); свободный аналог калибровки — `displaycal` 3.8.9.3, `dispcalgui`                                            | 🔄     |
| **RevoUninstaller** (в составе P7760)   | `revouninstallerpro` 3.1.1.20141201                                                                                                | ✅      |
| **Xerox MailBox Scan / WFSS**           | нет пакета; аналог — ПО сканирования Xerox не в репозитории                                                                        | ❌      |

---

## 3. Драйверы принтеров

| ПО из инвентаря | Пакет / версия | Статус |
|---|---|---|
| **Epson (1410, L800/L805, T50, R290 и др.)** | отдельных модельных драйверов нет; есть `epson-perfection-v33-scanner` 3.9.2.2 (сканер), `epson-iprojection` (проектор) | 🔄 |
| **HP (P2050, DJ430, T1100)** | нет модельных пакетов; универсальные: `hp-universal-print-driver-pcl` 8.2.0.26778, `hp-universal-print-driver-ps` 8.2.0.26778 | 🔄 |
| **Xerox (6204, DC252, WorkCentre m24, Wide Format)** | `xeroxupd` 5.1076.4 (Xerox Universal Print Driver) | ✅ (общий драйвер) |
| **Kyocera (KM-1635/2035, TASKalfa)** | нет пакета; универсальный драйвер в репозитории не найден | ❌ |
| **Canon (Lide 110)** | нет пакета; драйверы Canon в Chocolatey отсутствуют | ❌ |
| **Printhelp / PrintCD / EasyPhotoPrint** | нет пакетов (утилиты производителей) | ❌ |

---

## 4. Прочие драйверы

| ПО из инвентаря | Пакет / версия | Статус |
|---|---|---|
| **SamDrivers / SDI_RUS (драйверпаки)** | `snappy-driver-installer` 1.0.539.20170422, `snappy-driver-installer-origin`, `sdio` 2.0.2.884; альтернатива — `driverpacksolution` 17.2017.2.22 | ✅ |
| **CH341 / PL2303 (USB-COM)** | отдельных пакетов нет; есть схожий класс — `hsm-usb-serial-driver` 3.5.9 (USB-serial для Рутокен) | 🔄 |
| **Cino / VCOM / АТОЛ (сканеры ШК)** | `atol-dto` 10.8.0.0 (драйверы АТОЛ), `1c-barcode-scanner` 8.0.8.4, `barcode-to-pc-server` | ✅ |
| **1CBarCode** | `1c-barcode-scanner`, `1c-barcode-printing`, `zbar` 0.10 | ✅ |
| **CorelLaser** | нет пакета (специализированное ПО гравера) | ❌ |
| **Epson adjustment program (сервис)** | нет пакета (сервисное ПО, не в репозитории) | ❌ |
| **Драйверы чековых принтеров (Штрих)** | `atol-dto` — драйверы торгового оборудования АТОЛ | 🔄 |

---

## 5. Операционные системы и образы

| Образ / инструмент | Пакет / версия | Статус |
|---|---|---|
| **Win 7 / 8.1 / 10 образы (ISO)** | образы ОС не распространяются через Chocolatey (лицензирование) | ❌ |
| **Rufus** | `rufus` 4.15.0, `rufus.install`, `rufus.portable` | ✅ |
| **WinPE / запись на USB** | `winsetupfromusb` 1.10.0, `autobootdisk`, `hbcd` | 🔄 |
| **WindowsLoader (активатор)** | нет пакета (и официально недопустимо); аналогов активации в репозитории нет | ❌ |

---

## 6. Активаторы и кряки

| Инструмент | Пакет | Статус |
|---|---|---|
| **KMSAuto / KMS / AAct / MSAct / W10 Digital Activation** | нет пакетов (недопустимое ПО, в репозитории отсутствует) | ❌ |
| **Windows Loader / активация Windows** | нет пакетов | ❌ |
| **Кряки (Crack/Keygen)** | нет пакетов | ❌ |

> Активаторы и кряки в Chocolatey отсутствуют намеренно — репозиторий распространяет только легально перераспространяемое ПО.

---

## 7. Компоненты и рантаймы

| Компонент из инвентаря | Пакет / версия | Статус |
|---|---|---|
| **Visual C++ Redistributable (2010–2017)** | `vcredist-all` 1.0.1, `vcredist2005`, `vcredist2008`, `vcredist2010`, `vcredist2012`, `vcredist2013`, `vcredist2015`, `vcredist2017`, `vcredist140`, `MSVisualCplusplus2012-redist`, `MSVisualCplusplus2013-redist` | ✅ |
| **.NET Framework 4.7/4.8** | `netfx-4.7.1`, `netfx-4.7.2` 4.7.2.0, `netfx-4.6.2`, `dotnet4.7`, `dotnet4.7.1` | ✅ |
| **DirectX** | `directx` 9.29.1974.20210222, `directx-sdk` | ✅ |
| **Шрифты** | `dejavufonts` 2.37, `RobotoFonts`, `fonts-poppins`, `nerd-fonts-*` (JetBrainsMono 3.5.0 и др.), `chocolatey-font-helpers.extension` | ✅ |

---

## 8. Сводка

| Статус       | Кол-во | Примеры                                                                                                                                                                                                                                                                                     |
| ------------ | ------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ✅ Пакет есть | ~30    | 7zip, anydesk, teamviewer, pdf24, winrar, autocad, ultraiso, ccleaner, defraggler, rufus, potplayer, aimp, uTorrent, Yandex-browser, Office 2019, TotalCommander, Movavi*, драйверпаки                                                                                                      |
| 🔄 Аналог    | ~25    | BitTorrent→qbittorrent, Photoshop→gimp, Illustrator/CorelDRAW→InkScape, ABBYY→tesseract, Acrobat→sumatrapdf, Alcohol 120%→alcohol52-free, Nero→cdburnerxp, ACDSee→IrfanView, Bandicam→obs-studio, HP/Epson/Xerox→универсальные драйверы, Office→LibreOffice/OnlyOffice, Acronis→аналога нет |
| ❌ Нет        | ~10    | PROMT, Фото на документы Профи, Kyocera, Canon, CorelLaser, Epson adjustment, Tweak-SSD, активаторы/кряки, ISO-образы ОС, MailboxScan                                                                                                                                                       |

**Вывод для интеграции в stage-3:** для большей части бесплатного ПО и ряда коммерческих продуктов
(Office 2019, AutoCAD, UltraISO, CCleaner, Defraggler, Total Commander, Movavi, драйверпаки SDI/DriverPack)
уже существуют готовые пакеты Chocolatey, которые можно использовать при сборке пакетного репозитория (BaGet)
либо при развёртывании по парку. Для коммерческого ПО без официальных пакетов (Photoshop, Illustrator,
CorelDRAW, KOMPAS, ABBYY, Acronis) актуальны свободные аналоги, перечисленные выше.