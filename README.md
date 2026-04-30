# hubble-device-sdk-blobs

Pre-compiled binary blobs for the [Hubble Network Device SDK](https://github.com/HubbleNetwork/hubble-device-sdk). These static libraries contains functionalities necessary to implement Hubble satellite network protocol.

## Contents

| Path | Target SoC series | Description |
|---|---|---|
| `nrf52/libhubble_sat_nrf52.a` | nRF52 | Hubble SAT network library for nRF52 series |
| `nrf53/libhubble_sat_nrf53.a` | nRF53 (network core) | Hubble SAT network library for nRF53 series |
| `nrf54/libhubble_sat_nrf54.a` | nRF54 (app core) | Hubble SAT network library for nRF54 series |

Each blob ships with a corresponding `.sha256` file for integrity verification.

## License

See [LICENSE](LICENSE) for terms governing distribution and use of these binaries.
