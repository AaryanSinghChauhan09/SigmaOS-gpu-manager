# SigmaOS-gpu-manager

SigmaOS integration component for **NVIDIA settings**.

## Commands

```bash
sigmaos-gpu-manager install   # install package + deploy defaults
sigmaos-gpu-manager deploy    # copy config templates to $HOME
sigmaos-gpu-manager status    # binary/package/config report
sigmaos-gpu-manager reset     # remove deployed config
sigmaos-gpu-manager open      # launch the application
```

## Design

- Shell-based component manager (Omarchy-style per-app repos)
- Secure defaults; no secrets stored
- Deterministic `test.sh` with isolated `$HOME`
