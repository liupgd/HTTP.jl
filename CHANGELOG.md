# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.9.8] - 2020-05-01

## [0.9.7] - 2020-04-28
### Added
- Implement `Sockets.getpeername(::HTTP.Stream)` for getting the client IP address and port
  from a `HTTP.Stream` ([#702]).

## [0.9.6] - 2020-04-XX
### Added
- New function `HTTP.statustext` for getting the string representation of a HTTP status code ([#XXX]).
- New exception `ReadTimeoutError` which is thrown for request that time out ([#XXX]).
### Changed
- Un-deprecate `HTTP.status`, `HTTP.headers`, `HTTP.body`, `HTTP.method`, and `HTTP.uri` ([#XXX).
### Fixed
- Fixes and improvements to rate limiting in `HTTP.listen` and `HTTP.serve` ([#XXX]).

[Unreleased]: https://github.com/JuliaWeb/HTTP.jl/compare/v0.9.8...HEAD
[0.9.8]: https://github.com/JuliaWeb/HTTP.jl/compare/v0.9.7...v0.9.8
[0.9.7]: https://github.com/JuliaWeb/HTTP.jl/compare/v0.9.6...v0.9.7


[#702]: https://github.com/JuliaWeb/HTTP.jl/pull/702
