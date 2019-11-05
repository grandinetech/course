# Implementation II
  
Complete the chosen module using [Rust](https://www.rust-lang.org/) programming language and the following requirements:

* Deliver the full module (implement the missing parts that were not implemented in task III) as a Rust crate following the specification. The crate should be interchangeable with alternative implementations (delivered by other students or contributors) within the platform.
* Define a public interface of the crate. Other teams may depend on your crate so publish your interface as early as possible. The fastest wins, but the original author still has a right to change the interface if a better option is offered by some other team.
* Follow [Rust](https://www.rust-lang.org/) language best practices. Prefer type-safe code as long as it doesn't dramatically increase compile time.
* Implement proper error handling for the entire crate. For example, `assert` should not be used in most of the cases, instead use `Result` object as this will allow the caller to handle error in a graceful way.
* Write automated tests. Desired automated test coverage is 100%. The coverage may be lower if there is a valid reason, however, the coverage must be at least 80%. Tests must pass.
* Pass the linters and any other checks in `scripts/ci`. Do not ignore the Clippy lints, it is allowed to use even more restrictive linting profile.
* Make a fork and a pull request if you need any changes to the provided type system. Your pull request will be merged once +1 every team approves it.
* Make a fork and a pull request for your crate and improve the code according to the feedback on Github.

Reward: 1.5 points.
