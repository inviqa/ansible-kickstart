# ansible-kickstart
Kickstarter script to install ansible with no human interaction

# installation
```
curl --silent --show-error https://raw.githubusercontent.com/inviqa/ansible-kickstart/master/ansible-kickstart | sudo bash
```

# Parameters (optional)
```
Choose whether installing a VirtualEnv
`--install-ansible-venv <true|false>`

Choose where to install the VirtualEnv
`--venv <dir>`
Implies `--install-ansible-venv`

Choose what version of Ansible to install
`--ansible-version <ansible-version>`

Choose the url for the ansible provisioning script
`--ansible-provision-url`

Choose the installation directory for the ansible provisioning script
`--ansible-provision-directory`

Choose whether to install Ansible base config
`--install-ansible-base`

Choose the url for the ansible base configs
`--ansible-base-url`
Implies `--install-ansible-base`

Choose the installation directory for the ansible base configs
`--ansible-base-directory`
Implies `--install-ansible-base`

Skip the XCode CommandLineTools installation
`--skip-xcode-clt`
Applies only to macOS
```
