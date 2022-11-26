# CubeKV

CubeKV is the distributed key-value store on top of CubeFS.

## Data Model

DB, (shardkey,sortkey) -> value

A DB can be partitioned into multiple shards for better write throughput.

## Architecture

Master, DataServer, gRPC SDK

### DataServer

use Badger or RocksDB as the local storage engine


## Write Performance Optimization

CubeFS WAL files


