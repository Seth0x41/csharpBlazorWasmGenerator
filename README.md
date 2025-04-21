# csharpBlazorWasmGenerator

This repo generates the runtime files required to run C# in the browser using Blazor WebAssembly with a WebAssembly-based .NET runtime (as used in [LiveCodes](https://livecodes.io/)).

## Example for generated files

- repo: https://github.com/Seth0x41/csharp-wasm
- npm package: https://www.npmjs.com/package/@seth0x41/csharp-wasm

## .NET Version Update

Run `dotnet publish` and upload the WebAssembly files from the publish/wwwroot/_framework directory to a CDN.

## License

MIT
