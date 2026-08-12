# CDI / Spark Unit Diagnostics And Setup

## 1. First Rule

Do not start by blaming the spark units.

On this platform, "bad CDI" symptoms are often caused by:

- low battery voltage during cranking;
- poor ground paths;
- corroded connectors;
- weak pulse generator output;
- a bad coil, plug cap, or HT lead;
- old kill-switch or ignition-switch contacts.

## 2. Common Failure Patterns

### One cylinder pair drops out

Most useful suspects:

- one spark unit;
- the pulse generator circuit feeding that spark unit;
- the coil serving that pair;
- connector or harness damage specific to that pair.

### Misfire gets worse when hot

Most useful suspects:

- a spark unit breaking down with temperature;
- pulse generator resistance drifting when hot;
- connector resistance rising with heat;
- a weak charging system causing low running voltage.

### Tachometer behaves strangely with rear-bank spark problems

The local forum references and collected notes repeatedly connect tachometer behavior with rear-bank ignition faults. That is a useful clue, not proof by itself.

## 3. Practical Diagnostic Order

Use this order before buying parts.

1. Confirm battery condition and cranking voltage.
2. Confirm clean grounds between battery, frame, and engine.
3. Confirm switched ignition power reaches both spark units during cranking and running.
4. Measure both pulse generators against spec.
5. Check coil primary and secondary resistance against the ignition manual.
6. Inspect plug caps, HT leads, and connectors for cracking or corrosion.
7. Check ignition timing with a strobe.
8. Only then condemn a spark unit.

## 4. Fast Isolation Logic

If the bike runs on only one cylinder pair:

- identify whether `1-3` or `2-4` is dead;
- compare pulse generator resistance between the pairs;
- compare coil feed and spark output between the pairs;
- if the two spark units share the same part number and connector format, swap them and see whether the fault follows the box.

If the fault moves with the box, the box is the prime suspect.

## 5. Timing-Light Check

For a stock-style system, the timing-light check is the real setup procedure.

Target checkpoints for the early `750 Sabre`:

- `10° BTDC` at idle;
- full advance at `37° BTDC` by `3,300 rpm`.

If timing is unstable, late, or asymmetric between the two cylinder pairs, check:

- pulse generators;
- spark units;
- rotor / trigger condition;
- harness voltage drop;
- grounds.

## 6. What "Setup" Means On This Bike

For stock spark units, setup does not mean editing a map. It means:

- clean power and grounds;
- healthy pulse generators;
- healthy coils;
- correct static wiring;
- timing marks verified with a strobe.

That is the correct baseline before any modern ignition conversion.

## 7. Before Any Replacement Ignition

Do these first:

- fix charging issues;
- clean all ignition connectors;
- verify pulse generator resistance cold and, if possible, hot;
- verify the bike has the correct coils and plug caps;
- get the carbs and valve clearances right.

If the engine has mechanical or fuel-system problems, no ignition box will tune around them cleanly.
