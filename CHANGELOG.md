# Revision history for Z-MessagePack

## 0.4.1.0 -- 2021-04-25

* Adapt to `Z-IO` 0.8. Add stream error handling code.

## 0.3.0.1 -- 2021-02-25

* Add `callStream` and `StreamHandler`.

## 0.3.0.0 -- 2021-02-25

* Add `Z.IO.RPC.MessagePack` module.
* Move some instances to `Z.Data.MessagePack` to make package buildable under constrained memory.
* Remove `decodeChunks'`.
* Change `Data.Version.Version`'s instance to use array.
