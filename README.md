# CubeKV

CubeKV is the distributed key-value store on top of CubeFS.

## Data Model

space, (hashkey+sortkey) -> value

A space can be partitioned into multiple shards for better write throughput.

## Architecture

Master, Server, gRPC SDK

### Server

use Badger or RocksDB as the local storage engine


## Write Performance Optimization

CubeFS WAL files


