# sampleNod
A SampleNod project to test basic cases for a single build.

## Run CI for this repo on Shippable

Test Cases that are covered in CI build triggering manually:


1. Valid languages and version.
2. Valid addons
3. User specified environment variables in global tag.
4. Secure environment variables(encrypting from shippable UI)  in global tag.
5. User specified environment variables in matrix tag.
6. Make sure whether pre_ci envs carrying over to pre_ci_boot section
7. Include(only) tags for master branch.
8. Exclude(except) tag for non master.
9. Using wildcard in branches tag(only) in integrations.
10. Private submodules are enabled.
11. Docker build and push
12. GCR build and push
13. Quay.io build and push
13. ECR build and push
14. Build status(waiting,proccessing,success).
15. Verify the status badge in UI

Test Cases that are covered on triggering a webhook build:
