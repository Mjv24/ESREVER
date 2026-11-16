# ESREVER

A reverse singing party game for friends. One file, no server, runs on GitHub Pages.

## Play
1. Upload `index.html` to a repo and enable GitHub Pages.
2. Open the page, tap **Create room**, and share the code or invite link.
3. Friends join from their own devices. **Practice solo** works too.

## How a round works
1. The singer records a short clip.
2. Everyone else hears it backwards and imitates that sound.
3. Each attempt is flipped back to normal and compared with the original.
4. Everyone can replay all attempts on the results screen. Players take turns singing, then the final ranking shows.

## Scoring (0 to 100)
- **Match**: how close the flipped attempt sounds to the original.
- **Accuracy**: pitch plus timing. Pitch ignores vocal range, and is skipped for speech.
- **Total**: 60% match, 40% accuracy. The singer earns a clarity bonus of 40% of the average guesser score.

Tune the constants in the `TUNE` block of `index.html`.

## Tips
- Use headphones so the mic does not hear the playback.
- The mic needs https, which GitHub Pages provides.
- The host must keep their tab open. Rooms connect peer to peer through PeerJS.
