# SM Space Saver

SM Space Saver is a lossless pre-compression layer designed for conversational text.

It works alongside existing compression systems such as gzip and zstd, helping recover additional storage space before traditional compression is applied.

## Features

- Lossless
- Exact rebuild
- Fixed dictionary design
- Optimised for conversational text
- Compatible with gzip and zstd
- Simple by design (KISS)

## Current Results

| Test | Result |
|--------|--------:|
| SM Space Saver Alone | ~14% |
| Additional Gain After gzip | ~1.5 percentage points |
| Rebuild Accuracy | 100% |

## Philosophy

In a world of data, every bit counts.

SM Space Saver does not replace existing compression systems.

It simply finds a little more space before they do their work.

## Status

Current Version: 1.0

Created by Stuart Camilleri

SBB Compression
