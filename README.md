# Appenzell Ausserrhoden: law history in git

The law of the canton of Appenzell Ausserrhoden (Kanton Appenzell Ausserrhoden, Switzerland) as a git history: one file per article, one commit per amending act on the day it took effect, and the amending act as the commit's author. `git blame` names the act behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `ch-ar/`. The federal law is in [lexifina/switzerland-law](https://github.com/lexifina/switzerland-law).

The text is in German, the canton's official language, exactly as the canton publishes it.

## What this repository holds

231 acts with 620 versions so far: the cantonal constitution, the cantonal laws (Gesetze) in force and 155 Verordnungen and Reglemente in force, in the order of the systematic collection, added in parts. Other decrees and decisions, intercantonal agreements and repealed acts are not included yet.

| Folder | Act | Versions | History |
| --- | --- | ---: | --- |
| `111-1/` | Verfassung des Kantons Appenzell A.Rh. (bGS 111.1) | 9 | as enacted, then each consolidated version: 1 May 1996 to 1 January 2027 |
| `111-3/` | Gesetz über den Eidschwur (bGS 111.3) | 1 | one version (the oldest available), 28 September 1997 |
| `121-1/` | Gesetz über das Landrecht und das Gemeindebürgerrecht (bGS 121.1) | 2 | oldest version available, then each consolidated version: 1 September 2005 to 1 January 2013 |
| `122-1/` | Registergesetz (bGS 122.1) | 1 | as enacted, 1 November 2019 |
| `131-12/` | Gesetz über die politischen Rechte (bGS 131.12) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 June 2019 |
| `133-1-informationsgesetz/` | Gesetz über Information und Akteneinsicht (bGS 133.1) | 2 | as enacted, then each consolidated version: 1 May 1996 to 1 June 2019 |
| `141-1-krg/` | Kantonsratsgesetz (bGS 141.1) | 1 | as enacted, 1 June 2019 |
| `142-3-egovg/` | Gesetz über eGovernment und Informatik (bGS 142.3) | 3 | as enacted, then each consolidated version: 1 January 2013 to 14 June 2019 |
| `142-12-organisationsgesetz-org/` | Regierungs- und Verwaltungsorganisationsgesetz (bGS 142.12) | 3 | as enacted, then each consolidated version: 1 June 2005 to 1 January 2016 |
| `142-21-pg/` | Personalgesetz (bGS 142.21) | 8 | oldest version available, then each consolidated version: 1 January 2008 to 1 July 2023 |
| `142-22-pkg/` | Gesetz über die Pensionskasse AR (bGS 142.22) | 3 | as enacted, then each consolidated version: 1 January 2014 to 1 January 2026 |
| `143-1-vrpg/` | Gesetz über die Verwaltungsrechtspflege (bGS 143.1) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2020 |
| `145-31/` | Justizgesetz (bGS 145.31) | 5 | as enacted, then each consolidated version: 1 January 2011 to 1 June 2019 |
| `145-52-anwaltsgesetz/` | Gesetz über die Ausübung des Anwaltsberufes (bGS 145.52) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2022 |
| `146-1-datenschutzgesetz/` | Gesetz über den Datenschutz (bGS 146.1) | 4 | oldest version available, then each consolidated version: 1 June 2008 to 1 January 2025 |
| `151-11/` | Gemeindegesetz (bGS 151.11) | 4 | oldest version available, then each consolidated version: 1 January 2011 to 1 November 2019 |
| `211-1-eg-zum-zgb/` | Gesetz über die Einführung des Schweizerischen Zivilgesetzbuches (bGS 211.1) | 7 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2026 |
| `211-2-beurkg/` | Beurkundungsgesetz (bGS 211.2) | 1 | as enacted, 1 February 2010 |
| `213-121-eg-zum-bewg/` | Gesetz über die Einführung des Bundesgesetzes vom 16. Dezember 1983 über den Erwerb von Grundstücken durch Personen im Ausland (bGS 213.121) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2016 |
| `233-2/` | Gesetz über die Gebühren in Verwaltungssachen (bGS 233.2) | 1 | one version (the oldest available), 1 June 2005 |
| `241-1/` | Gesetz über die Einführung des Bundesgesetzes vom 11. April 1889 über Schuldbetreibung und Konkurs (bGS 241.1) | 1 | one version (the oldest available), 1 January 2011 |
| `311/` | Gesetz über das kantonale Strafrecht (bGS 311) | 1 | one version (the oldest available), 1 January 2011 |
| `341-1-jvg/` | Gesetz über den Justizvollzug (bGS 341.1) | 1 | as enacted, 1 January 2015 |
| `412-00-volksschulgesetz-vsg/` | Gesetz über die Volksschule (bGS 412.00) | 1 | as enacted, 1 August 2023 |
| `413-1-mhg/` | Gesetz über die Mittel- und Hochschulen (bGS 413.1) | 2 | as enacted, then each consolidated version: 1 January 2015 to 1 August 2023 |
| `414-11-eg-zum-bbg/` | Einführungsgesetz zum Bundesgesetz über die Berufsbildung (bGS 414.11) | 4 | as enacted, then each consolidated version: 1 January 2008 to 1 August 2023 |
| `415-21-stipendiengesetz/` | Gesetz über Ausbildungsbeiträge (bGS 415.21) | 2 | oldest version available, then each consolidated version: 1 January 2008 to 1 January 2018 |
| `415-31-kinderbetreuungsgesetz-kibeg/` | Gesetz zur Förderung der familienergänzenden Kinderbetreuung (bGS 415.31) | 1 | as enacted, 1 June 2023 |
| `420-1/` | Kulturförderungsgesetz (bGS 420.1) | 1 | as enacted, 1 August 2006 |
| `421-10/` | Archivgesetz (bGS 421.10) | 1 | as enacted, 1 January 2011 |
| `422-16/` | Gesetz über die Errichtung der Stiftung Pro Appenzell (bGS 422.16) | 1 | as enacted, 28 April 1963 |
| `511-1/` | Bevölkerungsschutzgesetz (bGS 511.1) | 2 | as enacted, then each consolidated version: 1 January 2005 to 1 January 2016 |
| `511-2/` | Zivilschutzgesetz (bGS 511.2) | 3 | as enacted, then each consolidated version: 1 January 2005 to 30 September 2016 |
| `521-1/` | Polizeigesetz (bGS 521.1) | 5 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2016 |
| `525-1-hug/` | Hundegesetz (bGS 525.1) | 2 | oldest version available, then each consolidated version: 25 April 1982 to 1 January 2016 |
| `526-2-jagdgesetz/` | Gesetz über Jagd, Wild- und Vogelschutz (bGS 526.2) | 4 | oldest version available, then each consolidated version: 1 January 2007 to 1 June 2023 |
| `612-0-fhg/` | Finanzhaushaltsgesetz (bGS 612.0) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 June 2019 |
| `612-2/` | Gesetz über die Staatsstrassenrechnung und die leistungsabhängige Schwerverkehrsabgabe (bGS 612.2) | 3 | oldest version available, then each consolidated version: 1 January 2008 to 1 January 2016 |
| `613-1-finanzausgleichsgesetz/` | Gesetz über den Finanzausgleich zwischen dem Kanton und den Gemeinden (bGS 613.1) | 1 | one version (the oldest available), 9 June 2008 |
| `621-11/` | Steuergesetz (bGS 621.11) | 11 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2025 |
| `621-12-abrg/` | Gesetz über die steuerbegünstigten Arbeitsbeschaffungsreserven (bGS 621.12) | 2 | as enacted, then each consolidated version: 1 January 1989 to 1 January 2016 |
| `711-1-enteignungsgesetz/` | Gesetz über die Zwangsabtretung (bGS 711.1) | 1 | one version (the oldest available), 1 January 1995 |
| `712-1/` | Gesetz über das öffentliche Beschaffungswesen (bGS 712.1) | 1 | one version (the oldest available), 1 January 2011 |
| `721-1-baugesetz/` | Gesetz über die Raumplanung und das Baurecht (bGS 721.1) | 7 | oldest version available, then each consolidated version: 1 January 2011 to 1 October 2025 |
| `723-1-kgeoig/` | Kantonales Geoinformationsgesetz (bGS 723.1) | 1 | as enacted, 1 November 2012 |
| `731-11-strg/` | Strassengesetz (bGS 731.11) | 3 | as enacted, then each consolidated version: 1 February 2010 to 1 June 2023 |
| `741-1-wasserbaugesetz-wbaug/` | Gesetz über den Wasserbau und die Gewässernutzung (bGS 741.1) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 October 2025 |
| `750-1-keng/` | Energiegesetz (bGS 750.1) | 6 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2023 |
| `751-211/` | Gesetz über die Errichtung eines kantonalen Elektrizitätswerkes (bGS 751.211) | 1 | as enacted, 27 April 1913 |
| `760-1/` | Gesetz über die Förderung des öffentlichen Verkehrs (bGS 760.1) | 4 | as enacted, then each consolidated version: 1 January 1992 to 1 June 2023 |
| `761-11-eg-svg/` | Einführungsgesetz zum Bundesgesetz vom 19. Dezember 1958 über den Strassenverkehr (bGS 761.11) | 3 | oldest version available, then each consolidated version: 1 January 2008 to 1 January 2016 |
| `811-1/` | Gesundheitsgesetz (bGS 811.1) | 10 | oldest version available, then each consolidated version: 1 January 2011 to 14 January 2022 |
| `812-11-spitalverbundgesetz-svarg/` | Gesetz über den Spitalverbund Appenzell Ausserrhoden (bGS 812.11) | 4 | as enacted, then each consolidated version: 1 January 2012 to 1 January 2019 |
| `812-12/` | Gesetz über die Beteiligung des Kantons Appenzell A.Rh. am Ostschweizerischen Säuglings- und Kinderspital in St. Gallen (bGS 812.12) | 1 | as enacted, 29 April 1962 |
| `813-21/` | Einführungsgesetz zum Bundesgesetz über die Betäubungsmittel (bGS 813.21) | 2 | oldest version available, then each consolidated version: 1 January 2008 to 1 January 2016 |
| `814-0-umwelt-und-gewasserschutzgesetz-ugsg/` | Gesetz über die Einführung der Bundesgesetze über den Umweltschutz und über den Schutz der Gewässer (bGS 814.0) | 5 | oldest version available, then each consolidated version: 1 January 2009 to 1 October 2025 |
| `822-31/` | Gesetz über den Sonntagsverkauf (bGS 822.31) | 2 | as enacted, then each consolidated version: 1 January 2012 to 1 January 2016 |
| `822-32/` | Gesetz über den Werktags-Ladenschluss (bGS 822.32) | 2 | as enacted, then each consolidated version: 25 April 1948 to 1 January 2012 |
| `822-41-eg-zum-famzg/` | Einführungsgesetz zum Bundesgesetz über die Familienzulagen (bGS 822.41) | 4 | as enacted, then each consolidated version: 1 January 2009 to 1 April 2020 |
| `831-1-eg-ahvg-ivg/` | Einführungsgesetz zu den Bundesgesetzen über die Alters- und Hinterlassenenversicherung und über die Invalidenversicherung (bGS 831.1) | 2 | oldest version available, then each consolidated version: 1 January 2008 to 1 June 2016 |
| `832-31/` | Gesetz über Ergänzungsleistungen zur Alters-, Hinterlassenen- und Invalidenversicherung (bGS 832.31) | 1 | as enacted, 1 January 2008 |
| `833-11-eg-zum-kuvg/` | Gesetz über die Einführung des Bundesgesetzes vom 13. Juni 1911 über die Kranken- und Unfallversicherung (KUVG) (bGS 833.11) | 1 | one version (the oldest available), 28 April 1996 |
| `833-14-eg-zum-kvg/` | Gesetz über die Einführung des Bundesgesetzes über die Krankenversicherung (bGS 833.14) | 4 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2017 |
| `833-15-pfg/` | Gesetz über die Pflegefinanzierung (bGS 833.15) | 1 | as enacted, 1 January 2017 |
| `841-1/` | Gesetz über Massnahmen zur Förderung des Wohnungsbaues (bGS 841.1) | 1 | as enacted, 6 December 1973 |
| `851-1-sozialhilfegesetz-shg/` | Gesetz über die öffentliche Sozialhilfe (bGS 851.1) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2013 |
| `852-6-behindertenfinanzierungsgesetz-befig/` | Gesetz zur Finanzierung von Leistungsangeboten für Menschen mit Behinderung (bGS 852.6) | 3 | as enacted, then each consolidated version: 1 January 2008 to 14 January 2022 |
| `861-0-feuerschutzgesetz/` | Gesetz über den Feuerschutz (bGS 861.0) | 1 | one version (the oldest available), 1 January 2011 |
| `862-1-assekuranzgesetz/` | Gesetz über die Gebäude- und Grundstückversicherung (bGS 862.1) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2020 |
| `911-1/` | Gesetz über die Wirtschaftsförderung (bGS 911.1) | 2 | as enacted, then each consolidated version: 1 January 2006 to 1 January 2013 |
| `920-1/` | Gesetz über die Landwirtschaft (bGS 920.1) | 2 | oldest version available, then each consolidated version: 1 January 2008 to 1 January 2016 |
| `931-1-kantonales-waldgesetz/` | Gesetz über den Wald (bGS 931.1) | 4 | as enacted, then each consolidated version: 1 January 1997 to 1 October 2025 |
| `955-11/` | Gesetz über das Gastgewerbe (bGS 955.11) | 1 | as enacted, 1 May 1999 |
| `955-21-tg/` | Tourismusgesetz (bGS 955.21) | 3 | oldest version available, then each consolidated version: 1 January 2004 to 1 January 2017 |
| `955-22/` | Gesetz über die Entlastung von den Tourismusabgaben 2020 und 2021 (bGS 955.22) | 1 | as enacted, 1 January 2021 |
| `955-31-kgs/` | Kantonales Geldspielgesetz (bGS 955.31) | 3 | oldest version available, then each consolidated version: 1 January 1982 to 14 January 2022 |
| `122-11/` | Verordnung zum Registergesetz (bGS 122.11) | 1 | as enacted, 1 November 2019 |
| `122-21/` | Verordnung zur Bundesgesetzgebung über die Ausländerinnen und Ausländer (bGS 122.21) | 4 | as enacted, then each consolidated version: 1 January 2008 to 30 September 2016 |
| `122-22/` | Verordnung über die Gebühren im Ausländerrecht (bGS 122.22) | 3 | as enacted, then each consolidated version: 15 January 2008 to 1 January 2022 |
| `122-23/` | Verordnung über die Gebühren bei der Zuteilung ausländischer Arbeitskräfte (bGS 122.23) | 2 | as enacted, then each consolidated version: 1 February 1995 to 30 September 2016 |
| `122-24-kr-asylvo/` | Verordnung des Kantonsrates zum Asylwesen (bGS 122.24) | 4 | as enacted, then each consolidated version: 1 January 2008 to 30 September 2016 |
| `122-241-rr-asylvo/` | Verordnung des Regierungsrates zum Asylwesen (bGS 122.241) | 4 | as enacted, then each consolidated version: 1 January 2008 to 30 September 2016 |
| `123-1-ausweisverordnung/` | Verordnung über die Ausstellung von Ausweisen für Schweizer Staatsangehörige und von Reisedokumenten für Ausländer (bGS 123.1) | 5 | as enacted, then each consolidated version: 1 March 2010 to 1 January 2027 |
| `131-13/` | Verordnung über die eidpflichtigen Behördenmitglieder der Gemeinden (bGS 131.13) | 1 | as enacted, 1 June 2019 |
| `142-13/` | Verordnung über die Besoldung und die berufliche Vorsorge der Mitglieder des Regierungsrates (bGS 142.13) | 3 | oldest version available, then each consolidated version: 1 January 2008 to 1 June 2019 |
| `142-121-organisationsverordnung-orv/` | Verordnung zum Regierungs- und Verwaltungsorganisationsgesetz (bGS 142.121) | 11 | oldest version available, then each consolidated version: 1 January 2011 to 1 June 2026 |
| `142-211-bvo/` | Besoldungsverordnung (bGS 142.211) | 8 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2026 |
| `142-211-1-reis/` | Reglement über die Entschädigung von Inkonvenienzen, Spesen, Pikettdienst und ausserordentliche Arbeitszeit (bGS 142.211.1) | 6 | oldest version available, then each consolidated version: 1 January 2010 to 1 January 2026 |
| `142-211-5-ov-abo-verordnung-ovav/` | Verordnung über vergünstigte Abonnemente im öffentlichen Verkehr für kantonale Angestellte (bGS 142.211.5) | 1 | as enacted, 1 July 2026 |
| `142-212-pgv/` | Personalverordnung (bGS 142.212) | 9 | as enacted, then each consolidated version: 1 January 2008 to 1 January 2026 |
| `143-11/` | Vorläufige Verordnung zur Gewährleistung des Rechtswegs in Staatshaftungsverfahren (bGS 143.11) | 1 | as enacted, 15 February 2019 |
| `145-12/` | Besoldungsverordnung für die gerichtlichen Organe (bGS 145.12) | 5 | as enacted, then each consolidated version: 1 January 2011 to 1 June 2023 |
| `145-53/` | Verordnung über den Anwaltstarif (bGS 145.53) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2019 |
| `145-521/` | Verordnung über die Anwaltsprüfung (bGS 145.521) | 1 | one version (the oldest available), 1 July 2005 |
| `211-211-beurkv/` | Beurkundungsverordnung (bGS 211.211) | 2 | as enacted, then each consolidated version: 1 February 2010 to 1 January 2016 |
| `212-01-vsta/` | Verordnung über die Stiftungsaufsicht (bGS 212.01) | 2 | as enacted, then each consolidated version: 1 October 2003 to 1 March 2025 |
| `212-11/` | Verordnung über das Zivilstandswesen (bGS 212.11) | 6 | oldest version available, then each consolidated version: 1 January 2011 to 1 September 2017 |
| `212-43-tarif-kesr/` | Verordnung über die Verfahrenskosten, Entschädigungen und Spesen im Kindes- und Erwachsenenschutzrecht (bGS 212.43) | 2 | as enacted, then each consolidated version: 1 January 2013 to 1 January 2019 |
| `212-331-kavi/` | Kantonale Ausführungsverordnung zur Inkassohilfe (bGS 212.331) | 1 | as enacted, 26 April 2022 |
| `213-113/` | Verordnung zum Bundesgesetz über das bäuerliche Bodenrecht (bGS 213.113) | 2 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2017 |
| `213-310-kgbv/` | Kantonale Grundbuchverordnung (bGS 213.310) | 4 | as enacted, then each consolidated version: 23 December 1996 to 1 July 2025 |
| `213-311/` | Verordnung über die Einführung des Grundbuches in den Gemeinden (bGS 213.311) | 1 | one version (the oldest available), 15 February 1963 |
| `222-11/` | Vorläufige Verordnung zum Mietrecht (bGS 222.11) | 1 | as enacted, 15 January 2016 |
| `222-31/` | Verordnung zum Bundesgesetz vom 10. Dezember 1941 über die Revision des XX. Titels des Obligationenrechts (Die Bürgschaft) (bGS 222.31) | 1 | one version (the oldest available), 1 January 1957 |
| `222-215/` | Verordnung zum Bundesgesetz vom 28. September 1956 über die Allgemeinverbindlicherklärung von Gesamtarbeitsverträgen (bGS 222.215) | 3 | oldest version available, then each consolidated version: 1 January 1995 to 30 September 2016 |
| `222-216/` | Verordnung über den Normalarbeitsvertrag für Betriebs- und Hausangestellte in der Landwirtschaft (bGS 222.216) | 1 | as enacted, 1 January 2009 |
| `222-218/` | Verordnung über den Normalarbeitsvertrag für hauswirtschaftliche Arbeitnehmer und Arbeitnehmerinnen (bGS 222.218) | 1 | as enacted, 1 January 2026 |
| `223-1/` | Verordnung über das Handelsregister (bGS 223.1) | 2 | oldest version available, then each consolidated version: 1 January 2010 to 1 January 2016 |
| `233-3-gebuhrenordnung/` | Verordnung über die Rechtskosten und Entschädigungen in der Zivil- und Strafrechtspflege (bGS 233.3) | 3 | oldest version available, then each consolidated version: 1 January 2004 to 1 December 2017 |
| `233-21-kgv/` | Kanzleigebührenverordnung (bGS 233.21) | 1 | as enacted, 1 January 2003 |
| `244-1/` | Verordnung über die Aufhebung der Sicherungsbeschlagnahme von Luftfahrzeugen (bGS 244.1) | 1 | as enacted, 13 February 1951 |
| `323-1-kobv/` | Kantonale Ordnungsbussenverordnung (bGS 323.1) | 3 | as enacted, then each consolidated version: 1 May 2005 to 1 January 2022 |
| `331-1/` | Verordnung über das Strafregister (bGS 331.1) | 3 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2022 |
| `341-11/` | Verordnung über den Straf- und Massnahmenvollzug und die Bewährungshilfe (bGS 341.11) | 4 | as enacted, then each consolidated version: 1 January 2015 to 1 January 2022 |
| `341-12/` | Verordnung über die Vollzugseinrichtungen (bGS 341.12) | 2 | as enacted, then each consolidated version: 1 January 2015 to 30 September 2016 |
| `412-01-volksschulverordnung-vsv/` | Verordnung über die Volksschule (bGS 412.01) | 1 | as enacted, 1 August 2023 |
| `412-02-blv/` | Besoldungsverordnung für die Lehrpersonen der Volksschule (bGS 412.02) | 2 | as enacted, then each consolidated version: 1 August 2023 to 1 January 2024 |
| `412-03-schulleitungsverordnung-slv/` | Verordnung über die Schulleitung in der Volksschule (bGS 412.03) | 1 | as enacted, 1 August 2023 |
| `413-11-mhv/` | Verordnung über die Mittel- und Hochschulen (bGS 413.11) | 2 | as enacted, then each consolidated version: 1 January 2015 to 1 August 2023 |
| `414-111-kant-bbv/` | Verordnung zum Einführungsgesetz zum Bundesgesetz über die Berufsbildung (bGS 414.111) | 3 | as enacted, then each consolidated version: 1 January 2008 to 1 January 2016 |
| `414-112/` | Verordnung über die Entschädigung von Mitwirkenden bei betrieblichen Qualifikationsverfahren und bei Betriebsexpertisen in der Berufsbildung (bGS 414.112) | 1 | as enacted, 1 April 2009 |
| `415-211-stipendienverordnung/` | Verordnung über Ausbildungsbeiträge (bGS 415.211) | 2 | oldest version available, then each consolidated version: 1 October 2009 to 13 February 2018 |
| `415-311-kinderbetreuungsverordnung-kibev/` | Verordnung zur Förderung der familienergänzenden Kinderbetreuung (bGS 415.311) | 1 | as enacted, 1 June 2023 |
| `420-11/` | Kulturförderungsverordnung (bGS 420.11) | 4 | oldest version available, then each consolidated version: 27 November 2007 to 1 January 2020 |
| `420-21/` | Verordnung über den Oskar und Dora Meier-Strub-Fonds (bGS 420.21) | 1 | as enacted, 1 September 2017 |
| `421-15/` | Verordnung über die Kantonsbibliothek (bGS 421.15) | 2 | as enacted, then each consolidated version: 1 June 2009 to 1 January 2016 |
| `421-111/` | Benützungsreglement für das Staatsarchiv (bGS 421.111) | 1 | as enacted, 1 January 2011 |
| `422-2/` | Tierschutzverordnung (bGS 422.2) | 2 | oldest version available, then each consolidated version: 18 November 1996 to 1 January 2016 |
| `422-111/` | Verordnung über den Naturschutz (bGS 422.111) | 1 | one version (the oldest available), 6 May 1991 |
| `422-161/` | Verordnung über die Verwaltung der Stiftung Pro Appenzell (bGS 422.161) | 3 | oldest version available, then each consolidated version: 1 July 2003 to 1 June 2023 |
| `511-11/` | Verordnung zum Bevölkerungsschutzgesetz (bGS 511.11) | 1 | as enacted, 1 January 2005 |
| `511-21/` | Verordnung zum Zivilschutzgesetz (bGS 511.21) | 3 | as enacted, then each consolidated version: 1 January 2005 to 30 September 2016 |
| `512-111/` | Verordnung über die kantonale Militärverwaltung (bGS 512.111) | 2 | as enacted, then each consolidated version: 2 December 2009 to 1 January 2016 |
| `521-11-polizeiverordnung-polv/` | Verordnung zum Polizeigesetz (bGS 521.11) | 3 | oldest version available, then each consolidated version: 14 December 2010 to 1 July 2021 |
| `521-12/` | Verordnung über die elektronische Bearbeitung von polizeilichen Datensammlungen (bGS 521.12) | 1 | as enacted, 1 January 2003 |
| `521-13-gebuhrentarif-der-kantonspolizei/` | Verordnung über die Gebühren der Kantonspolizei (bGS 521.13) | 4 | oldest version available, then each consolidated version: 1 January 2005 to 1 September 2017 |
| `521-14/` | Verordnung über die privaten polizeiähnlichen Tätigkeiten (bGS 521.14) | 1 | as enacted, 1 July 2004 |
| `524-2/` | Verordnung über den Vollzug der Bundesgesetzgebung über Waffen, Waffenzubehör und Munition (bGS 524.2) | 3 | as enacted, then each consolidated version: 1 January 1999 to 1 January 2020 |
| `525-11-huv/` | Hundeverordnung (bGS 525.11) | 4 | oldest version available, then each consolidated version: 29 May 2001 to 1 January 2025 |
| `526-21-jagdverordnung/` | Verordnung zum Gesetz über Jagd, Wild- und Vogelschutz (bGS 526.21) | 6 | oldest version available, then each consolidated version: 18 October 2005 to 1 April 2024 |
| `527-2-fischereiverordnung/` | Verordnung über die Fischerei (bGS 527.2) | 2 | oldest version available, then each consolidated version: 1 January 2003 to 30 September 2016 |
| `612-3-sportfondsverordnung/` | Verordnung über die Verwendung der kantonalen Sportfondsgelder (bGS 612.3) | 3 | oldest version available, then each consolidated version: 16 November 2004 to 1 January 2016 |
| `621-21-gsv/` | Verordnung über die amtlichen Grundstückschätzungen (bGS 621.21) | 3 | as enacted, then each consolidated version: 1 January 2011 to 1 January 2023 |
| `621-111-steuerverordnung/` | Verordnung zum Steuergesetz (bGS 621.111) | 12 | oldest version available, then each consolidated version: 1 January 2010 to 1 January 2024 |
| `625-11/` | Verordnung über die Durchführung des Bundesgesetzes über die direkte Bundessteuer (DBG) (bGS 625.11) | 2 | oldest version available, then each consolidated version: 19 June 2007 to 1 January 2016 |
| `625-21/` | Verordnung zum Bundesgesetz vom 13. Oktober 1965 über die Verrechnungssteuer (bGS 625.21) | 3 | oldest version available, then each consolidated version: 1 January 2004 to 1 January 2026 |
| `625-31/` | Verordnung zum Bundesgesetz über die Wehrpflichtersatzabgabe (bGS 625.31) | 6 | as enacted, then each consolidated version: 6 April 2004 to 1 July 2025 |
| `626-33/` | Verordnung über die Anrechnung ausländischer Quellensteuern (bGS 626.33) | 1 | as enacted, 1 January 2020 |
| `711-2/` | Verordnung zum Bundesgesetz über die Enteignung (bGS 711.2) | 1 | as enacted, 24 January 2006 |
| `712-11/` | Verordnung über das öffentliche Beschaffungswesen (bGS 712.11) | 2 | as enacted, then each consolidated version: 1 January 2005 to 1 January 2016 |
| `721-11-bauv/` | Bauverordnung (bGS 721.11) | 9 | as enacted, then each consolidated version: 1 January 2004 to 1 January 2026 |
| `721-12-beitragsverordnung/` | Verordnung über Beiträge an Denkmalpflege-, Natur- und Heimatschutzmassnahmen (bGS 721.12) | 3 | oldest version available, then each consolidated version: 9 September 1996 to 30 September 2016 |
| `721-121/` | Verordnung über die anrechenbaren Kosten bei Denkmalpflege- und Heimatschutzbeiträgen (bGS 721.121) | 1 | one version (the oldest available), 24 August 2004 |
| `723-101-kgeoiv/` | Kantonale Geoinformationsverordnung (bGS 723.101) | 6 | as enacted, then each consolidated version: 1 November 2012 to 1 January 2026 |
| `723-104-korebkv/` | Kantonale Verordnung über den Kataster der öffentlich-rechtlichen Eigentumsbeschränkungen (bGS 723.104) | 1 | as enacted, 1 January 2021 |
| `723-105-kvav/` | Kantonale Verordnung über die amtliche Vermessung (bGS 723.105) | 3 | as enacted, then each consolidated version: 1 November 2012 to 30 September 2016 |
| `731-31/` | Verordnung über die Einführung des Bundesgesetzes vom 4. Oktober 1985 über Fuss- und Wanderwege (bGS 731.31) | 3 | oldest version available, then each consolidated version: 1 January 2008 to 30 September 2016 |
| `731-111-strv/` | Strassenverordnung (bGS 731.111) | 4 | as enacted, then each consolidated version: 1 February 2010 to 30 September 2016 |
| `731-113/` | Verordnung über das Parkieren auf Staatsarealen (bGS 731.113) | 3 | as enacted, then each consolidated version: 1 January 1997 to 1 January 2019 |
| `731-114/` | Verordnung über die Beitragsleistung an die Anpassung oder Aufhebung von Bahnübergängen (bGS 731.114) | 2 | as enacted, then each consolidated version: 1 January 2008 to 1 January 2016 |
| `741-11-wbauv/` | Wasserbauverordnung (bGS 741.11) | 3 | as enacted, then each consolidated version: 1 January 2007 to 1 October 2025 |
| `742-1-perimeterverordnung/` | Verordnung über die Grundeigentümerbeiträge bei der Korrektion oder Verbauung öffentlicher Gewässer (bGS 742.1) | 2 | oldest version available, then each consolidated version: 1 January 2007 to 1 January 2016 |
| `750-11-energieverordnung-kenv/` | Verordnung zum Energiegesetz (bGS 750.11) | 5 | oldest version available, then each consolidated version: 1 January 2008 to 1 January 2023 |
| `751-3/` | Vorläufige Verordnung über die Einführung des Bundesgesetzes über die Stromversorgung (bGS 751.3) | 2 | as enacted, then each consolidated version: 1 January 2009 to 1 January 2016 |
| `760-11-v-gov/` | Verordnung zum Gesetz über die Förderung des öffentlichen Verkehrs (bGS 760.11) | 2 | as enacted, then each consolidated version: 1 January 1992 to 1 July 2014 |
| `760-12/` | Einführungsverordnung zur schweizerischen Automobilkonzessionsverordnung (AKV) (bGS 760.12) | 2 | as enacted, then each consolidated version: 19 May 1998 to 1 January 2016 |
| `761-111/` | Verordnung zum Einführungsgesetz vom 24. April 1983 zum Bundesgesetz vom 19. Dezember 1958 über den Strassenverkehr (EG SVG) (bGS 761.111) | 5 | oldest version available, then each consolidated version: 1 August 1998 to 12 June 2017 |
| `761-113/` | Verordnung über die Versteigerung von Kontrollschildern (bGS 761.113) | 2 | as enacted, then each consolidated version: 1 March 2016 to 1 February 2018 |
| `761-114/` | Verordnung über die Organisation des Strassenverkehrsamtes (bGS 761.114) | 1 | as enacted, 1 September 2025 |
| `763-11/` | Verordnung über die Luftseilbahnen mit Personenbeförderung ohne Bundeskonzession und die Skilifte (bGS 763.11) | 2 | oldest version available, then each consolidated version: 1 January 2003 to 1 January 2016 |
| `765-1-krlv/` | Kantonale Rohrleitungsverordnung (bGS 765.1) | 1 | as enacted, 1 April 2020 |
| `766-1-schiffsfuhrerausweisverordnung-sfav/` | Verordnung über Schiffsführerausweise (bGS 766.1) | 2 | as enacted, then each consolidated version: 1 April 2025 to 13 February 2026 |
| `811-11/` | Verordnung zum Gesundheitsgesetz (bGS 811.11) | 8 | oldest version available, then each consolidated version: 1 May 2010 to 1 November 2026 |
| `811-11-1/` | Prüfungsreglement für Heilpraktikerinnen und Heilpraktiker (bGS 811.11.1) | 2 | oldest version available, then each consolidated version: 1 May 2009 to 1 January 2016 |
| `811-12-baderverordnung/` | Verordnung über die öffentlichen Bäder (bGS 811.12) | 2 | as enacted, then each consolidated version: 1 March 2003 to 1 January 2016 |
| `811-13/` | Verordnung über die Gesundheitsfachpersonen (bGS 811.13) | 4 | as enacted, then each consolidated version: 1 January 2008 to 1 June 2019 |
| `811-14-heimverordnung/` | Verordnung über die Heimaufsicht (bGS 811.14) | 4 | as enacted, then each consolidated version: 1 January 2008 to 30 September 2016 |
| `811-16-forderverordnung-pflegeausbildung-fopa/` | Verordnung über die Förderung der Pflegeausbildung (bGS 811.16) | 1 | as enacted, 1 October 2024 |
| `811-112/` | Verordnung über die Gesundheitsvorsorge in Schulen und Heimen für Kinder und Jugendliche (bGS 811.112) | 3 | oldest version available, then each consolidated version: 8 March 1994 to 1 April 2021 |
| `811-116-hebammen-verordnung/` | Verordnung über den Beruf der Hebamme (bGS 811.116) | 1 | as enacted, 8 March 1994 |
| `812-111-3/` | Verordnung über die Entschädigung der Mitglieder des Verwaltungsrates des Spitalverbundes Appenzell Ausserrhoden (bGS 812.111.3) | 2 | as enacted, then each consolidated version: 1 January 2014 to 1 June 2023 |
| `813-22/` | Vorläufige Verordnung über die Einführung des Bundesgesetzes über den Schutz vor gefährlichen Stoffen und Zubereitungen (bGS 813.22) | 2 | as enacted, then each consolidated version: 1 October 2005 to 1 January 2016 |
| `814-01-umwelt-und-gewasserschutzverordnung-ugsv/` | Verordnung zum Gesetz über die Einführung der Bundesgesetze über den Umweltschutz und über den Schutz der Gewässer (bGS 814.01) | 3 | oldest version available, then each consolidated version: 1 October 2010 to 1 February 2023 |
| `814-01-2-schadenwehrverordnung/` | Verordnung über die Schadenwehr (bGS 814.01.2) | 1 | one version (the oldest available), 1 October 2005 |
| `814-01-3-gov/` | Verordnung über den Umgang mit invasiven gebietsfremden Organismen (bGS 814.01.3) | 1 | as enacted, 1 September 2010 |
| `815-11-lkv/` | Verordnung über die Lebensmittelkontrolle (bGS 815.11) | 2 | as enacted, then each consolidated version: 9 September 1996 to 1 January 2016 |
| `815-13-fkv/` | Verordnung über die Fleischkontrolle (bGS 815.13) | 2 | as enacted, then each consolidated version: 18 November 1996 to 1 January 2016 |
| `816-11/` | Verordnung zum Bundesgesetz vom 13. Juni 1928 betreffend Massnahmen gegen die Tuberkulose (bGS 816.11) | 4 | as enacted, then each consolidated version: 25 October 1973 to 1 January 2019 |
| `816-31/` | Verordnung über das Bestattungswesen (bGS 816.31) | 2 | oldest version available, then each consolidated version: 1 January 2008 to 1 January 2016 |
| `822-11/` | Verordnung zum Bundesgesetz vom 13. März 1964 über die Arbeit in Industrie, Gewerbe und Handel (Arbeitsgesetz) (bGS 822.11) | 2 | oldest version available, then each consolidated version: 1 January 1995 to 1 January 2016 |
| `822-21/` | Einführungsverordnung zum Bundesgesetz vom 20. März 1981 über die Heimarbeit (bGS 822.21) | 2 | oldest version available, then each consolidated version: 1 January 1995 to 1 January 2016 |
| `822-61/` | Verordnung über Massnahmen gegen die Schwarzarbeit (bGS 822.61) | 2 | as enacted, then each consolidated version: 1 January 2008 to 1 January 2016 |
| `822-411-v-zum-famzg/` | Verordnung zum Einführungsgesetz zum Bundesgesetz über die Familienzulagen (bGS 822.411) | 4 | oldest version available, then each consolidated version: 1 January 2011 to 1 January 2016 |
| `823-1/` | Verordnung über das kantonale Einigungsamt (bGS 823.1) | 1 | as enacted, 2 September 1949 |
| `824-01/` | Verordnung zur Bundesgesetzgebung über die in die Schweiz entsandten Arbeitnehmerinnen und Arbeitnehmer und flankierende Massnahmen (bGS 824.01) | 3 | oldest version available, then each consolidated version: 1 February 2006 to 30 September 2016 |
| `824-11/` | Verordnung über die Arbeitsvermittlung und die Arbeitslosenversicherung (bGS 824.11) | 3 | oldest version available, then each consolidated version: 1 January 2003 to 30 September 2016 |
| `831-11/` | Verordnung über die Entschädigung der Mitglieder der Verwaltungskommission der Ausgleichskasse und der IV-Stelle Appenzell Ausserrhoden (bGS 831.11) | 1 | as enacted, 1 June 2016 |
| `832-311/` | Verordnung über Ergänzungsleistungen zur Alters-, Hinterlassenen- und Invalidenversicherung (bGS 832.311) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2016 |
| `833-141-v-zum-kvg/` | Verordnung zum Gesetz über die Einführung des Bundesgesetzes über die Krankenversicherung (bGS 833.141) | 4 | as enacted, then each consolidated version: 1 January 2010 to 1 January 2017 |
| `833-151-pfv/` | Verordnung über die Pflegefinanzierung (bGS 833.151) | 7 | as enacted, then each consolidated version: 1 January 2017 to 1 January 2026 |
| `834-11/` | Geschäftsreglement für die tripartite Kommission des Kantons Appenzell A.Rh. (bGS 834.11) | 3 | oldest version available, then each consolidated version: 1 February 2006 to 1 January 2017 |
| `841-2/` | Verordnung über Massnahmen zur Sanierung der Wohnverhältnisse in den Berggebieten (bGS 841.2) | 2 | oldest version available, then each consolidated version: 1 January 2008 to 30 September 2016 |
| `841-11/` | Verordnung zum Gesetz vom 24. April 1966 über Massnahmen zur Förderung des Wohnungsbaues (bGS 841.11) | 1 | as enacted, 24 October 1966 |
| `851-11-sozialhilfeverordnung-shv/` | Verordnung zum Gesetz über die öffentliche Sozialhilfe (bGS 851.11) | 2 | as enacted, then each consolidated version: 1 January 2009 to 1 January 2016 |
| `852-51/` | Verordnung zur Interkantonalen Vereinbarung für Soziale Einrichtungen (bGS 852.51) | 5 | as enacted, then each consolidated version: 1 January 2008 to 14 January 2022 |
| `852-61-behindertenfinanzierungsverordnung-befiv/` | Verordnung zur Finanzierung von Leistungsangeboten für Menschen mit Behinderung (bGS 852.61) | 4 | oldest version available, then each consolidated version: 1 July 2009 to 14 January 2022 |
| `861-1-feuerschutzverordnung/` | Verordnung über den Feuerschutz (bGS 861.1) | 1 | one version (the oldest available), 1 January 2009 |
| `862-11-assekuranzverordnung/` | Verordnung über die Gebäude- und Grundstückversicherung (bGS 862.11) | 2 | oldest version available, then each consolidated version: 1 January 2009 to 1 January 2020 |
| `862-111/` | Verordnung über die Entschädigung der Mitglieder des Verwaltungsrates der Assekuranz (bGS 862.111) | 2 | as enacted, then each consolidated version: 1 January 2020 to 1 July 2024 |
| `911-11/` | Verordnung über die Wirtschaftsförderung (bGS 911.11) | 3 | oldest version available, then each consolidated version: 2 December 2008 to 30 September 2016 |
| `920-11/` | Pflanzenschutzverordnung (bGS 920.11) | 4 | as enacted, then each consolidated version: 1 January 1999 to 30 September 2016 |
| `920-12-strukturverbesserungsverordnung/` | Verordnung über die Strukturverbesserungen in der Landwirtschaft (bGS 920.12) | 2 | as enacted, then each consolidated version: 1 January 2000 to 1 January 2016 |
| `920-13-awv/` | Verordnung über die Alpwirtschaft (bGS 920.13) | 2 | as enacted, then each consolidated version: 1 January 2000 to 1 January 2016 |
| `920-14-tzv/` | Verordnung über die Tierzucht (bGS 920.14) | 2 | as enacted, then each consolidated version: 1 January 2000 to 1 January 2016 |
| `920-16-kweinv/` | Kantonale Weinverordnung (bGS 920.16) | 2 | as enacted, then each consolidated version: 1 March 2013 to 30 September 2016 |
| `920-17-lqbv/` | Verordnung über die Landschaftsqualitätsbeiträge (bGS 920.17) | 1 | as enacted, 1 July 2014 |
| `920-18-vnbv/` | Verordnung über die Vernetzungsbeiträge (bGS 920.18) | 1 | as enacted, 9 December 2016 |
| `920-161-rebv/` | Verordnung über zugelassene Rebsorten (bGS 920.161) | 1 | as enacted, 1 March 2013 |
| `921-3/` | Verordnung zum Bundesgesetz über die landwirtschaftliche Pacht (bGS 921.3) | 2 | oldest version available, then each consolidated version: 1 January 1995 to 1 January 2016 |
| `925-32-tgv/` | Verordnung über die Tiergesundheit (bGS 925.32) | 2 | as enacted, then each consolidated version: 1 January 1999 to 1 January 2016 |
| `925-321-veav/` | Verordnung über die Entschädigungen und Abgaben im Veterinärwesen (bGS 925.321) | 1 | as enacted, 1 June 2016 |
| `931-11-kantonale-waldverordnung/` | Verordnung zum kantonalen Waldgesetz (bGS 931.11) | 2 | oldest version available, then each consolidated version: 1 January 2008 to 30 September 2016 |
| `955-14/` | Verordnung zum Bundesgesetz vom 21. Juni 1932 über die gebrannten Wasser (Alkoholgesetz) (bGS 955.14) | 2 | oldest version available, then each consolidated version: 1 January 1995 to 30 September 2016 |
| `955-51/` | Verordnung zum Bundesgesetz über den Konsumkredit vom 23. März 2001 (KKG) und zur bundesrätlichen Verordnung zum Konsumkreditgesetz vom 6. November 2002 (VKKG) (bGS 955.51) | 2 | as enacted, then each consolidated version: 1 January 2004 to 30 September 2016 |
| `955-111-gastgewerbeverordnung/` | Verordnung zum Gesetz vom 7. Februar 1999 über das Gastgewerbe (bGS 955.111) | 2 | as enacted, then each consolidated version: 1 May 1999 to 30 September 2016 |
| `955-213-tv/` | Tourismusverordnung (bGS 955.213) | 1 | as enacted, 1 June 2017 |
| `955-311-vkgs/` | Verordnung zum kantonalen Geldspielgesetz (bGS 955.311) | 1 | as enacted, 1 February 2022 |
| `955-321-lotteriefondsverordnung-lofv/` | Verordnung über die Zuweisung und Verwendung der Reingewinne aus Grossspielen (bGS 955.321) | 2 | oldest version available, then each consolidated version: 1 January 1995 to 1 February 2022 |
| `956-11/` | Verordnung zum Bundesgesetz über das Messwesen (bGS 956.11) | 2 | as enacted, then each consolidated version: 1 December 2008 to 30 September 2016 |
| `956-33/` | Verordnung zum Bundesgesetz vom 25. März 1977 über explosionsgefährliche Stoffe (Sprengstoffgesetz) (bGS 956.33) | 2 | oldest version available, then each consolidated version: 1 January 1995 to 1 January 2016 |
| `956-311/` | Verordnung zum Bundesgesetz vom 4. Oktober 1930 über die Handelsreisenden sowie über die dazugehörende Vollziehungsverordnung vom 5. Juni 1931 (bGS 956.311) | 1 | one version (the oldest available), 1 January 2007 |

