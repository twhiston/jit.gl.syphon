# Syphon Max

Rebuild of Syphon for m1 and the 8.2 max sdk.

It expects the Syphon-Framework in the root folder of the repo and it's included as a submodule.

You should clone this into your max-sdk path so everything works

`git clone git@github.com:twhiston/jit.gl.syphon.git "~/Documents/Max 8/Packages/max-sdk/build/source/syphon"`


All credit to https://github.com/Syphon/Jitter for the original. I'll try to contribute this back to them, but it's a big rebuild so we'll see how they want to do it!

You will probably need to 

```bash
xattr -d com.apple.quarantine jit.gl.syphonserver.mxo
xattr -d com.apple.quarantine jit.gl.syphonclient.mxo
```