# Role Testing

This example shows how Vagrant can be used for testing Roles.

The Vagrantfile is loacted inside the `./hello-world/tests/` directory.
It spins up three virtual machines running Debian9, Centos 7 and Ubuntu16.04 and deploys the role `hello-world` onto each of them, additionally a basic functionality test is implemented.

# Usage

Navigate into the directory `./hello-world/tests/` and run `vagrant up`