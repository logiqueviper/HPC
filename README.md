# Dispatch Cost and Mechanism Activation in Wireless Chunk Scheduling

- [Download the complete ZIP](HPC_SimPy_Research_Artefact.zip?raw=true)
- [Read the IEEEtran manuscript](IEEE_Journal_Manuscript.pdf)
- [Read the supplement](Participation_Aware_Scheduling_Supplement.pdf)

The ZIP contains simulation source, raw evaluation and calibration records,
analysis, vector plots, LaTeX, tests, reproduction scripts and a file-hash manifest.
The current study has 22,400 completed evaluation runs, 1,960 independent tuning
runs, 190 stationary ns-3 radio trials and 46 passing implementation/inference tests.
Paired Student inference covers 77 difference and 77 equivalence hypotheses.

Modeled serialized dispatch cost is swept from 0 to 20,000 ms, with fixed-size
selection repeated independently at each point. At 5,000 ms the full policy gains
1.26% over retuned fixed chunks; at 20,000 ms it loses 32.10%. Core and activation
results are mixed. High costs and injected delays are sensitivity assumptions,
not measured production overhead. No physical-device validation, faithful complete
mobile-framework reproduction or universal scheduler-superiority claim is made.

This branch distributes research files; it is not a DOI-bearing archival deposit.
Author/funding/conflict/license confirmation, independent USENIX publisher checks,
and authenticated archival publication remain documented in the ZIP. No journal
submission or acceptance is claimed. Historical papers inside the ZIP are provenance;
the two top-level PDFs are the current outputs.

ZIP SHA-256: `166e9edad550581655b3466501ac21d830f064035e8a31c98a046cdcfc67aa6b`.
