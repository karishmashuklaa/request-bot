A bot that sends requests to a backend API indefinitely.

### Usage

1. Clone the repository

2. Build the Project

Ensure you have Rust installed. If not, <a href="https://www.rust-lang.org/tools/install">install Rust</a>.
```
cargo build
```

3. Run the program
```
cargo run
```
By default, it sends all requests to  <a href="https://google.com">google.com</a>. To pass your own site, run the following command
```
cargo run -- https://example.com
```
4. Monitor Output

The program will start sending requests indefinitely and display output for each request
```
Request 0 => Success => Status code: 200
Request 1 => Failed => [Error Message]
```
---
This tool is for educational and experimental purposes only. Avoid using it for any malicious activities.
