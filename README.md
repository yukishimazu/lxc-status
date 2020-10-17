# lxc-status
lxc container status monitoring tool

## Usage

    ./lxc-status
or

    watch ./lxc-status

## Sample

    ~/lxc-status# ./lxc-status
    ----------------------------------------------------------------
    Name            | Status     | Memory          | Memory(peak)
    ----------------------------------------------------------------
             bionic |    Running |          121 MB |          143 MB
          calappdev |    Running |         47.6 MB |         53.8 MB
         golfappdev |    Running |         1.64 GB |         1.66 GB
             gollum |    Running |         35.1 MB |         40.2 MB
    ----------------------------------------------------------------
    Total                        |         1.83 GB |         1.89 GB
    ----------------------------------------------------------------

## References

* https://linuxcontainers.org/lxc/
* https://discuss.linuxcontainers.org/t/list-running-containers/7049/5
