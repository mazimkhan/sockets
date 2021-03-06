# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
## [v1.1.1]
### Improved
- Documentation now defines expected error codes
- Error codes returned match documentation
- Additional checks for failing conditions

### Added
- A new TCPStream constructor for use with ```accept()```
- The previous TCPStream constructor used with ```accept()``` is now deprecated


## [v1.1.0]
### Improved
- SocketAddr now formats both IPv4 and IPv6 addresses
- SocketAddr now interprets text addresses into internal representation with the setAddr API
- Added an API to enable/disable Nagle's algorithm on TCP Streams
