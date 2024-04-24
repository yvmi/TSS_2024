# How to get started with your Vision Kit?
## Vision Kit Setup
1. Connect the battery bank to your Raspberry Pi.
2. Using a HDMI to micro HDMI adaptor. Connect your Raspberry Pi to a screen
4. Connect a keyboard using one of the USB ports of the Raspberry Pi

## Connect to WiFi
1. Run the following command
```
   sudo raspi-config
```
2. Insert the Network ID and password.
3. Press Finish

Note: Make sure that you connect your Raspberry Pi to the same Network as your TSS

## Run the Vision Kit
1. Make sure you run your TSS using the ```./server.exe --public``` command
2. Change to the TSS directory using
   ```
   cd TSS_Client
   ```
3. Now to run the Vision Kit you run the following command
```
npm start [TSS IP]
```
4. Check your TSS the Position data for EV1 should be updating 

## Considerations
**1. Type error after running Vision Kit**

This means that the GPS is failing to retrieve data. Usually the **Fix** light will be blinking fast as well

**How to fix it?**
- Let the Vision Kit sit outdoors or near a window until the light stops blinking or slows down. (this can take anywhere from 10 to 3 hours)
- Then connect it back to the Monitor and keyboard
- And try to start the Vision Kit again

**2. The Vision Kit data displays X and Y data in relation to the center of the Rockyard**
