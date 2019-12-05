# Interoperability
  
Demonstrate that your module developed in the previous tasks works correctly with the other Ethereum 2 implementations:

* Fully integrate your module. This task involves any changes and efforts needed to fully integrate your module. Most likely these activities will not be limited by only bug fixing, teams are responsible to communicate and solve any issues that arise during the integration of the modules.
* Demonstrate live interoperability with the latest version of a leading Ethereum 2 implementation. Use interoperability scripts provided in the project repository.
* Deliver your full module (implement any needed changes) as a Rust crate following the specification. The crate should be interchangeable with alternative implementations (delivered by other students or contributors) within the platform.
* Follow [Rust](https://www.rust-lang.org/) language best practices. Prefer type-safe code as long as it doesn't dramatically increase compile time.
* Implement proper error handling for the entire crate. For example, `assert` should not be used in most of the cases, instead use `Result` object as this will allow the caller to handle error in a graceful way.
* Write automated tests. Desired automated test coverage is 100%. The coverage may be lower if there is a valid reason, however, the coverage must be at least 80%. Tests must pass.
* Demonstrate that your crate implements the specification correctly.
* Pass the linters and any other checks in `scripts/ci`. Do not ignore the Clippy lints, it is allowed to use even more restrictive linting profile.
* Make a fork and a pull request if you need any changes to the provided type system. Your pull request will be merged once +1 every team approves it.
* Make a fork and a pull request for your crate and improve the code according to the feedback on Github.

Reward: 1.5 points.
