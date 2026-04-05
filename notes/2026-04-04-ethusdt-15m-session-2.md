# Session Note

**Date:** 2026-04-04
**Symbol:** BINANCE:ETHUSDT
**Timeframe:** 15m
**Task:** Re-check the current EMA 20 / 50 setup, make one very small Pine improvement, and keep a minimal replay review frame.

## Observation

Price is near 2050.74 on the 15-minute chart. EMA 20 is about 2051.43 and EMA 50 is about 2051.79. The chart still has EMA 20 / 50, CVD, and Volume loaded. Recent candles show movement on both sides of the EMA area, which still looks more like short-term testing than a clean directional move.

## Inference

The setup remains neutral. Price is close enough to the EMA cluster that the chart does not yet show a strong resolution in either direction.

## Hypothesis

If price can hold above the EMA area with cleaner closes, the setup would look more constructive. If it slips back under the EMA cluster and keeps failing there, the setup would look weaker.

## Pine change

Created EMA 20 / 50 overlay v2 with one small improvement: an optional source input. This keeps the script simple while making it easier to test the same overlay on inputs other than close.

## Compile result

EMA 20 / 50 overlay v2 compiled successfully with no errors and no warnings.

## Replay/review notes

Replay is available on the chart, but it is not actually started in this session. Review frame:
- note whether candles close above or below the EMA area
- note whether tests of the EMA zone hold or fail quickly
- note whether volume supports the move away from the EMA cluster

## Next step

Run one short replay check from a valid anchor and record whether price holds above or below the EMA area.
