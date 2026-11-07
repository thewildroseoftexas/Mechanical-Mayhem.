MECHANICAL MAYHEM V30 - FULLSCREEN CIPHER TEST

Upload index.html and workshop.png to the same GitHub Pages test repository.

V30 fixes the Android fullscreen top-layer issue by placing the Cipher Engine
inside the fullscreen workshop element, so it is visible immediately when the
five-second tower balance test completes. No need to exit fullscreen.

Only the cipher presentation/transition was changed. The V28 mobile cipher
layout, V27 small question marks, approved physics, artwork, cipher logic,
and restart behavior are preserved.

TEST:
1. Enter Full Screen on phone and stack/confirm the correct five pieces.
2. After five seconds, Cipher Engine should appear immediately in Full Screen.
3. Confirm cipher panels scroll and controls work.
4. Start Entire Mystery Over: verify workshop and all eight items reset.
5. Complete a second tower in Full Screen; cipher should appear again.
6. Optional: exit Full Screen while cipher is open and verify it stays visible.

If it still fails, please report whether you are in Full Screen and whether
the engine appears after using the phone Back button.
