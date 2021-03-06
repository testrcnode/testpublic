[![Run Status](https://rcapi.shippable.com/projects/5902e82dbb7fa80500494a99/badge?branch=master)](https://rcapp.shippable.com/github/rc-testorg/coretest_orgpublicrepo) 

[![Coverage Badge](https://rcapi.shippable.com/projects/5902e82dbb7fa80500494a99/coverageBadge?branch=master)](https://rcapp.shippable.com/github/rc-testorg/coretest_orgpublicrepo)

PROD STATUS
[![Run Status](https://api.shippable.com/projects/59059dbb4ff18d070024ac63/badge?branch=master)](https://app.shippable.com/github/rc-testorg/coretest_orgpublicrepo)

[![Coverage Badge](https://api.shippable.com/projects/59059dbb4ff18d070024ac63/coverageBadge?branch=master)](https://app.shippable.com/github/rc-testorg/coretest_orgpublicrepo)


# coretest_singlebuildNod
A SampleNod project to test basic cases for a single build.


This project is enabled in `shiptest-rc-ow` account in shippable.


## Run CI for this repo on Shippable

Test Cases that are covered in CI build triggering manually:


1. Valid languages and version.
   - Triggers a single build with lang `node_js` having  version `0.10`
2. User specified environment variables in global tag.
   - Envs (eg: TEST=FOO) is specified in env tag.
3. Secure environment variables in global tag.
   - Encrypted from shippable UI and specified in env tag.
4. User specified environment variables in matrix tag.
5. Make sure whether pre_ci envs carrying over to pre_ci_boot section
   - IMAGE_TAG envs specified in pre_ci should be fetched in pre_ci_boot.

6. Include(only) tags for master branch.
7. Exclude(except) tag for non master.
8. Using wildcard in branches tag(only) in integrations.
9. Private submodules are enabled.
    - verify the gitsync step in console to verify the submodules are enabled.

10. Docker build and push(private image)
11. GCR build and push
12. Quay.io build and push
13. ECR build and push
14. Build status(waiting,proccessing,success).
15. Custom build( specify envs from UI(custom: foo)  and verify its taken to the build).
16. Rerun the custom build.It should run with the custom envs from the original build.
17. Key-value pair integration.
  - $key1 echoes `value1` and $key2 echoes `value2` as these are the values integrated from account integration.
  
  
  
  
  
 




     




