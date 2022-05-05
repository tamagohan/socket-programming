# Network programming with Rust

## How to use

### How to use TCP/UDP clinet/server

Change directory to `/server_and_client`

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

### How to use pcaket-capture

Change directory to `packet-capture`

* Confirm your network interface name
  `ex: $ip addr`
* Run packet-capture

  ```shell
  cargo build
  sudo sudo ./target/debug/packet-capture <network interface name>
  # example
  sudo sudo ./target/debug/packet-capture en0
  ```

### How to run webserver

Change directory to `webserver`

* Place the html files you want to host under the webroot folder in advance
* Run the webserver

  ```shell
  cargo run 127.0.0.1:8080
  ```
