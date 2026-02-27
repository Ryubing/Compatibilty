# Contributing

Hey, thanks for taking the time to read the contribution guidelines! We're happy you're interested in helping out.

For this repo, we accept two types of pull requests: CSV and RPC.

## CSV

For CSV type requests, you'll be modifying the [compatibility.csv](https://github.com/Ryubing/Compatibilty/blob/main/compatibility.csv) file. All entries are alphabetical based on the game name, and are required for compatibility reporting within the emulator.

A standard entry will look like this:

``Title ID,"Name of The Game",report;tags,utc timestamp``

Here's an example using _The Legend of Zelda: Tears of the Kingdom_.

```csv
0100F2C0115B6000,"The Legend of Zelda™: Tears of the Kingdom",gpu;amd-vendor-bug;intel-vendor-bug;mac-bug,ingame,2024-08-24 12:38:30
```

<img width="868" height="75" alt="image" src="https://github.com/user-attachments/assets/b7e5605f-b05e-4e0e-8323-2715059a0e16" />

For issues that are marked "not-in-csv", that means that the title reported in the issue is not in this database, and is an ideal candidate for a pull request.
Note that you should NOT include "not-in-csv" as a label when making a pull request to add the title to the database.

If you are updating a title within the database, please update the UTC timestamp.

## RPC

For RPC type requests, you will be uploading an image to the ``logos`` folder.

This image is extracted from the game by right-clicking the game within the main menu and selecting "Extract Data" -> "Logo".
When uploading this image, please make sure that the image is titled with the title ID (this should be the default when saving from Ryubing).

<img width="795" height="233" alt="image" src="https://github.com/user-attachments/assets/9a4c58b2-4f80-4a61-8a70-7cbcfb4409d3" />
