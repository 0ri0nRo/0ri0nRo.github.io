---
title: "My Skills"
---

### Current Position: IoT Developer

In my current role as an IoT Developer, I specialize in leveraging AWS cloud services to design, develop, and maintain Internet of Things (IoT) solutions. My responsibilities encompass a wide range of tasks and technologies, primarily focused on AWS infrastructure and services. Below are the key areas of my expertise and the tools I employ in my day-to-day operations:

#### Key Responsibilities

- **Development**: Creating scalable and efficient IoT solutions using AWS services.
- **Integration**: Seamlessly integrating various AWS services to build robust and secure IoT ecosystems.
- **Maintenance and Optimization**: Ensuring optimal performance of IoT applications and continuously improving existing solutions.

#### Technologies and Tools

- **AWS Cloud**: Utilizing the extensive range of AWS cloud services to build and deploy IoT applications.
- **AWS Lambda**: Implementing serverless computing to run code in response to triggers and events, ensuring efficient resource utilization.
- **API Gateway**: Creating and managing APIs to facilitate communication between IoT devices and backend services.
- **AWS DynamoDB**: Leveraging DynamoDB for scalable and low-latency data storage solutions.
- **Python**: Using Python as the primary programming language for developing IoT applications, enabling rapid development and deployment.

By harnessing these technologies, I contribute to developing innovative IoT solutions that drive efficiency, enhance connectivity, and provide valuable insights from connected devices. My role requires staying up-to-date with the latest advancements in IoT and AWS technologies to ensure that our solutions remain cutting-edge and competitive in the market.

#

### Blockchain and Smart Contracts
- **Solidity**: Programming language for creating smart contracts on Ethereum and other blockchains.
- **Ethereum Virtual Machine (EVM)**: Execution environment for Ethereum smart contracts.

### Programming Languages
- **Go**: Programming language used to develop GETH, the official implementation of the Ethereum client.
- **Ego**: A Go-based programming language, designed to simplify the development of blockchain applications. It allows interaction with the Ethereum blockchain and efficient writing of smart contracts.
- **Python**: Programming language used to develop API with FastAPI and Flask framworks.
- **Java**
- **C**
- **SQL** with PostgreSQL and MySQL

### Containerization
- **Docker**: Open-source platform used for developing, shipping, and running applications in containers. Docker containers allow developers to isolate their applications and their dependencies in lightweight and portable environments, making it easier to deploy and manage applications across different platforms.

### Trusted Execution Environments (TEE)
- Experience in leveraging TEE for secure and trusted execution of code, especially in the context of IoT where data security and protection are crucial.
## MQTT
MQTT (Message Queuing Telemetry Transport) is a lightweight, open messaging protocol based on a publish-subscribe model. It is designed for communication between network devices with resource constraints, such as IoT devices, sensors, and mobile applications.

1. **Lightweight**: MQTT is designed to be extremely lightweight in terms of network overhead and resource usage. This makes it suitable for devices with limited resources such as sensors, microcontrollers, and IoT devices.
2. **Publish-Subscribe Model**: MQTT uses a publish-subscribe communication model, where devices can act as producers (publishers) and consumers (subscribers) of messages.
3. **QoS (Quality of Service)**: MQTT supports various levels of QoS to ensure the reliability and delivery of messages. QoS levels include QoS 0 (at most once), QoS 1 (at least once), and QoS 2 (exactly once), with different levels of delivery guarantee.
4. **Retain Flag**: MQTT offers the ability to set the "retain" flag on a message, which means that the MQTT broker will store the last message published on a specific topic and send it to new subscribers when they subscribe to that topic.
5. **Clean and Persistent Sessions**: MQTT supports both clean and persistent sessions. With clean sessions, the broker does not maintain any session information for clients after disconnection. With persistent sessions, the broker maintains session information, allowing clients to resume their activity after reconnection.

## Alembic
- Alembic is a database migration tool for Python, and I used it with the SQLAlchemy ORM (Object-Relational Mapping) framework.
- It allows managing database migrations in a simple and controlled way, allowing changes to the database schema in an incremental and reversible way.
- Database migrations are defined as Python scripts that describe the changes to be made to the database.
- Alembic keeps track of the current state of the database and applies migrations.

## Uvicorn
- Uvicorn is an ASGI (Asynchronous Server Gateway Interface) server for Python, used to run asynchronous web applications.
- It integrates well with modern web frameworks like FastAPI, which support asynchronous operations in Python.

## MQTT, FASTAPI Project
The MQTT project for retrieving and managing weather data from the OpenWeatherMap API. The main objectives include:

- Use an MQTT publisher to retrieve weather data and publish it on an MQTT broker.
- Implement an MQTT subscriber to subscribe to data from the MQTT broker and save it in a database.
- Saving to MySQL and MongoDB.
- Unit tests to ensure the basic functionality of the system (used pytest and mock for simulations).
- Publish data from the database on a basic dashboard using Grafana for visualization (Subsequently Power BI).

## AI Chess Detector
- **Project Objective**: Explore the potential of Artificial Intelligence and Computer Vision in solving problems related to understanding and interpreting a chess game.
- **Chessboard**: Usually consists of a magnetic or touch-sensitive playing surface. When a piece is moved, the sensors record the movement.
- **Convolutional Neural Network (CNN)**

Visit my [GitHub page](https://github.com/0ri0nRo) to see more code!
