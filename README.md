# arch-audit

[![Build Status](https://travis-ci.org/ilpianista/arch-audit.svg?branch=master)](https://travis-ci.org/ilpianista/arch-audit)

[pkg-audit]()-like utility for [Arch Linux](https://archlinux.org).

Uses data collected by the awesome [Arch CVE Monitoring Team](https://wiki.archlinux.org/index.php/Arch_CVE_Monitoring_Team).

**This is WIP.**

## Installation

    git clone https://github.com/ilpianista/arch-audit
    cd arch-audit
    cargo build

## Usage

    cargo run

## Example output

    Package wpa_supplicant is affected by ["CVE-2016-4477", "CVE-2016-4476"]. VULNERABLE!
    Package libtiff is affected by ["CVE-2015-7554", "CVE-2015-8683"]. VULNERABLE!
    Package openssl is affected by ["CVE-2016-2177", "CVE-2016-2178", "CVE-2016-2179", "CVE-2016-2180", "CVE-2016-2181", "CVE-2016-2182", "CVE-2016-2183", "CVE-2016-6302", "CVE-2016-6303", "CVE-2016-6304", "CVE-2016-6306"]. Update to 1.0.2.i-1!
    Package linux is affected by ["CVE-2016-5244", "CVE-2016-5243"]. VULNERABLE!
    Package crypto++ is affected by ["CVE-2016-7420"]. VULNERABLE!
    Package xerces-c is affected by ["CVE-2015-0252"]. Update to 3.2.1-1!
    Package giflib is affected by ["CVE-2015-7555"]. Update to 5.2.1-1!
    Package jasper is affected by ["CVE-2015-5203"]. VULNERABLE!