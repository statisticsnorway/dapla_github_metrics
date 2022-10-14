# dapla_github_metrics

Collect metrics on use of Dapla from SSB's Github.

Uses an internal SSB config file as a source, so will only work for those in SSB's Github organisation

---

## To run on Dapla

- `git clone https://github.com/statisticsnorway/atlantis-team-config.git`
- `git clone https://github.com/statisticsnorway/dapla_github_metrics.git`
- `cd dapla_github_metrics`
- `ssb-project build`
- Open `src/notebooks/number-of-teams.ipynb`
- Select the `dapla_github_metrics` kernel
- Run all the cells
