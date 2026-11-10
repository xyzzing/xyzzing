## About
Strategy and transformation professional with 18 years across institutional
banking, sustainability and operations. My consistent pattern: I find where
management information or governance is missing, then build the process that
closes the gap. 

I also building open-source tooling for running AI locally on AMD hardware, and
I'm studying for the NTU FlexiMasters in Responsible Applied AI.

**Open to strategy and transformation roles anywhere**
linkedin.com/in/zacchen


## Open Source Mission
Make sophisticated tooling transparent, auditable and usable by organisations
without enterprise budgets. Today that means local AI agents you can measure
and govern: what a task costs in energy, whether the agent finished it, and
where its reasoning budget went.
- **Strata**: HIP/AMD contributions to a local large-model inference engine.
- **Sinter**: llama.cpp supervisor for AMD Radeon with energy telemetry and
  task-completion benchmarking.
- **Minder**: agent-governance tooling, evals first.
- Issues and PRs raised on PyTorch and AMD LLVM.


## The flight-test program

The mission above is one loop, several birds - the names are falconry: the
house keeps the birds, the falconer trains them, the tunnel measures the
flight. The public pieces:

- [minder](https://github.com/xyzzing/minder) - the tower: governed agent
  runtime (capture, memory, policy, operator console). Install and try-it
  in its README.
- [cupola](https://github.com/xyzzing/cupola) - the furnace + watch-dome:
  certify-before-serve and work backpressure above the engine.
- [windroos](https://github.com/xyzzing/windroos) - the rose: the repo
  agent, capturing lessons and charts from every run.
- [sinter](https://github.com/xyzzing/sinter) - the engine supervisor:
  deterministic llama-server lifecycle, admission checks, verifiable state
  on AMD Radeon.
- [Strata](https://github.com/xyzzing/Strata) - the inference engine fork
  this stack is measured on.

Private for now: the mews (contract-drift tripwires, full-loop shakedown,
program map), valkenier (training), windtunnel (measurement rooms).
