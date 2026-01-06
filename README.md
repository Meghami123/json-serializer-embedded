# Embedded JSON Serializer (C)

## Overview
This project implements a lightweight, embedded-friendly JSON serialization
library written in C. The serializer converts structured meter data into a
predefined JSON format without using dynamic memory allocation.

## Platform & Development Environment
- Target Platform: Arduino framework (portable to STM32 / ESP32)
- Language: C
- Development Environment: Arduino IDE / STM32CubeIDE compatible

## Verification
The core serialization logic was verified using a host-based C compiler
(Programiz Online Compiler). The same code can be directly integrated into
embedded firmware projects where the JSON string can be transmitted over
UART, Serial, or network interfaces.

## Build & Run (Arduino_demo.ino)
