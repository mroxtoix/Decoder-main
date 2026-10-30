

An advanced analysis tool designed to decrypt and extract configuration data from xWorm RAT samples efficiently.

## How It Works / Workflow
1. **Analyze via dnSpy:** Open the target payload inside **dnSpy** to inspect classes, methods, and encrypted strings (such as Mutex, Hosts, Ports, and Keys).
2. **Run Decoder Tool:** Launch the **RatDecoder** tool and provide the Mutex.
3. **Decrypt Data:** Input the encrypted strings sequentially to instantly decode and reveal the raw C2 configuration parameters.

## Tool Preview
![Tool Workflow Preview](screenshot.png)

---
Developed by darkness
