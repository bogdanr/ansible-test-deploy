This is a very basic playbook for deploying from Git.

The destinations and the source are defined in `cfg.yaml` and to run the playbook all it's required is to run:

    ansible-playbook deploy.yaml

Currently it's hardcoded to deploy the latest code from master but of course it is very easy to change it to support branches or tags.