## Source

The bGS (systematic collection) of the canton, published by the canton at <https://ar.clex.ch/>. For each act it gives every consolidated version it holds, with the day each version took effect, and a change table listing each amendment: its decision date, the day it took effect, the provision it touched and its entry in the chronological collection (CRS). Annexes the collection publishes only as separate PDF files are not included.

## Dates

- Each commit is dated at **noon, Europe/Zurich, on the day the version took effect**, as the collection gives it ("in Kraft seit / von"). The decision date of each amending act is the `Enacted:` trailer.
- An act's first commit is its oldest version in the collection. It is credited to the act as enacted only when the change table shows no amendment in force before it; otherwise it is the "oldest version available", naming the earlier amendments.
- Versions that take effect after the retrieval day are on the `zukunft` branch, never merged into `main`.
- `--before="YYYY-MM-DD"` alone uses your clock's time of day; use `T23:59:59Z` or `tools/on.py`.

## Files

`<act>/art-005.md` is Art. 5 (or § 5), `art-005a.md` Art. 5a; `ingress.md` holds the title, date and preamble; `gliederung.md` the section headings; `schluss.md` the closing formula and signatures. One paragraph or list item per line. Amendment markers (`*`), footnote numbers and the "Stand" date are left out.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the canton's own text of that version, and every article's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the amending act, named by its entry in the chronological collection (CRS), with an e-mail address that cannot exist (`<act key>@ar.clex.ch.invalid`). Where one version holds changes by several amending acts and the change table does not say which provision each one touched, the commit names them all. The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one the canton publishes as binding (its chronological collection, or its systematic collection where cantonal law makes that binding). The history starts with the oldest consolidated version the collection holds for each act, which for many acts is later than the act's enactment. Only the acts listed above are included.
