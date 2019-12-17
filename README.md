# hello-flask-zappa.pipeline.side8

Demo of a flask zappa app that implements pipeline.side8 deployments.

The Zappa lambda is generated using the `zappa package` command, after which it shifts over to the pipeline.side8 pipeline instead of using zappa for deployments.

Edit the cloudformation.yml or create other non-Zappa apps to integrate other AWS services.
