---
pagetitle: Release Notes for ASM330LHB Component
lang: en
header-includes: <link rel="icon" type="image/x-icon" href="_htmresc/favicon.png" />
---

::: {.row}
::: {.col-sm-12 .col-lg-4}

<center>
# Release Notes for ASM330LHB Component Driver
Copyright &copy; 2023 STMicroelectronics\

[![ST logo](_htmresc/st_logo_2020.png)](https://www.st.com){.logo}
</center>

# License

This software component is licensed by ST under BSD 3-Clause license, the "License".
You may not use this component except in compliance with the License. You may obtain a copy of the License at:

[BSD 3-Clause license](https://opensource.org/licenses/BSD-3-Clause)

# Purpose

This directory contains the ASM330LHB component drivers.
:::

::: {.col-sm-12 .col-lg-8}
# Update history

::: {.collapse}
<input type="checkbox" id="collapse-section1" aria-hidden="true">
<label for="collapse-section1" aria-hidden="true">V1.0.0 / 09-Mar-2023</label>
<div>

## Main changes

### First release

- First official release [ref. DS v7.0 (01-Feb-2023)]

##
</div>

<input type="checkbox" id="collapse-section2" aria-hidden="true">
<label for="collapse-section2" aria-hidden="true">V2.0.0 / 19-Mar-2024</label>
<div>

## Main changes

- Add "const" to ctx arg for all APIs

##
</div>

<input type="checkbox" id="collapse-section3" aria-hidden="true">
<label for="collapse-section3" aria-hidden="true">V2.0.1 / 11-Apr-2024</label>
<div>

## Main changes

- updated README.md file with tag reference and mdelay description
- Fixed code style (Artistic Style Version 3.4.13)

##
</div>

<input type="checkbox" id="collapse-section4" aria-hidden="true">
<label for="collapse-section4" aria-hidden="true">V2.1.0 / 18-Dec-2024</label>
<div>

## Main changes

- Read always both FIFO_STATUS1 and FIFO_STATUS2 regs
- Align asm330lh software compatible drivers
- Fix fifo_watermark_set() API

##
</div>

<input type="checkbox" id="collapse-section5" aria-hidden="true">
<label for="collapse-section5" aria-hidden="true">V2.2.0 / 07-Jul-2025</label>
<div>

## Main changes

- Fix driver formatting options
- Added pointer to private data in stmdev_ctx_t

##
</div>

<input type="checkbox" id="collapse-section6" checked aria-hidden="true">
<label for="collapse-section6" aria-hidden="true">V2.3.0 / 07-Oct-2025</label>
<div>

## Main changes

- Aligned ln_pg_write/read implementations
- Added checks before writes and membank setting
- Adding CODE_OF_CONDUCT.md and SECURITY.md

##
</div>
:::


:::
:::

<footer class="sticky">
::: {.columns}
::: {.column width="95%"}
For complete documentation on ASM330LHB,
visit:
[ASM330LHB](https://www.st.com/en/mems-and-sensors/asm330lhb.html)
:::
::: {.column width="5%"}
<abbr title="Based on template cx566953 version 2.0">Info</abbr>
:::
:::
</footer>
