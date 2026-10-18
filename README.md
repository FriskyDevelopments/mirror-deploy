# mirror-deploy
Dual-builder mirror deployment pipeline: two builders execute the same map in parallel on OpenShift, diff their outputs, and only promote to prod when the diff is empty. Includes log comparison for diagnosing builder divergence.
