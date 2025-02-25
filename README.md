# EEM FMC Carrier
HPC FMC Carrier with Artix-7 FPGA in EEM form factor

## Differences from FMC HPC specification
- 4 MGT links instead of 10
- HB signals are powered from VADJ, not from FMC_VIO_B_M2C

Note that LVDS is supported only with VADJ=2.5V (selectable by jumpers).

## Design Files

Check [Releases](https://github.com/sinara-hw/EEM_FMC_Carrier/releases) for reviewed versions of this module.

## Discussion

Please use [Discussion tab](https://github.com/sinara-hw/EEM_FMC_Carrier/discussions) for discussing feature requests, choosing names etc. Let's try to keep issues tab only to actionable items that need to be fixed in design sources.
