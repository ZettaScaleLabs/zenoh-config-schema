# JSON Schema for Zenoh configuration

> [!CAUTION]
> The provided schemas are LLM-generated and thus remain experimental and not guaranteed to be fully accurate.

This repository contains a set of versioned
[Draft 4](https://json-schema.org/specification-links#draft-4)
JSON Schemas for Zenoh configuration files.

## Usage

```toml
#:schema https://raw.githubusercontent.com/ZettaScaleLabs/zenoh-config-schema/main/1.7.2.json
# see https://taplo.tamasfe.dev/configuration/developing-schemas.html

id = "abc"
mode = "client"

[connect]
endpoints = ["tcp/127.0.0.1:9000"]
```

## License

The schemas are generated from Eclipse Zenoh source code and are thus assumed to fall under the
Eclipse Zenoh license. Whether the license(s) of the LLM's training input affect this
assessment does not seem to have a clear answer—I am not a lawyer.
