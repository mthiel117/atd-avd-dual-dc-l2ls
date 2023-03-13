# ATD AVD Dual Data Center L2LS Design

## ATD Topology

![ATD L2LS Topo](images/atd-avd-dual-dc-l2ls-topo.png)

## Initialize WAN environment

Push pre-defined configs for WAN Nodes

``` bash
make prepwan
```

## Build Site Configs

``` bash
# Build Site 1 Configs
make build-site-1

# Build Site 2 Configs
make build-site-2
```

## Deploy Site Configs

``` bash
# Build Site 1 Configs
make deploy-site-1

# Build Site 2 Configs
make deploy-site-2
```