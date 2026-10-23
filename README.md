# bitClear filter lists

Signed filter-list feed for [bitClear](https://pocketbitsllc.com/), a Safari ad blocker by Pocket Bits LLC.
The app downloads `v2/latest.json`, verifies its Ed25519 signature (`latest.json.sig`) and every list's SHA-256,
and only installs versions newer than the one it has.

The lists are converted to Safari's content-blocker format from these sources. Each list keeps its own licence,
and the converted lists here are distributed under the same terms. Attribution and source versions for every
list are in `v2/latest.json`.

- EasyList and EasyPrivacy, the EasyList authors (https://easylist.to/): CC BY-SA 3.0
- Fanboy's Annoyance List, including the EasyList Cookie List: CC BY 3.0
- Regional lists: see each entry's `license` and `attribution` in `v2/latest.json` (CC BY 3.0, CC BY-SA 3.0/4.0, or Unlicense)

Rebuilt about twice a week. This branch is replaced on every publish; older versions aren't kept.
