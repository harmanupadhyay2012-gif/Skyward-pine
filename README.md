
# Skyward Recovery for Redmi 7A (pine)

> **Status: Experimental / Work in progress. Not ready to flash.**

This project investigates porting Skyward Recovery 0.3.1 to the Xiaomi Redmi 7A.

## Target device

- Device: Xiaomi Redmi 7A
- Codename: `pine`
- Platform: `mi439`
- Variant: India
- Firmware reported: MIUI 12.5.1 India
- Android version: Android 10

## Project goal

Prepare and investigate a device-specific Skyward Recovery port for Redmi 7A.

## Current progress

- [x] Target device identified
- [x] Skyward Recovery 0.3.1 source obtained
- [ ] Verify compatible recovery kernel
- [ ] Prepare device configuration
- [ ] Verify partition layout and fstab
- [ ] Inspect vendor dependencies
- [ ] Build recovery image
- [ ] Validate image
- [ ] Test on Redmi 7A

## Important compatibility note

The stock recovery kernel has been reported as 32-bit ARM, while the Skyward build configuration appears to target ARM64. This compatibility issue must be resolved before building.

The complete vendor image has not yet been inspected.

## Safety warning

**Do not flash an unverified image.**

A recovery image built for the wrong kernel, partition layout, or device variant can cause boot failure. Keep a verified stock firmware package and backups before testing.

## Disclaimer

This is an unofficial experimental project. It is not affiliated with Xiaomi or the Skyward Recovery developers.
