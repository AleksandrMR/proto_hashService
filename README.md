# ProtoGen for HashService

To use these contracts, you must run all the commands in the Makefile in this order:
1. install-deps
2. get-deps
3. vendor-proto
4. generate

After which the necessary dependencies will be pulled up and the necessary contracts for gRPS and Gateway will be generated.


---
**NOTE**

If you change the version in the .proto file, or create a new version of the .proto file for which new contracts need to be generated, be sure to also change the version in the Makefile.

---


