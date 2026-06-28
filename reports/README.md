# reports/

Final, clean, human-readable, **actionable** outputs that Claude Code writes
for you live here — polished deliverables (triage summaries, security reports,
decision write-ups), not machine artifacts or working files.

Separation of concerns (all three are gitignored):

| Folder      | Holds                                                    |
|-------------|----------------------------------------------------------|
| `out/`      | RAPTOR run artifacts — JSON, SARIF, machine-readable      |
| `scratch/`  | copied-over repos, triage notes, ad-hoc/in-progress work  |
| `reports/`  | final human-readable deliverables (this folder)           |

Everything in this folder is gitignored **except this README**, so private
report contents never land in version control. Claude writes its final,
cat-ready summaries here; check this folder for the clean version of a run's
output.
