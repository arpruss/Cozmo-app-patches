Patches for Cozmo Android app 3.6.6 or 3.6.9

1. Copy /sdcard/Android/data/com.digitaldreamlabs.cozmo2 [3.6.6] or /sdcard/Android/data/com.anki.cozmo2 [3.6.9] from your Android devices to your computer.

2. Make a backup copy.

3. Put scratch.diff in the com.digitaldreamlabs.cozmo2 or com.anki.cozmo2 directory.

4. Run: patch -p1 < scratch.diff


Current patches:

 A. Long-tap green flag in constructor mode runs in turbo mode with no block highlighting.
 
 B. Long-tap of blocks in constructor mode pops up a context menu with options to duplicate, delete or comment.