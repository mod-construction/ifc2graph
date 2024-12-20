# ifc2graph

A Python tool for converting Industry Foundation Classes (IFC) files into knowledge graphs, enabling semantic analysis and querying of building information models.

## Overview

`ifc2graph` transforms IFC-based Building Information Models (BIM) into graph-based representations, making it easier to:

- Query complex relationships between building elements
- Perform semantic analysis of building data
- Enable knowledge discovery in construction datasets
- Integrate BIM data with other graph-based systems

## Features

- Convert IFC files to property graphs
- Support for common IFC schemas (IFC2X3, IFC4)
- Export to various graph formats (Neo4j, RDF, GraphML)
- Preserve IFC relationships and properties
- Configurable mapping rules
- Batch processing capabilities

## Installation
```bash
pip install ifc2graph
```

## Usage
```bash
ifc2graph -i input.ifc -o output.graphml
```


---

## Contributing

We appreciate feedback and contribution to this project! Before you get started, please see the following:

* [Contribution guidelines](CONTRIBUTING.md)
* [Code of conduct](CODE_OF_CONDUCT.md)

## License

[MIT](LICENSE)
