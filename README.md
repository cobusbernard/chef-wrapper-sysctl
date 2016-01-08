# chef-wrapper-sysctl-cookbook

Wrapper cookbook for sysctl. Currently only used to disable ipv6.

## Supported Platforms

Ubuntu 14.04

## Usage

### chef-wrapper-sysctl::default

Include `chef-wrapper-sysctl` in your node's `run_list`:

```json
{
  "run_list": [
    "recipe[chef-wrapper-sysctl::default]"
  ]
}
```

## License and Authors

Author:: Cobus Bernard (<me@cobus.io>)
