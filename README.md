# Gruppenrichtlinien-22KW06
Samples zum Gruppenrichtlinien Kurs der ppedv AG

KursBlatt:

Agenda:
- Grundlagen ActiveDirectory
  - FSMO Rollen (Betriebsmaster)
  - Container
  - Organisationseinheiten und Ihre Strukturierung
- Cloudbasierten Alternativen
  - MDM   
- Installation AD
  - Grundlagen ADMX
    - Central Store
    - Local Store
- GPO:
  - Grundlagen
    - Vererbung
    - Richtlinien / Einstellungen
  - Dateierweiterung
  - Netzlaufwerk
  - StartLayout
  - Bitlocker
- Filterung:
    - Delegierung / Sicherheitsfilterung
    - WMI Filterung
      ```sql
      #ProductType 1 = Client | 2 = DC | 3 = normaler Server
      SELECT ProductType FROM Win32_OperatingSystem WHERE ProductType = 1
      ```