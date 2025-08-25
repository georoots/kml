# GeoRoots KML
Browser based tool that convers KML data into EU Deforestation Regulation (EUDR) compatible GeoJSON format

## Usage

* Open the kml.html file in your browser.
* Select a language from the dropdown at the top.
* Drag & Drop correctly prepared .kml file into the centre of the page or use the file selector button.
* Once loaded, enter additional information like Country (does not get automatically detected), Producer Name and enter size for Point geometries (KML files do not usually store this information)
* Once complete, press generate GeoJSON and the final file will be donwloaded by your browser and saved into your downloads.

## FAQ

##### Q: **My language is not included. Can it be added?**
A: Yes, please open an issue ticket and request a new language.

##### Q: **Why does the program load country if it knows the location?**
A: Country border definitions are a dataset in itself and may require amendments from time to time. To keep this program lightweigh and work offline, it is not performing country identification.

##### Q: **What format do I need to enter the country code in?**
A: The country code should be in two letter country code: [Wikipedia ISO 3166-1 alpha-2](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-2)



## About GeoRoots: Open Source Toolkit for EUDR Compliance and geo traceability

GeoRoots is a collection of minimalistic, open-source tools designed specifically for EU Deforestation Regulation (EUDR) requirements and enhancing geo traceability.

Our philosophy is simple: provide useful tools that respect your privacy, work offline (where possible), and require no complex setup or subscription fees. Every tool runs entirely in your browser and can be downloaded for offline use.

### Why Use GeoRoots?

*   **100% Private**: All tools run locally in your browser. No data is ever transmitted to external servers.
*   **Open Source**: Fully open source and transparent. Inspect, modify, and contribute to the code.
*   **Offline Ready**: Download and use tools completely offline. Perfect for remote locations.
*   **Mobile Friendly**: Works on desktop, tablet, and mobile devices.

### Perfect for:

*   Producers and cooperatives
*   Smaller traders and exporters
*   Importers, operators
*   Sustainability consultants

### Useful Official Resources

*   [EUDR DDS on LIVE Environment](https://eudr.webcloud.ec.europa.eu/tracesnt/)
*   [EUDR DDS on TEST Environment](https://acceptance.eudr.webcloud.ec.europa.eu/tracesnt/)
*   [EUDR on Green Forum](https://green-forum.ec.europa.eu/deforestation-regulation-implementation/information-system-deforestation-regulation_en)
*   [EUDR on EUR-Lex](https://eur-lex.europa.eu/legal-content/EN/HIS/?uri=CELEX:52024PC0452)

### License

This project is licensed under the GPLv3 License. See the [LICENSE](LICENSE) file for details.

### Contributing

We welcome contributions! Please see our [contribution guidelines](CONTRIBUTING.md) for more information.


### Contact

For any questions or feedback, please open an issue on this repository.
