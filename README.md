# NeedleTelemetry

[![CI](https://github.com/combo-lab/needle_telemetry/actions/workflows/ci.yml/badge.svg)](https://github.com/combo-lab/needle_telemetry/actions/workflows/ci.yml)
[![Hex.pm](https://img.shields.io/hexpm/v/needle_telemetry.svg)](https://hex.pm/packages/needle_telemetry)

Provides a modular approach for using [beam-telemetry](https://github.com/beam-telemetry) packages.

## Notes

This package is still in its early stages, so it may still undergo significant changes, potentially leading to breaking changes.

## Installation

Add `:needle_telemetry` to the list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:needle_telemetry, "<requirement>"}
  ]
end
```

> **Note**
>
> `:needle_telemetry` is depending on following packages:
>
> - `:telemetry`
> - `:telemetry_poller`
> - `:telemetry_metrics`
>
> If you want to use them, there is no need to add them to `mix.exs` explicitly. They are available after you adding `:needle_telemetry`.

## Usage

For more information, see the [documentation](https://hexdocs.pm/needle_telemetry).

## License

MIT
