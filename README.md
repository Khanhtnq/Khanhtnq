# Khanh Tran (`@Khanhtnq`)

**Compiler & Systems Engineering ? Distributed Runtime Architecture ? Protocol & Smart Contract Security**

---

### Core Engineering Focus
- **Compilers, Static Analysis & Language Runtimes**: `Rust`, `Go`, `C++` ? type-checker soundness, borrow/loan escape analysis, AST/SSA code generation, and differential fuzzing oracles.
- **Distributed Systems & Observability**: `TypeScript`, `Go`, `Temporal`, `OpenTelemetry`, `Podman/Docker`, `WebGL2` ? deterministic workflow replay, OTLP span pipelines, rootless container engines, and high-throughput 60 FPS graph visualization.
- **DeFi & Smart Contract Security**: `Solidity`, `Foundry`, `EVM` ? ERC-223 / Uniswap V3 pool validation, router fund-loss prevention, options accounting, and cross-chain allowance hardening.

---

### Selected Open-Source Contributions & Landings
- **Hybrid Compiler (`limitlessprojects/Go-Hybrid`)**:
  - **Merged (`#648`)**: Implemented `[N]T{...}` and `[...]T{...}` fixed-size array composite literals across `hy-syntax`, `hy-check`, and `hy-emit`.
  - **Merged (`#641`)**: Preserved `make`/`new` type shapes, validated closure builtins, and enforced forward file-level constant checking (`HYB-E6003`).
  - **Merged (`#559`)**: Closed `O8` map-slot loan sibling-branch handoff and shadowing binder last-use soundness gaps in `hy-emit`.
  - **MOONSHOT Ledger Intake `W-023` (`#577`)**: Designed and built the Go toolchain differential oracle (`INVARIANT 4`) and M1/M2 seeded Go-decidable fuzzing harness (`hyfuzz`).
  - **Pareto Land Candidate (`#591`)**: Closed constant-folding, type-alias, and slice/index/`make` bound soundness gaps across `HYB-E6001`?`HYB-E6005`.
- **SpaceApp Distributed Stack (`oll4com/spaceapp`)**:
  - **OTLP Telemetry (`#145`) & Deterministic Replay (`#150`)**: Exported Temporal workflow/activity spans over OTLP and gated deterministic workflow replay on the time-skipping test server.
  - **WebGL2 3D Memory Graph (`#152`) & Container Runtime (`#144`, `#146`, `#148`)**: Built a 50k-node 60 FPS WebGL2 renderer, rootless Podman support, and multi-stage runtime image budgets.
- **Protocol Security (`EthereumCommonwealth/Dex223-contracts#114`, `useverdex/verdex#9`)**:
  - Prevented canonical pool hijacking and ERC-223 router fund loss; hardened partial swap fills, options accounting, and multi-chain transaction allowances.
