# Changelog

## 1.3.2
- Nuget refs updated and new `QueueLimit` option added to bound the in-memory queue used for log entries. This is useful for adding back-pressure to avoid out-of-memory issues with high-volume logging.

## 1.3.1
- Added `netstandard2.0` to improve dependency graph in newer solutions. See guidance at https://docs.microsoft.com/en-us/dotnet/standard/library-guidance/cross-platform-targeting

## 1.3.0
- Fix bug with default JSON object writer ending quote.

## 1.2.0
- Config options to toggle JSON output with a single sink.
- Extension methods for Serilog log configuration.
- Allow custom delegate to replace JSON object writer.

## 1.0.0
- Initial console sinks for plaintext and JSON.
