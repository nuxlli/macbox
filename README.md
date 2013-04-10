# Macbox #

Using `sandbox-exec + chroot + bindfs` tries to implement an alternative LXC on Mac OS X.

# Dependencies #

- Ruby 2.0
	- Gem: awesome_print
- bindfs
- Mac OS X Leopard or major

# Using #

```
$ ./macbox /bin/bash
```

# Warning #

This project uses root permissions, mount important directories and hardlink, careful when using.

# Referencies #

http://reverse.put.as/wp-content/uploads/2011/09/Apple-Sandbox-Guide-v1.0.pdf
