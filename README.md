Interval Identifier (Max for Live)

Audio effect that detects incoming pitch and displays:
- The detected note name (C–B)
- The interval name relative to a selected key

It uses fzero~ for pitch detection, maps the pitch class to a note name, and maps the interval to a readable label (e.g., minor 3rd).

Binary header note

.amxd files are JSON with a binary header/footer. If the JSON length changes, the `ptch` chunk size in the header must be updated to match the current JSON payload length (plus any trailing bytes). A mismatch can cause Ableton/Max to report “Device file broken.” LLMs will need to know this context when building Max for Live devices.
