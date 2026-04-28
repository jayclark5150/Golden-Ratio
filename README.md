# Coffee Ratio Calculator

A simple iOS Shortcut designed to calculate brewing ratios for coffee. It allows users to determine the relationship between coffee grounds and water volume to ensure a consistent brew.

## Features

- Dual Input Modes: Calculate based on either grams of coffee or milliliters of water.
- Precision Ratios:
    - Uses a 1:15 ratio when calculating from coffee weight (Grams x 15).
    - Uses a 1:16 ratio when calculating from water volume (Milliliters / 16).
- Fast Output: Displays the calculation result instantly via system alerts.

## Installation

1. Ensure the Shortcuts app is installed on your iOS device or Mac.
2. Download the .shortcut file from this repository or use the provided iCloud share link.
3. If prompted, allow the shortcut to run by enabling "Allow Untrusted Shortcuts" in your system settings (if applicable).

## Logic Flow

The shortcut utilizes a Choose from Menu action with two distinct paths:

1. Grams of Coffee
    - Prompts for numerical input (grams of beans).
    - Multiplies the input by 15.
    - Shows the result for the target water weight.

2. Milliliters of Water
    - Prompts for numerical input (milliliters of water).
    - Divides the input by 16.
    - Shows the result for the target coffee weight.

## Requirements

- iOS 15.0 or later / macOS Monterey or later.
- Shortcuts App.
