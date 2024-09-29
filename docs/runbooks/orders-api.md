# Runbook: orders-api

If orders fail after a deployment, revert the change on `main`; the deploy workflow
redeploys the reverted version.
