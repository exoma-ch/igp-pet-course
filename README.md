# IGP — PET detector physics

Student materials for the ETH D-PHYS [In-Group Project][igp] on PET detector
physics. Over the block you characterise a small coincidence setup built from
SiPM arrays coupled to LYSO scintillators, then write a report and present a
poster.

## Downloads

Everything you need is attached to the **[latest release][latest]**:

| File | What it is |
|---|---|
| `manual.pdf` | The practicum manual: theory, setup, data acquisition, analysis and what goes in the report. Read it before your first lab day. |
| `analysis-kit.zip` | Your starting point for the analysis: the `igppet` helpers, the example notebooks and a project that installs them. Install [uv][uv], unzip it and run `uv run jupyter lab` in `igp-analysis/`. The manual's data analysis chapter explains the rest. |
| `igppet-*.whl` | The same helpers on their own, if you manage your Python environment yourself (Python 3.14). |
| `report-template.zip` | The [Typst][typst] template for your report. Unzip it and compile `report-template/report-template.typ`, or upload the folder to [typst.app][typst]. Using it is optional. |

Each cohort gets its own release. Older releases stay available, but use the
one your supervisor points you to.

No measurement data is distributed here: you take your own in the lab.

## Questions and corrections

Ask your supervisor. If you find a mistake in the manual, tell them, so the
next cohort gets a corrected version.

## License

The materials are licensed under [CC BY 4.0](LICENSE).

[igp]: https://igp.phys.ethz.ch/index.php?page=exp
[latest]: https://github.com/exoma-ch/igp-pet-course/releases/latest
[typst]: https://typst.app
[uv]: https://docs.astral.sh/uv/getting-started/installation/
