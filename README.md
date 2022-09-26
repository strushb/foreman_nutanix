# Foreman Nutanix Plugin

## Description
```foreman_nutanix``` might add [Nutanix AHV](http://nutanix.com/) as a Compute Resource for The Foreman

* Website: [TheForeman.org](http://theforeman.org)

### Development Setup

Clone the repo from github:
```bash
git clone https://github.com/strushb/foreman_nutanix.git
```

Add the following to bundler.d/Gemfile.local.rb in your Foreman development directory

```ruby
gem 'foreman_nutanix', :path => 'path to foreman_nutanix directory'
```

Then run `bundle install` from the same directory

## Features
* None yet

## Configuration
Go to **Infrastructure > Compute Resources** and click on "New Compute Resource".

Choose the **Nutanix provider**, and fill in all the fields.

## Planned Features
* Create VMs in Nutanix
    
## Known Limitations
* Work in Progress
