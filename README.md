Gas Lavel Detection and Automatic Booking :

The objective of this project is to monitor the gas level in the cylinder and automatically place an order for a new cylinder when the gas level drops below a certain threshold. For this, I utilized Arduino Uno, SIM900a, a load cell (HX711), and a display.

Here's how the project works:

1. Connect the weighing sensor to the Arduino using the provided cable.
2. Insert the power cable into the Arduino's port from a 12V adapter and switch it on.
3. Upon startup, it displays the project name and initiates calibration.
4. The display prompts to put 180 grams and wait. Once done, calibration completes in 3 seconds.
5. GSM initialization then starts, completing in 3 seconds as well.
6. Now, the system is ready. It displays the gas left percentage and weight.
7. If the gas percentage falls to 10%, a message is sent to the distributor.
8. Note that the percentage is measured up to 2 kg only.
9. If the weight exceeds 2 kg, it shows 100%, but the weight is accurately measured up to 20 kg.
10. Fix the weighing pan to the bench securely.

