Run from your dev machine. Currently just installs rvm and latest ruby, rails, and puma to specified server.
Designed for use with yum-using linuxes, specifically tested with Amazon Linux 2 and CentOS 7.5 on EC2.

#### Usage:
`./amznlinux-bootstrap --host HOSTNAME --user USERNAME --key KEYLOCATION`


#### Example:
`./amznlinux-bootstrap --host ec2-1234.compute.amazonaws.com --user ec2-user --key ~/.ssh/mykey.pem`

- TODO: add flags to enable toggling ruby/rails/puma install and versions
- TODO: allow for fallback to ~/.ssh/config so username or keyfile don't have to be explicitly specified
