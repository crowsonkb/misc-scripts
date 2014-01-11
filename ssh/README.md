Fast-reconnecting multiplexing SSH scripts, startable at login.

`ssh-master-kath` will notice that the SSH connection has been dropped within five or so seconds and begin reconnection attempts once per second. `ssh-kath` will wait until the master connection is re-established, then reconnect itself.

`io.kath.ssh-master-kath.plist` goes in `~/Library/LaunchAgents`. Edit it to reflect the actual location of the `ssh-master-kath` script.
