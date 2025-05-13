# Application 1
This folder contains my LED blinking and telemetry task.
# Application 1 – LED Blink + Console Output

**Name:** Destiny Ellenwood 
**Course:** EEE 4775 - Real-Time Systems  
**Theme Chosen:** Space Systems  

## Summary
This project simulates a satellite beacon using a blinking LED (2 Hz) and logs telemetry to the console every 10 seconds using FreeRTOS tasks.

## Timing Behavior
- **LED task period:** 500 ms
- **Console task period:** 10,000 ms
- Tasks use `vTaskDelay` to ensure accurate timing.
- Verified by console timestamps and observing LED behavior.

## Wokwi Link
[https://wokwi.com/projects/...](#)

## AI Usage
Used ChatGPT to help translate ESP-IDF-style `app_main()` into Arduino-style `setup()` and to verify FreeRTOS timing accuracy.

## Notes
- Used `xTaskCreate()` for both tasks
- Tasks run concurrently with equal priority
