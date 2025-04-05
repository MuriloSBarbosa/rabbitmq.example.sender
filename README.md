# RabbitMQ Example Sender

![Python](https://img.shields.io/badge/Python-3.x-blue)  
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-Message%20Broker-orange)  

This project demonstrates a simple RabbitMQ message sender implemented in Python. It is designed to showcase how to send messages to a RabbitMQ queue.

## Features

- Connects to a RabbitMQ server.
- Sends messages to a specified queue.
- Easy-to-understand implementation for learning purposes.

## Prerequisites

- Python 3.x installed.
- RabbitMQ server running locally or remotely.
- `pika` library installed.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/rabbitmq.example.sender.git
    cd rabbitmq.example.sender
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Start your RabbitMQ server.

2. Run the sender script:

    ```bash
    python sender.py
    ```

3. Check the RabbitMQ management interface or the consumer to verify the messages.

## Configuration

You can configure the RabbitMQ connection settings (e.g., host, port, queue name) in the `config.py` file.


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [RabbitMQ Documentation](https://www.rabbitmq.com/documentation.html)
- [Pika Library](https://pika.readthedocs.io/)
