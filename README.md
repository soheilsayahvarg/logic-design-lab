# Logic Design Lab — Sharif CE

Reports, pre-reports, Fritzing breadboard layouts, and Proteus simulations for all ten
sessions of the Logic Design Lab (آزمایشگاه مدار منطقی), Sharif University of
Technology, Spring 2024.

Published so the next people taking this lab have something to compare against. Reports
are in Persian.

**Use this to check your own work, not to replace it.** These reports are graded on
your own measurements, and the lab staff have seen these files. Copying them is
plagiarism and easy to catch.

Work by **Soheil Sayah Varg** and **Amirhossein Mousavifard**.

---

## The sessions

| # | Topic | ICs used |
| ---: | --- | --- |
| 1 | Gate transfer characteristics — measuring V-I and V-O curves | — |
| 2 | Fan-out and loading, driving successive NAND stages | 7400 |
| 3 | Clock generation with a 555 timer | 555, 7404 |
| 4 | Shift registers, multiplexers, decoders, flip-flops | 7495, 74173, 74153, 74154, 7432, 7408, 7404, 555 |
| 5 | Counters built from JK flip-flops | 74107, 74109, 74157, 7404, 7408, 7409, 7421, 7432 |
| 6 | Counter-driven control circuit (water/door application) | 7493 |
| 7 | Queue behaviour with a counter and multiplexer | 7493 |
| 8 | Register and ALU | — |
| 9 | Stack — pointer with up/down control, empty and full flags | 74153 |
| 10 | Multiplexer and flip-flop combinations | 74153, 7474, 7476 |

Session 1 has no pre-report; sessions 8, 9, and 10 have pre-reports only.

## What is in each folder

```text
<session>/
├── Pre-Report/
│   ├── Pre-Report.docx / .pdf
│   ├── Fritzing/*.fzz          breadboard layout per question
│   └── Proteus/*.pdsprj        simulation per question
└── Report/
    ├── Report.docx / .pdf
    └── Proteus/, Fritzing/     as above
```

Files are named after the question they answer — `a.fzz`, `c.pdsprj`, and so on — so
they line up with the parts in the lab manual. Session 1 also has `Oscilloscope.docx`
with the scope traces, and session 2 has `Data.xlsx` with the fan-out measurements.

## Software you will need

- **Fritzing** for `.fzz` breadboard layouts. It is paid on the official site but builds
  from source, and older releases are freely available.
- **Proteus** for `.pdsprj` simulations. Version matters — an older install will refuse
  a project saved by a newer one.
- **Word** or any `.docx` reader; every report also has a PDF if you only want to read
  it.

`logic-lab.pdf` is the official lab manual (prepared by the late Eng. Haideh Motevalli,
revised by Dr. Hossein Asadi).

## A note on the measurements

Sessions 1 and 2 are measurement labs — transfer characteristics and fan-out — and the
numbers depend on your particular ICs, your power supply, and your scope. Your curves
will not match these exactly, and they are not supposed to. If yours are wildly
different, that is worth investigating before you assume one of us is wrong.
