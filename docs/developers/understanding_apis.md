#

## Table of Contents

The iRODS APIs are documented in Doxygen: [https://docs.irods.org/4.3.0/doxygen](https://docs.irods.org/4.3.0/doxygen)

This page gives a description of commonly used iRODS APIs by describing the internal processes and providing some analysis that follows from that.

Quick Links:

- [Open](#open)
- [Write](#write)
- [Close](#close)
- [Finalize](#finalize)
- [Put](#put)
- [Get](#get)
- [Copy](#copy)
- [Replicate](#replicate)
- [Phymv](#phymv)
- [Unlink](#unlink)
- [Rename](#rename)

## Open

Open is modeled after [POSIX open](https://pubs.opengroup.org/onlinepubs/007904875/functions/open.html).

There are two ways to open a data object:
```C
int rcDataObjOpen(rcComm_t*, dataObjInp_t*);
```

```C
int rc_replica_close(struct RcComm*, const char*);
```

## Write
## Close
## Finalize
## Put
## Get
## Copy
## Replicate
## Phymv
## Unlink
## Rename
