# ci-smoke-lab-9
Throwaway sandbox for end-to-end CI + contribution flow smoke test

## Build artifact

This repo uploads a short text file (`artifact.txt`) as a GitHub Actions build artifact named exactly `demo-build`, produced by the CI workflow's `demo-build` job via the `actions/upload-artifact@v4` action.
