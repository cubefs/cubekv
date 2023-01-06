# CubeKV

CubeKV is the distributed key-value store on top of CubeFS.

## Data Model

space, (hashkey+sortkey) -> document

A space can be partitioned into multiple shards for better write throughput.

## Architecture

Master, Server, gRPC SDK

### Server

use Badger as the local storage engine

a server container hosts one shard

## Write Performance Optimization

CubeFS WAL files

Group commit

## Secondary Indexing

Cubesearch consumes the WALs on CubeFS to build secondary indices


