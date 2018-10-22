# Introduction

In August of 2015 Trust-DNS began as an experiment developing a set of libraries and tools for developing DNS server and client software. Since that time it has grown to include a native Rust (stub) resolver and proceeded to become used in more and more contexts. The libraries are fully featured, such they implement many of the DNS RFCs (request for comments), which generally make up the "specification" of DNS.

Trust-DNS is made up of four primary libraries (crates). The `trust-dns-proto` crate is responsible for the implementation of the core DNS parsers and Record Data implementations. The `trust-dns-resolver` crate is a stub resolver, fully capable of replacing a system resolver, and being embedded in Rust software. The `trust-dns` (client) crate, useful for when low-level access to DNS is required, also supporting dynamic DNS. The `trust-dns-server` crate, which implements the tools for building a name server in Rust (as well as the official `named` binary for Trust-DNS).

The dream is to make Trust-DNS the most stable, and trusted set of DNS software ever written. This dream has only been ventured with the support of the Rust programming language's guarantees, and the amazing support of the Rust programming community. Hint: Rust is in the name.
