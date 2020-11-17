# General instructions on building overlay of your choice:

```
dtc -I dts -O dtb -o <File_to_Create>.dtb0 <Input_File>.dts
```

### For emmc overlay:

```
dtc -I dts -O dtb -o tegra210-icosa_emmc-overlay.dtbo emmc_overlay.dts
```

copy tegra210-icosa_emmc-overlay.dtb to p1 on emmc and use Android_Emmc.txt to create boot.scr

### For UART-B debugging overlay:

```
dtc -I dts -O dtb -o tegra210-UART-B-overlay.dtbo uart_b_debug.dts
```

put in switchroot_android folder, or root of p1 on emmc, depending on what you are doing exactly....
