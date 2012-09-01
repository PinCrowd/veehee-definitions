# Pincrowd Vagrant Definitions #

These definitions are used to build base Vagrant boxes for Pincrowd Developers.


## Getting Started

 - [Install RVM](https://rvm.io/rvm/install/)

###Setup `veewee`

```bash
   rvm install 1.8.7
   rvm install 1.9.2
   rvm use 1.9.2
   rvm gemset create veewee
   rvm 1.9.2@veewee
   gem install veewee
```

### Build the box:

```bash
    vagrant basebox build pincrowd64
    vagrant basebox validate pincrowd64
    vagrant basebox export pincrowd64
    vagrant init pincrowd64
    vagrant up
    vagrant ssh

    vagrant box add 'pincrowd64' 'pincrowd64.box'
```

## Resources

  - [Vagrant Walk-Through](http://seletz.github.com/blog/2012/01/17/creating-vagrant-base-boxes-with-veewee/)
  - [VagrantUp.Com](http://vagrantup.com/)
  - [Sun XVM VirtualBox®](http://virtualbox.org/)
  - [http://virtualboxes.org/](http://virtualboxes.org/)

