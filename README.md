# FSL Online Saves

Client and server for storing local FSL saves for GTA Online.

Adding money to GTA Online and local saves allowing you to bypass the ban. More details: http://fsl.pythonanywhere.com

## Installation

> [!WARNING]
> **For GTA V Enhanced and GTA V Legacy (latest versions)**, use [WINMM.dll](FSL/WINMM.dll)
>
> [version.dll](FSL/version.dll) is outdated and may not work with newer game versions.

Copy [WINMM.dll](https://github.com/isamo09/fls-online-saves/raw/main/FSL/WINMM.dll) to the root folder of the game (where GTA5.exe is located).

## Money Cheats

Press `~` in GTA Online session to open console, then enter a cheat code:

| Cheat Code | Amount Added |
|------------|--------------|
| `1M` | $1,000,000 |
| `2M` | $2,000,000 |
| `10M` | $10,000,000 |
| `100M` | $100,000,000 |
| `1B` | $1,000,000,000 |
| `10B` | $10,000,000,000 |

## Downloads

- [WINMM.dll](https://github.com/isamo09/fls-online-saves/raw/main/FSL/WINMM.dll) - For latest GTA versions (Recommended)
- [version.dll](https://github.com/isamo09/fls-online-saves/raw/main/FSL/version.dll) - Old version
- [Save Manager](https://github.com/isamo09/fls-online-saves/releases/latest/download/main.exe) - Cloud save manager
- [Clean Save](https://github.com/isamo09/fls-online-saves/raw/main/FSL/clear_saves.zip) - Extract to `%AppData%\FSL` if blocked

## How It Works

FSL redirects save requests from Rockstar servers to local files. All save data is stored in `%APPDATA%\FSL`.

> [!NOTE]
> You can't be banned because your saves never reach the Rockstar servers.

> [!TIP]
> Maintain your own backups - everything in `%APPDATA%` will be wiped during a Windows reset.
