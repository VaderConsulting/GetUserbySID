# GetUserbySID

CSC VB6 Logon 3.2 background process (`Logonsvr32.exe`, project title Users & Groups) that walks domain SAM/Active Directory users via Active DS, reads each member `objectSID`, and reports new vs changed accounts. UI caption "Logon 3.2 Background Process"; any command-line switch runs a one-shot pass instead of the continuous loop.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `GetUserBySID` (`GetUserbySID.vbp`) | VB6 | WinForms exe | Domain user SID scan / logon background process |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `GetUserbySID.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Active DS Type Library (`activeds.tlb`)

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Old/GetUserbySID`.
Company names in project files: CSC.

## License

MIT (c) 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
