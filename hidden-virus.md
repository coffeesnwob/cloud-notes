# Hidden Virus

This virus hides your documents in a flash drive. It often changes your document’s attributes, making them “hidden” or “system” files. To remove this virus you have to do the following steps:

1. Open the Command Prompt
	- Press `Win + R`, type `cmd`, and hit Enter

2. Navigate to your flash driveL
	- Type `E:` (replace `E:` with your flash drive’s letter) and press Enter.

3. Run the following command to unhide files:

```powershell
attrib -h -r -s /s /d *.*
```

- `-h` removes the hidden attribute.
- `-r` removes the read-only attribute.
- `-s` removes the system file attribute.
- `/s` applies to all files in subdirectories.
- `/d` applies to directories.

## Backup Your Data

After recovering your documents, back them up to a safe location then format your flash drive to ensure the virus is completely removed:

- Right-click the drive in File Explorer > Select Format > Choose Quick Format.

## How to prevent future infections?

1. Avoid using your flash drive on untrusted computers.
2. Disable autorun for external drivers:

	- Open `gpedit.msc` > Navigate to _Computer Configuration > Administrative Templates > Windows Components > AutoPlay Policies_ > Enable _Turn off AutoPlay_.

3. Keep your antivirus software updated.

---
