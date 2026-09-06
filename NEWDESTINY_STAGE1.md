# New Destiny Stage 1

Branch: `newdestiny-stage1`

Purpose: build the original TMProject2GlobalClient source as a clean Win32/x86 Release baseline before protocol adaptation.

Stage 1 rules:
- no New Destiny binary patching
- no VM detection/blocking code added
- use the upstream client source as baseline
- first validation target: application starts and reaches the login screen when placed with the required WYD client data files

Next stages will compare this clean build against the existing New Destiny client for file dependencies, login/handshake, packet encoding/decoding, structures and opcodes.
