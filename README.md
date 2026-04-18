Phasmophobia Evidence Tracker (PET)

This is a simple console app written in Python for tracking evidence and identifying ghosts in Phasmophobia. It runs in the terminal so it doesn't take up much screen space.

Features:

Add evidence quickly using simple keys (b = spirit box, e = emf, f = freezing, etc.)

Automatically filters and shows possible ghosts based on your current evidence

Identifies the ghost immediately once enough evidence is gathered

Ghost lookup: you can check the required evidence for any ghost if you forget. You don't have to type the full name, just a part of it works (like mimic, twins, etc.)

You can clear all evidence for a new contract or delete a specific one if you made a mistake

How to run it:
You only need Python 3 installed. There are no external libraries to download.
Just download the files, open your terminal in that folder and run:
python main.py

Note: The script creates and deletes two temporary text files (GhostEvidenceFile.txt and InputEvidenceFile.txt) in its folder to handle the logic.

How to use:
Just follow the menu. Press the corresponding number or letter and press Enter.
If you need to delete a specific piece of evidence you accidentally added, select option 2 and type it with a space, for example "2 b" to remove spirit box or "2 d" to remove dots.
