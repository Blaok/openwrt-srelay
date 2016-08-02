# Srelay for OpenWRT

At OpenWRT SDK root or build root:

```
pushd package
git clone https://github.com/Blaok/openwrt-srelay.git
popd
scripts/feeds install -d m openwrt-srelay
make package/openwrt-srelay/compile
```

Package should appear at `bin/${arch}/packages/base`.
