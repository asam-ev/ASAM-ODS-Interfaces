# ASAM ODS Interfaces

This repository contains [Protocol Buffer (.proto)](https://protobuf.dev/overview/) files from the [ASAM ODS standard](https://www.asam.net/standards/detail/ods/). These files are provided as a convenience for developers working with ODS services and are utilized by various pipelines to facilitate communication with ODS services.

## Overview

The [ASAM ODS (Open Data Services)](https://www.asam.net/standards/detail/ods/wiki/) standard defines a set of services and protocols for the management and exchange of measurement data in the automotive industry. The .proto files in this repository define the Protocol Buffer schemas used to interface with
 these ODS services.

## Repository Contents

- `.proto` files: Protocol Buffer definitions for ASAM ODS services.
- `ODSBaseModel_asam??.protobuf.json` file. Representing a protobuf `ods:BaseModel` instance from `ods.proto` [serialized as json](https://protobuf.dev/programming-guides/proto3/#json).

## Usage

To use the `.proto` files follow the [protobuf getting started](https://protobuf.dev/getting-started/).

## Maintenance and Support

The files in this repository are maintained exclusively by the ASAM ODS development projects as part of further development of the [ASAM ODS standard](https://www.asam.net/standards/detail/ods/).

### Reporting Issues

If you encounter any issues with the .proto files, please report them by opening an issue in this repository. We will forward the issues to the appropriate ASAM ODS project team for resolution.

## Disclaimer

The files provided in this repository are made available as a convenience. They are not officially supported or endorsed by ASAM. Use them at your own risk.

## License

This project is licensed under the terms of the [Mozilla Public License 2.0](LICENSE).

---

For more information about ASAM ODS, please visit the official [ASAM website](https://www.asam.net/standards/detail/ods/).

---

Feel free to contribute by forking this repository and submitting pull requests. However, please note that all contributions will be reviewed by the ASAM ODS project team.

---

Maintained by ASAM e.V.

Contact: info@asam.net

---
