# Homebrew Tap

Homebrew formulae for [KubeWise](https://github.com/tochemey/kubewise) — the Kubernetes cost and performance "what-if" simulator.

## Installation

```bash
brew install tochemey/tap/kubewise
```

## Available Formulae

| Formula            | Description                                          |
|--------------------|------------------------------------------------------|
| `kubectl-whatif`   | Kubernetes cost and performance what-if simulator    |

## Usage

Once installed, use `kubectl whatif` to snapshot your cluster, simulate changes, and see cost impact:

```bash
kubectl whatif snapshot
kubectl whatif rightsize
kubectl whatif consolidate --node-type=m6i.xlarge
kubectl whatif spot
```

For full documentation, see the [KubeWise README](https://github.com/tochemey/kubewise).

## License

Apache License 2.0. See [LICENSE](LICENSE) for details.
