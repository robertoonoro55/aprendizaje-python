# Challenge 001: Updating Python Version in Windows 11

## Problem
The system was showing Python 12.4 instead of the desired version 11.9.

## Solution
1. Press Windows + X and select "System"
2. Scroll down in the left panel and click on "Apps"
3. In the Apps window, click on "Installed Apps"
4. In the list of installed applications:
   a) If you see Python 12.4, select it, click on the three dots on the right, and select "Uninstall"
   b) Verify if Python 3.11.9 (64-bit) is in the list of apps
5. Close all windows to save the changes
6. Restart any open command window for the changes to take effect

## Verification
1. Press Windows + X and select "Terminal" (Command Prompt)
2. Type the following: py --version
3. The result should be: Python 3.11.9

## Notes
- This process is specific to Windows 11
- The steps differ slightly from general guides for earlier Windows versions
