# Anti-Sleep-Alarm
An Anti-Sleep Alarm System, is designed to improve road safety by detecting driver drowsiness in real-time. The system uses an IR-based eyeblink sensor to monitor eyelid activity and triggers alerts if prolonged eye closure is detected.

## Features

- Real-Time Drowsiness Detection: Monitors eyelid closure using an IR sensor.
- Alert Mechanism: Activates a buzzer and controls a motor based on eye closure duration.
- Time-Based Actions:
  - 3 seconds: Buzzer sounds to alert the driver.
  - 4 seconds: Motor shuts off, simulating vehicle halt.

## Hardware Requirements

- IR Sensor  
- Buzzer  
- Motor  
- Arduino Microcontroller

## How It Works

1. The IR sensor continuously monitors eyelid activity.
2. If eyes are closed for 3 seconds, the buzzer alerts the driver.
3. If eyes remain closed for 4 seconds, the motor turns off.
4. The system resets when the driver’s eyes reopen.

## Setup Instructions

1. Connect hardware components as per the provided code:
   - sensorPin: Pin 2  
   - buzzerPin: Pin 9  
   - motorPin: Pin 8  
2. Upload the Arduino code to the microcontroller.
3. Power the system and begin monitoring.
