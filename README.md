# Network programming with Rust

## How to use

* start TCP Server

  ```shell
  cargo run tcp server <address>:<port>
  # example
  cargo run tcp server 127.0.0.1:33333
  ```

* start TCP Client

  ```shell
  cargo run tcp client <address>:<port>
  # example
  cargo run tcp client 127.0.0.1:33333
  ```

* start UDP Server

  ```shell
  cargo run udp server <address>:<port>
  # example
  cargo run udp server 127.0.0.1:33333
  ```

* start UDP Client

  ```shell
  cargo run udp client <address>:<port>
  # example
  cargo run udp client 127.0.0.1:33333
  ```
