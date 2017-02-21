## to merge
```bash
mergehex --merge _build/nrf51422_xxac.hex ~/Documents/nrf51822/softdevices/s130_nrf51_2.0.1_softdevice.hex --output _build/uart.hex
```

## prerequisites
* gcc-arm-none-eabi-6_2-2016q4-20161216-mac.tar.bz2
* nRF5_SDK_12.2.0_f012efa.zip
* s130_nrf51_2.0.1.zip
* nRF5x-Command-Line-Tools_9_3_1_OSX.tar

[download nordic libs here](http://www.nordicsemi.com/eng/Products/Bluetooth-low-energy/nRF51822#Downloads)

[downolad GNU toolchani here](https://developer.arm.com/open-source/gnu-toolchain/gnu-rm/downloads)

## directory structure
```
/nrf51822
    /ble_batt_mon                                 # project's git repository
    /cmdtools                                     # nordic command tools
        /mergehex                                 # created after expanding the tarball
        nRF5x-Command-Line-Tools_9_3_1_OSX.tar    # untar here
    /gcc-arm-none-eabi-6_2-2016q4                 # gcc
    /sdk                                          # nordic SDK
        nRF5_SDK_12.2.0_f012efa.zip               # unzip here
    /softdevices                                  # nordic softdevice
        /s130_nrf51_2.0.1_API                     # created after unziping the archive
        s130_nrf51_2.0.1.zip                      # unzip here
```

