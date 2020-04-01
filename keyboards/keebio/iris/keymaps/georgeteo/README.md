# Setup QMK

https://docs.qmk.fm/#/newbs_getting_started

# Compile

```
qmk compile -kb keebio/iris/rev4 -km georgeteo
```

# Flash

- Use [qmk-toolbox](https://qmk.fm/toolbox/) with `microcontroller=atmega32u4`.
- Flash left and right seprately with the same `.hex` file.
