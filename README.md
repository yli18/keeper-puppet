# keeper-puppet
Puppet installation scripts for KEEPER infrastructure

```
mkdir puppet/etc/puppetlabs/code/environments/production/data
```
Put in <code>puppet/etc/puppetlabs/code/environments/production/data</code> directory common <code>keeper.ini</code> and <code>keeper_files</code> directory. Setup <code>keeper.ini</code> if needed.
```
sudo apt-get install virtualbox
sudo apt-get install vagrant
./scripts/start_vagrant.sh
```
