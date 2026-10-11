# task6-fault-tolerant-system
Task 6 implements a fault-tolerant monitoring system using ESP32, FreeRTOS, and MQTT. It detects Wi-Fi and MQTT failures, displays network status on an OLED, and triggers buzzer alerts. Sensor readings are buffered locally during outages and automatically synchronized to the cloud after reconnection using exponential backoff.
