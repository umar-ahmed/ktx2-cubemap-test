Cubemap generated with `toktx`:

```shell
toktx \
    --t2 \
    --genmipmap \
    --assign_oetf srgb \
    --target_type RGBA \
    --cubemap \
    --encode etc1s \
    -- cubemap.ktx2 \
    nx.png px.png py.png ny.png pz.png nz.png
```

To run, use `npx serve .`
