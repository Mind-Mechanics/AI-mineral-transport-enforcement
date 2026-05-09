# AI-mineral-transport-enforcement

## The Problem
In Kerala ( A state In India ) Sheer volume of transport assets passes through the Borders of the State. The Officers cannot manually check each one of them, and the illegal vehicles can also use unautherised bypass routes 

## The Prototype Automation Chain
This prototype demonstrates a localized hardware-to-software automation loop designed to eliminate manual intervention:

1. A Mineral loaded vehicle approaches the automated checkpoint
2. The vehicle's Unique Digital permit is scanned using MFRC522 sensor instantly.
3. A microcontroller processes the ID and triggers a high-torque servo motor to automatically position the AI Camera its holding.
4. An active processing link on the central laptop captures a real-time snapshot and logs the transaction data instantly.
