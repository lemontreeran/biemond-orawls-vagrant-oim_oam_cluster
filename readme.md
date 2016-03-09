#OIM/OAM cluster vagrant box

Oracle access & identity manager 11.1.2.3


##Details
- OEL 6.6 vagrant box
- Puppet 3.8
- Vagrant >= 1.8
- Oracle Virtualbox >= 5.0 or VMware fusion >= 6

Add all the Oracle binaries to the vagrant folder or make links to these files inside this folder

Or pptional edit the Vagrantfile and add the software share plus update all puppet files ( change /vagrant to /software )
- oim1admin.vm.synced_folder "/Users/edwin/software", "/software"
- oimdb.vm.synced_folder "/Users/edwin/software", "/software"
- oimoud.vm.synced_folder "/Users/edwin/software", "/software"

Vagrant boxes
- vagrant up oimdb
- vagrant up oim1admin
- vagrant up oimnode1
- vagrant up oimnode2

## Databases
- oimdb 10.10.10.9, 11.2.0.4 met OIM/OAM RCU

### software
- Oracle Database 11.2.0.4 Linux
- 1395582860 Aug 31 16:21 p13390677_112040_Linux-x86-64_1of7.zip
- 1151304589 Aug 31 16:22 p13390677_112040_Linux-x86-64_2of7.zip
- OPatch upgrade p6880880_112000_Linux-x86-64.zip
- RCU ofm_rcu_linux_11.1.1.9.0_64_disk1_1of1.zip

## OIM/OAM Middleware

### WebLogic Server
- oim1admin 10.10.10.61 port 7001 weblogic/weblogic1, WebLogic 10.3.6 with OIM,OAM,SOA Suite

## Software

### JDK
- UnlimitedJCEPolicyJDK7.zip
- jdk-7u80-linux-x64.tar.gz

### WebLogic
- wls1036_generic.jar

### BSU patch
- p20181997_1036_Generic.zip

### FMW
- ofm_iam_generic_11.1.2.3.0_disk1_1of3.zip
- ofm_iam_generic_11.1.2.3.0_disk1_2of3.zip
- ofm_iam_generic_11.1.2.3.0_disk1_3of3.zip
- V75849-01_1of2.zip soa suite 11.1.1.9.0 from edelivery
- V75849-01_2of2.zip soa suite 11.1.1.9.0 from edelivery

