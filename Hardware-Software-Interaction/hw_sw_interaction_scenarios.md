# Hardware–Software Interaction Scenarios

## Normal Interaction Scenarios
- Driver correctly detects hardware
- Register reads/writes are accurate
- Status and health signals are consistent

## Degraded Interaction Scenarios
- Partial hardware availability
- Intermittent communication
- Delayed responses

## Fault Interaction Scenarios
- Device disconnected during operation
- Power interruption to hardware
- Incorrect wiring or signal noise

## Expected System Behavior
- Driver reports hardware state accurately
- No system crash or undefined behavior
- Safe fallback or error reporting

## Senior Insight
In embedded systems, hardware failures are normal.
What matters is **how software behaves when hardware misbehaves**.
