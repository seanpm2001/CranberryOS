
***

<img src="/CranberryOS_1024pxLogo_V1_HighCompression.png" alt="CranberryOS logo" width="256" height="256">

# [CranberryOS](#CranberryOS)

`⚡️📻️⚡️💾️ CranberryOS is an operating system for signal jammers. It requires special permissions to use legally.`

***

## [Legal notice](#Legal-notice)

In most countries, it is illegal for civilians to possess signal jammers. This software is intended for use on hardware contracted to law enforcement and other permitted users.

So far, no contracts have been made for this project (as of 2023, Tuesday, June 27th) it will likely be a long time before one is made.

***

## [Native devices](#Native-devices)

The devices that come pre-installed with CranberryOS have not yet been developed.

- [:octocat: `See: Cranberry Jammer`](https://github.com/seanpm2001/Cranberry-Jammer/)

**Devices**

- [:octocat: `cb49n1j1`](https://github.com/seanpm2001/Cranberry-Jammer#cb49n1j1)
- [:octocat: `cb49b1j1`](https://github.com/seanpm2001/Cranberry-Jammer#cb49b1j1)

***

## [Languages](#Languages)

CranberryOS is written in 6 programming languages:

- Assembly: For the core
- C : For the core and some hardware interaction
- Shell : For scripting
- Tcl : For the interface
- VHDL : For additional hardware interaction
- Verilog : For signal jamming hardware functions

***

## [Internet](#Internet)

CranberryOS does not support any forms of Internet connection (including Bluetooth) to avoid it targeting itself, or being compromised. It does not need Internet access to begin with.

***

## [Processor architecture](#Processor-architecture)

CranberryOS works on 64 bit AMD and Intel CPUs, and future support for an unnamed 128 bit processor(s) is planned.

CranberryOS does not support CPUs with 54 or less bits

***

## [Linux](#Linux)

CranberryOS works with the Linux Kernel. Planned dual-kernel support for TinyOS and other open-source kernels is planned.

***

## [Interface](#Interface)

The system is designed to have a square screen, and thus has a square interface. Any Linux desktop distribution that can work with this is supported, but the system is mostly locked down into [`SIG-C.INIT`](#SIG-C-INIT) the main interface and control panel for the single jammer.

The default screen resolution is `1000x1000` while the maximum screen resolution is `16000x16000` the absolute minimum screen resolution is `500x500`

---

### [SIG-C.INIT](SIG-C-INIT)

SIG-C.INIT (Signal C initialized) is the main interface and control system for CranberryOS. It is written in C, Shell, and Tcl.

***

## [Updates](#Updates)

[Because the system has no Internet](#Internet) updates are done via USB or other direct plugin methods. They have to be manually installed when deemed necessary.

***

## [Memory efficiency](#Memory-efficiency)

The system is designed to use no more than 63 megabytes of RAM on 64 bit processors, and no more than 126 megabytes of RAM on 128 bit processors.

There is a 72 megabyte minimum for RAM (on 64 bit systems) and a 144 megabyte minimum (on 128 bit systems) while the maximum RAM limit depends on the kernel version.

***

## [Original draft](#Original-draft)

```plain-text
CranberryOS

VERY BASIC OPERATING SYSTEM

Based on: Linux

Write in: C, Tcl, VHDL, Assembly, Verilog, Shell

Type: Signal jammer control system

Network: Absolutely no network connectivity of any kind (not even Bluetooth)

Update method: Software install via USB

RAM: Use less than 64 megabytes (64 bit) Use less than 128 megabytes (128 bit)

Bits: 64x128

Default resolution: 1000x1000

Max resolution: 16000x16000
```

***

## [Documentation](#Documentation)

Additional documentation is available [:octocat: `in a separate repository`](https://github.com/seanpm2001/CranberryOS_Docs/)

***

# [File info](#File-info)

**File version:** `1 (2023, Tuesday, June 27th at 10:49 pm PST)`

***

# [Footer](#Footer)

You have reached the end of this page.

###### [EOF](#EOF)

***
