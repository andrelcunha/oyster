# Oyster

Oyster is a lightweight containerization tool inspired by Docker. It aims to help developers understand containerization concepts and learn Go by implementing core Docker features.

## Features

- Create and manage containers
- Build and handle images
- Manage container networking
- Persistent storage management
- Simple CLI and API for interaction


## Getting Started

### Prerequisites

- [Go](https://golang.org/dl/) installed (version 1.18 or higher)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yandrelcunha/oyster.git
   ```
2. Navigate to the project directory:
   ```sh
   cd oyster
   ```
3. Build the project:
   ```sh
   go build -o oyster
   ```
## Usage
### Running a Container
```sh
./oyster run <image>
```
### Stopping a Container
To stop a container:
```sh
./oyster stop <container_id>
```
## License
This project is licensed under the MIT License. See the ￼LICENSE file for more details.
## Acknowledgments
- Inspired by [Docker](https://www.docker.com/)
- Build with [Cobra](https://github.com/spf13/cobra)