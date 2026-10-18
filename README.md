# OSINT-Tools-Ukraine
<img src="https://upload.wikimedia.org/wikipedia/commons/4/49/Flag_of_Ukraine.svg" alt="Ukraine_FLAG"/>
A list of OSINT resources and tools that may be useful to you when conducting investigations related to Ukraine. Most of the resources and tools have versions in Ukrainian, some also in English. Since 24 February 2022, martial law has restricted several registers: the Public Cadastral Map was switched off for the general public, and the Unified Register of Court Decisions and some other state sites are not reachable from many foreign IP addresses. The Unified State Register of legal entities (EDR), including beneficial owners, remains searchable for free and is published daily as open data; real estate rights information is available as a paid online extract through Diia with Ukrainian e-ID. Asset declarations of public officials were reopened in 2023. Names may appear in Ukrainian, Russian, and transliterated forms, so search all variants.

**Last Updated:** 2026-10-14

## Contributions
Feel free to join this project — [OSINT For Countries V2.0](https://github.com/Provereno-Media/OSINT-for-countries-V2.0)

## Table of contents:
 - [Open Data portals](#open-data-portals)
 - [Legal Entities](#legal-entities)
 - [Cadastral and other Maps](#maps)
 - [Vehicles](#vehicles)
 - [People, phones, social etc.](#people)
 - [Public procurements](#public-procurement)
 - [WHOIS](#whois)

## Open Data portals
(Country Open Data, Stock Exchange, Courts)
- [data.gov.ua (Unified State Open Data Portal)](https://data.gov.ua/) — national open data portal with datasets of ministries, agencies and local authorities, including the EDR, vehicle registrations and the ship register; CKAN API. *Lang: UK, EN.*
- [State Statistics Service of Ukraine](https://stat.gov.ua/) — official statistics; publication of some indicators has been limited under martial law. *Lang: UK, EN.*
- [National Bank of Ukraine — Open Data](https://bank.gov.ua/en/open-data) — central bank statistics, exchange rates and registers of banks and non-bank financial institutions, with an API. *Lang: UK, EN.*
- [Єдиний державний реєстр судових рішень (Unified State Register of Court Decisions)](https://reyestr.court.gov.ua/) — full texts of court decisions with personal data of private persons anonymised; search by case number, court, judge or text. Often unreachable from foreign IP addresses. *Lang: UK.*
- [Судова влада — Стан розгляду справ (Judiciary — Case Status and Hearings)](https://court.gov.ua/fair/) — case status and hearing schedules of Ukrainian courts by party name or case number. *Lang: UK.*
- [Законодавство України (Verkhovna Rada Legislation Database)](https://zakon.rada.gov.ua/laws) — official database of Ukrainian legislation with consolidated texts. Often unreachable from foreign IP addresses. *Lang: UK, EN.*
- [SMIDA](https://smida.gov.ua/) — disclosure database of the National Securities and Stock Market Commission: issuers' annual and special reports, shareholders with large stakes and officers. *Lang: UK.*
- [Державний реєстр санкцій (NSDC State Register of Sanctions)](https://drs.nsdc.gov.ua/) — official register of persons and companies under Ukrainian sanctions, with grounds and decree numbers. Blocks automated access; also mirrored by [OpenSanctions](https://www.opensanctions.org/datasets/ua_nsdc_sanctions/). *Lang: UK, EN.*
- [Автоматизована система виконавчого провадження (Enforcement Proceedings System)](https://asvpweb.minjust.gov.ua/) — Ministry of Justice lookup of enforcement proceedings by the proceeding number and access code; see also the [Unified Register of Debtors](https://erb.minjust.gov.ua/). Blocks automated access. *Lang: UK.*

## Legal Entities
- [Єдиний державний реєстр — безкоштовний запит (EDR Free Search)](https://usr.minjust.gov.ua/content/free-search) — Ministry of Justice's free search of legal entities, sole traders and public associations by name or EDRPOU code: status, address, managers, founders and beneficial owners. Often unreachable from foreign IP addresses; the same data are published as a daily [open dataset](https://data.gov.ua/dataset/a1799820-195b-4982-8141-6e84f58103e7). *Lang: UK.*
- [Opendatabot](https://opendatabot.ua/en) — company and sole-trader profiles built on open registers: owners, beneficiaries, court cases, tax debts, real estate and vehicles, with monitoring. Freemium. Blocks automated access. *Lang: UK, EN.*
- [YouControl](https://youcontrol.com.ua/) — company due-diligence platform: registration history, links between people and companies, court cases, sanctions and procurement. Freemium: basic profiles free, full dossiers paid. Blocks automated access. *Lang: UK, EN.*
- [VKURSI.PRO](https://vkursi.pro/) — business-intelligence platform with company and person dossiers, link analysis and sanctions screening from more than 60 sources. Freemium. *Lang: UK.*
- [Державна податкова служба — Реєстри (Tax Service Registers)](https://cabinet.tax.gov.ua/registers) — public registers of the State Tax Service: VAT payers, single-tax payers, non-profit organisations and others. *Lang: UK.*
- [edrpou.ubki.ua](https://edrpou.ubki.ua/ua) — free company cards by EDRPOU code from the credit bureau UBKI: registration data, managers and financial indicators. *Lang: UK.*
- [North Data](https://www.northdata.com/) — North Data covers company data in Ukraine as part of its XL package, which includes comprehensive information on companies, key persons, and financials. *Lang: EN, DE, FR.*
- [Tesari First Resort](https://tesari.ai/) — Tesari is an all-source intelligence platform designed for high-stakes environments, with applications ranging from trade compliance and supply chain illumination to financial crime investigations and complex litigation. It is a paid platform that offers a Tech for Good (Community Impact) Programme for OSINT practitioners and journalists. *Lang: EN.*

## Maps
(Cadastral Maps if available, GIS etc.)
- [Інформація з Державного реєстру речових прав (Real Estate Rights Register Extract via Diia)](https://diia.gov.ua/services/informaciya-z-derzhavnogo-reyestru-rechovih-prav-na-neruhome-majno) — paid online extract on owners, encumbrances and mortgages of real estate by object or by person; Ukrainian e-ID required. *Lang: UK.*
- [Офіційний електронний портал Держгеокадастру (StateGeoCadastre e-Services)](https://e.land.gov.ua/) — electronic services of the State Land Cadastre, including extracts on land plots by cadastral number. The Public Cadastral Map has been closed to the general public since February 2022. *Lang: UK.*
- [Kadastrova Karta](https://kadastrova-karta.com/) — unofficial cadastral map of land plots with cadastral numbers, purpose and area; recency of the underlying data not verified. Premium features paid. *Lang: UK.*
- [Єдина державна електронна система у сфері будівництва (Unified Construction System)](https://e-construction.gov.ua/) — public registers and map of construction permits, notices of start of works, commissioning certificates and the parties involved. *Lang: UK.*
- [Visicom Maps](https://maps.visicom.ua/) — detailed Ukrainian map with address search and building numbers. *Lang: UK, EN.*
- [DeepStateMap](https://deepstatemap.live/en) — daily-updated map of the front line and occupied territories. *Lang: UK, EN.*

## Vehicles
### Land
- [Відомості про транспортні засоби та їх власників (Vehicle Registrations Open Data)](https://data.gov.ua/dataset/06779371-308f-42d7-895e-5a39833375f0) — Ministry of Internal Affairs dataset of registration operations by year: make, model, year, colour, plate, operation type and date, service centre, owner type (person or company) and territory code; no owner names. *Lang: UK.*
- [MTSBU — Перевірка поліса (Motor Insurance Policy Check)](https://policy.mtsbu.ua/) — Motor Transport Insurance Bureau's check of compulsory motor insurance by plate, VIN or policy number: insurer, validity and vehicle. *Lang: UK.*
- [baza-gai.com.ua](https://baza-gai.com.ua/) — search by plate or VIN in registration data from the Ministry of Internal Affairs' open data: make, model, registration history and photos. Freemium. *Lang: UK.*

### Maritime
- [Державний судновий реєстр України (State Ship Register)](https://data.gov.ua/dataset/d3aee671-a29b-494e-877f-29f78a3e4581) — quarterly spreadsheet of sea-going and inland vessels registered in Ukraine, published by the Maritime and Inland Water Transport Service. *Lang: UK.*
- [VesselFinder](https://www.vesselfinder.com/) — live AIS vessel map with vessel and port database. Freemium: live map free; some features paid. *Lang: EN.*
- [Equasis](https://www.equasis.org/) — international database of ship and shipping-company safety information: IMO number, flag, owner, manager, inspections. Free registration required. *Lang: EN.*

### Aviation
- [Державний реєстр цивільних повітряних суден (Civil Aircraft Register)](https://data.gov.ua/dataset/08a647a0-7829-46ab-aa50-5afb7146a7a8) — State Aviation Service dataset of UR- registered aircraft; last updated in 2019. *Lang: UK.*
- [ADS-B Exchange](https://globe.adsbexchange.com/) — live and historical aircraft tracking without filtering of blocked aircraft; search by registration, ICAO hex or callsign. *Lang: EN.*

## People
(Names, Addresses, Yellow Pages, White Pages etc.)
- [Реєстр декларацій (NACP Asset Declarations Register)](https://public.nazk.gov.ua/) — asset declarations of officials, MPs, judges, prosecutors and civil servants: income, real estate, vehicles, companies, family members. *Lang: UK.*
- [Реєстр корупціонерів (Register of Corruption Offenders)](https://corruptinfo.nazk.gov.ua/) — NACP register of persons who committed corruption or corruption-related offences. *Lang: UK.*
- [Верховна Рада України (Verkhovna Rada)](https://www.rada.gov.ua/) — parliament's website with MPs' profiles, factions, votes and bills. *Lang: UK, EN.*
- [Центральна виборча комісія (Central Election Commission)](https://www.cvk.gov.ua/) — official election results and candidate lists, including candidates' biographies. *Lang: UK, EN.*
- [Chesno](https://www.chesno.org/politician/) — civic movement's database of politicians: biographies, declarations, voting and party switches. *Lang: UK.*
- [Єдиний реєстр адвокатів України (Unified Register of Advocates)](https://erau.unba.org.ua/) — National Bar Association's register of lawyers with certificate data and place of practice. *Lang: UK.*
- [Розшук МВС (Ministry of Internal Affairs — Wanted Persons)](https://wanted.mvs.gov.ua/) — search of persons wanted by the police, missing persons and stolen vehicles. Blocks automated access. *Lang: UK.*
- [PRA.IN.UA](https://pra.in.ua/en) — genealogy community with indexes of metric books, census lists and archival sources. *Lang: UK, EN.*
- Try [OSINT Industries](https://app.osint.industries) and don't forget about the [Digital Profiler's Toolkit](https://github.com/paulpogoda/Digital-Profiler-s-Toolkit)

## Public procurement
- [Prozorro](https://prozorro.gov.ua/uk) — national e-procurement system: all public tenders, bids, contracts and amendments with documents. *Lang: UK, EN.*
- [Prozorro BI](https://bi.prozorro.org/) — public analytics module of Prozorro: dashboards and exports by buyer, supplier and item. *Lang: UK, EN.*
- [Dozorro](https://dozorro.org/) — Transparency International Ukraine's procurement monitoring portal: risk indicators, reviews and complaints. Blocks automated access. *Lang: UK.*
- [Clarity Project](https://clarity-project.info/) — procurement and company analytics: tenders by buyer and supplier, links between participants and public finances. Freemium. Blocks automated access. *Lang: UK, EN.*
- [Є-Data / Spending (Public Finance Transparency Portal)](https://spending.gov.ua/) — Treasury transactions, contracts and reports of public fund managers. Blocks automated access. *Lang: UK.*
- [Prozorro.Sale](https://prozorro.sale/) — electronic auctions of state and municipal property, privatisation, leases and bad bank assets. Blocks automated access. *Lang: UK, EN.*
- [DREAM](https://dream.gov.ua/en) — Digital Restoration Ecosystem for Accountable Management: reconstruction projects, funding and contractors. *Lang: UK, EN.*

## WHOIS
- [Hostmaster — WHOIS](https://www.hostmaster.ua/whois/) — official .UA registry WHOIS and RDAP lookup of domain registration details. *Lang: UK, EN.*
- [IANA — .ua Delegation Record](https://www.iana.org/domains/root/db/ua.html) — official delegation data for .ua: registry operator, contacts and name servers. *Lang: EN.*
- [RIPE Database Query](https://apps.db.ripe.net/db-web-ui/query) — RIPE NCC WHOIS for IP ranges and AS numbers allocated to Ukrainian networks. *Lang: EN.*
- [ViewDNS.info](https://viewdns.info/) — reverse IP, reverse WHOIS, IP history, DNS records and subdomain discovery. *Lang: EN.*

---

## Contributing

To contribute to this repository:
1. Verify all links are working and accessible
2. Provide accurate descriptions of database contents
3. Follow the 7-category structure
4. Include official government sources when available
5. Submit pull requests with detailed change descriptions

## Legal Disclaimer

This repository is for educational and legitimate investigative purposes only. Users are responsible for:
- Complying with all applicable laws and regulations
- Respecting terms of service for all databases and tools
- Using information ethically and responsibly
- Obtaining proper authorization when required

The information provided is for informational purposes only and should not be considered legal advice.

---

**Repository maintained by the [OSINT-for-Countries-V2.0 community](https://github.com/Provereno-Media/OSINT-for-countries-V2.0)**
