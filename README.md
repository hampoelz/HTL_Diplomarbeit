# HTL_Diplomarbeit
🎓 Plattformübergreifender WebApp-Wrapper mit benutzerdefiniertem NodeJS-Backend

![Banner](./Branding/rendered/Banner.png)

## Ausgangslage:

Mit dem Framework ElectronJS werden Programme für Desktop-Systeme mit Webtechnologien (Frontend) und NodeJS (Backend) entwickelt. Mobile-Systeme werden nicht unterstützt. Durch das CapacitorJS-Framework werden Mobile-Apps mit Webtechnologien entwickelt, jedoch fehlt dort das NodeJS-Backend. Somit können keine Apps mit Webtechnologien und NodeJS vollständig plattformübergreifend entwickelt werden.

## Projektteam (Arbeitsaufwand)

| **Name** | **Individuelle Themenstellung** | **Klasse** | **Arbeitsaufwand** |
|------|-----------------------------|--------|----------------|
| Rene Hampölz (Hauptverantwortlich) | "Capacitor-NodeJS" und "Capacitor-BrowserView" | 5BHET | 180 Stunden |
| Noah Quinz | "Universal PWA-Wrapper" | 5BHET | 180 Stunden |

## Untersuchungsanliegen der individuellen Themenstellungen

1. **Capacitor-NodeJS**
   * Integration des Projekts "nodejs-mobile" in das CapacitorJS-Framework (um ein NodeJS-Backend in Android und iOS zu ermöglichen)
   * Integration in das Projekt "capacitor-community/electron" (um das selbe NodeJS-Backend in Windows, macOS und Linux zu verwenden)
   * Erstellung einer API zwischen Frontend und Backend (angelehnt an der ElectronJS ipc API)
2. **Capacitor-BrowserView**
   * ​​Portierung der BrowserView-Funktion von ElektronJS zu CapacitorJS (für iOS und Android)
   * Integration in das Projekt "capacitor-community/electron" (für Windows, macOS und Linux)
3. **Universal PWA-Wrapper**
   * ​​Entwicklung eines Grundgerüsts mit ElectronJS, CapacitorJS und der NodeJS- und BrowserView-Erweiterung
   * Integration weiterer Funktionen (UX, Updater, etc.)

## Zielsetzung

Web-Entwickler sollen ohne Erfahrung über native Apps, aus ihrer WebApp bzw. Website, eine platformübergreifende App erstellen können. Um die WebApp mit zusätzlichen Funktionen zu erweitern, steht ein NodeJS-Backend zur Verfügung. Die App enthält Out-Of-The-Box eine minimale, aber moderne Benutzeroberfläche, Browser-Cache Funktionalitäten, sowie einen einfach zu konfigurierenden Updater.

## Geplantes Ergebnis der individuellen Themenstellungen:

1. **Capacitor-NodeJS**: Das CapacitorJS-Framework wird um ein NodeJS-Backend erweitert.
2. **Capacitor-BrowserView**: Die BrowserView-Funktion von ElektronJS wird zu CapacitorJS portiert.
3. **Universal PWA-Wrapper**: Mithilfe der beiden CapacitorJS-Erweiterungen und der Integration in die ElectronJS-Erweiterung für das CapacitorJS-Framework, wird schließlich der universelle WebApp Wrapper realisiert.

Meilensteine:

* [x] [Capacitor-NodeJS] Android Integration
* [ ] [Capacitor-NodeJS] iOS Integration
* [x] [Capacitor-NodeJS] ElectronJS Integration
* [ ] [Capacitor-BrowserView] iOS Portierung
* [ ] [Capacitor-BrowserView] Android Portierung
* [ ] [Capacitor-BrowserView] ElectronJS Integration
* [ ] [Universal PWA-Wrapper] Grundgerüst (mit ElectronJS, CapacitorJS und der NodeJS- und BrowserView-Erweiterung)
* [ ] [Universal PWA-Wrapper] Benutzeroberfläche
* [ ] [Universal PWA-Wrapper] Updater funktionalität
