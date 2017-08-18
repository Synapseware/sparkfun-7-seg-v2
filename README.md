SparkFun 7-Segment serial LCD v2
================================
https://www.sparkfun.com/products/retired/9765

# Description
We’ve overhauled this board adding I2C functionality, and Arduino bootloader and mounting holes! This page is for reference only.

The 7-Segment Serial Display turns the thirteen pins necessary to control a 4-digit seven segment display into just one or three. The display will give you full control of all digits, decimal points, the colon and the apostrophe. At the heart of the display is an ATMega328 which controls all the serial communications and the 4-digit 7-segment display through an easy to use API.

The Serial 7-Segment Display can be controlled in one of two ways: (1) serial TTL communication or (2) SPI serial communication. Regardless of which method you use to communicate with the display, the display is controlled with 4-byte packets and special 2-byte commands.

New for version 2: The input and power pins have been moved to the top of the display, allowing you to place the displays side-by-side. Additional characters have been added, including the “-”. A reset display command and single character control have also been added. See the new user’s manual below for detailed information about all of the new features!

## Features:

	* 4 digit blue alpha-numeric display with serial (1 pin) or SPI interface (3 pins)
	* Display numbers, most letters, and a few special characters
	* Individual control of decimal points, apostrophe, and colon
	* Selectable baud rate (2400 to 57600 bps)
	* Selectable brightness
    * Baud rate and brightness values retained in non-volatile memory
    * Individual segment control for each digit


