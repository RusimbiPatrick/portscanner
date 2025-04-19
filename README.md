# Port Scanner

Spawning a pool of worker goroutines that concurrently attempt to establish TCP connections to a range of ports on the specified address. If a connection is successful, a port is considered open. Otherwise, it's closed.
