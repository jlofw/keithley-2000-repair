# Repair documentation (work in progress)

## Built-in test

### Failed tests

- 100.2
  - This test has the identical setup as the 100.1 test. Signal LO is connected
    to the A/D circuit for ten readings and a min/max comparison is done to en-
    sure that all readings are within 100 counts of each other. The test is to check
    for noise. The failures are the same as in test 100.1.

    Primary checks should be the references and power supplies. Secondary
    tests are the op amps of the integrator (U138 and U137), gain op amp U142,
    and the zero-cross comparator U145.

     If the 100 series tests fail, all other tests will be invalid.
- 301.1
- 301.2
- 303.1
- 303.2
- 500.1
- 500.2
- 600.1
- 600.2
- 601.2

## Reference

- K2000 Repair Manual (see resources)
- <https://xdevs.com/fix/kei2000/>
- <https://xdevs.com/guide/plastic_bleach/>
- <https://www.eevblog.com/forum/repair/keithley-2000-firmware-update/>
- <https://www.eevblog.com/forum/repair/repair-old-keithley-2000-teardown-and-fix/>
- <https://www.eevblog.com/forum/repair/repaired-keithley-2000/>
- <https://www.eevblog.com/forum/repair/2x-keithley-2000-repair-log/>
- <https://www.eevblog.com/forum/repair/first-time-on-keithley-2000/>
- <https://forum.tek.com/viewtopic.php?f=32&t=6600>
