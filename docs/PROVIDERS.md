# List of TRIAS Providers

This is a list of public transport providers that provide a TRIAS API. Be aware that:
- Most of them **do not offer open APIs**, but require you to sign up with them.
- Not all providers offer the same functionalities. The TRIAS specification is *enormous* and most providers only implemented the basic stuff.
- All providers prohibit automated mass requests and enforce some other legalse, e.g. legal disclaimers in your app. Make sure to check their usage agreements.


### [Bayerische Eisenbahngesellschaft (DEFAS)](https://www.bayern-fahrplan.de/de/faq/hintergrundinfos)

- :heavy_check_mark: Supports Location Information, Stop Events and Trips
- :x: Contract required
- :x: *Really* complex onboarding

### [Karlsruher Verkehrsverbund](https://www.kvv.de/fahrplan/fahrplaene/open-data.html)

- :heavy_check_mark: Supports Location Information, Stop Events and Trips
- :x: Contract required

### [Münchner Verkehrsverbund](https://www.mvv-muenchen.de/fahrplanauskunft/fuer-entwickler/index.html)

Coming soon™.

### [Nahverkehr Baden-Württemberg (bwegt)](https://www.mobidata-bw.de/dataset/trias)

- :heavy_check_mark: Supports Location Information, Stop Events and Trips
- :x: Contract required

### [Schweizerische Bundesbahnen](https://opentransportdata.swiss/dataset/aaa) (Switzerland)

- :heavy_check_mark: Supports Location Information, Stop Events and Trips
- :heavy_check_mark: No contract required

They provide an open API for testing purposes. Use `https://api.opentransportdata.swiss/trias2020` as URL and `57c5dbbbf1fe4d000100001842c323fa9ff44fbba0b9b925f0c052d1` as `Authorization` header.

### [Verkehrsverbund Bremen & Niedersachsen](https://www.vbn.de/service/entwicklerinfos/)

- :heavy_check_mark: Supports Location Information, Stop Events and Trips
- :heavy_check_mark: No contract required
- :x: Only 3000 requests per day

### [Verkehrsverbund Oberelbe](https://www.govdata.de/daten/-/details/api-fahrplanauskunft-vvo)

- :heavy_check_mark: Supports Location Information, Stop Events and Trips
- :heavy_check_mark: Open Data

Use `http://efa.vvo-online.de:8080/std3/trias` as URL and `OpenService` as requestor ref. Make sure to set the `Content-Type` header to `text/xml` instead of `application/xml` (which is the default of `trias-client`).

### [Verkehrsverbund Region Trier](https://www.vrt-info.de/openservice)

- :heavy_check_mark: Supports Location Information, Stop Events and Trips
- :heavy_check_mark: No contract required

### [Verkehrsverbund Rhein-Neckar](https://www.vrn.de/opendata/API)

- :heavy_check_mark: Supports Location Information, Stop Events and Trips
- :heavy_check_mark: No contract required

### [Verkehrsverbund Rhein-Ruhr](https://openvrr.de/pages/api)

- :heavy_check_mark: Supports Location Information, Stop Events and Trips
- :grey_question: Contract might be required
- :x: Does not answer to onboarding requests

They provide an open API for testing purposes. Use `http://openservice-test.vrr.de/opendataT/trias` as URL.

### [Verkehrsverbund Rhein-Sieg](https://www.vrs.de/fahren/fahrplanauskunft/opendata-/-openservice)

- :heavy_check_mark: Supports Location Information, Stop Events and Trips
- :grey_question: Contract might be required

### [Verkehrsverbund Steiermark](https://www.verbundlinie.at/fahrplan/rund-um-den-fahrplan/link-zum-fahrplan) (Austria)

- :heavy_check_mark: Supports Location Information, Stop Events and Trips
- :heavy_check_mark: No contract required

### [Verkehrsverbund Stuttgart](https://www.openvvs.de/pages/api)

- :heavy_check_mark: Supports Location Information, Stop Events and Trips
- :heavy_check_mark: No contract required

The link to be used for requests here is: `https://www.efa-bw.de/trias?`
