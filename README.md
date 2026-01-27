// RTC DS1307 demo code for Arduino Data Logger Shield or any RTC DS1307 compatible module

// RTC Without Battery
// - RTC not running
// - Every compilation and upload update the datetime setting based on your computer time
// - Every USB power reset will reset the RTC datetime of the last compilation computer time

// RTC With Battery
// - RTC running since last reset and compilation computer time
// - Every compilation and upload will not change the RTC running time but will update the datetime setting based on your computer time

// RTC setting procedure
// 1. Ensure RTC board in connected to Arduino properly
// 2. Remove RTC Battery to ensure RTC is not running
// 3. Compiled and upload datetime setting based on your computer time
// 4. Remove and insert USB power to hard reset your Arduino
// 5. Insert RTC Battery to ensure RTC continue to run even USB power is remove
