# xfstests-dash
An in-browser parser and visualizer for xfstests xunit output.
Based on https://github.com/lotterfriends/online-junit-parser by André Tarnowsky.

## Usage
Visit https://ddiss.github.io/xfstests-dash or clone this repository and open index.html in your browser.
Run xfstests with xunit results output, e.g. `./check -R xunit`.
Copy the `results/result.xml` output into the dashboard text input or use the file picker.

## Testing
Self-testing is handled by `test/selftest.js`. The tests are triggered on demand when the page is loaded via:
https://ddiss.github.io/xfstests-dash#__selftest
