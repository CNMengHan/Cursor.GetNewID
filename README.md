# Cursor.GetNewID

**Description:**  
Cursor.GetNewID is a program that modifies the `storage.json` configuration file located in the following directory:  
`%APPDATA%\Cursor\User\globalStorage\`  
The program generates new unique identifiers for the following telemetry fields:  
- `telemetry.machineId`  
- `telemetry.macMachineId`  
- `telemetry.devDeviceId`  
- `telemetry.sqmId`  

By modifying these fields, this program allows you to obtain trial permissions or reset user-specific data associated with the Cursor application.

**Important:**  
The program must be run with **administrator privileges** in order to modify the `storage.json` file and update the telemetry data.

---

## Installation

1. Clone or download this repository to your local machine:
   ```bash
   git clone https://github.com/CNMengHan/Cursor.GetNewID.git
   ```
2. Navigate to the repository folder and run the program:
   - On Windows, ensure you're running the program as Administrator.

---

## Usage

1. Locate the `storage.json` configuration file on your machine:
   ```text
   %APPDATA%\Cursor\User\globalStorage\
   ```
2. Run the `regsvr32.exe` program as an administrator.
3. The program will generate and update the following identifiers in the `storage.json` file:
   - `telemetry.machineId`
   - `telemetry.macMachineId`
   - `telemetry.devDeviceId`
   - `telemetry.sqmId`
   
4. After running the program, you should have the necessary identifiers for trial permissions or resetting user-specific configurations in the Cursor app.

---

## Requirements

- **Administrator privileges** are required to run the program and modify the `storage.json` configuration file.
- The program is compatible with Windows operating systems.
