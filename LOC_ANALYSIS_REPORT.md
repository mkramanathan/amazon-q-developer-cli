# Lines of Code (LOC) Analysis Report

**Repository:** amazon-q-developer-cli
**Analysis Date:** 2026-01-16
**Total Files Analyzed:** 2607

---

## Executive Summary

- **Total Lines:** 343,651
- **Code Lines:** 276,089 (80.3%)
- **Comment Lines:** 37,266 (10.8%)
- **Blank Lines:** 30,296 (8.8%)
- **Comment to Code Ratio:** 0.13

---

## Breakdown by Programming Language

| Language | Files | Code | Comments | Blank | Total | % of Total Code |
|----------|------:|-----:|---------:|------:|------:|----------------:|
| Rust | 1,954 | 235,264 | 34,568 | 25,095 | 294,927 | 85.2% |
| TypeScript | 256 | 25,825 | 1,401 | 2,908 | 30,134 | 9.4% |
| JSON | 194 | 4,242 | 0 | 21 | 4,263 | 1.5% |
| TOML | 54 | 2,258 | 85 | 273 | 2,616 | 0.8% |
| Python | 11 | 1,999 | 165 | 460 | 2,624 | 0.7% |
| JavaScript | 38 | 1,878 | 563 | 340 | 2,781 | 0.7% |
| Protocol Buffers | 7 | 1,218 | 132 | 289 | 1,639 | 0.4% |
| Markdown | 42 | 1,159 | 0 | 473 | 1,632 | 0.4% |
| Shell | 14 | 838 | 292 | 273 | 1,403 | 0.3% |
| CSS | 3 | 560 | 16 | 96 | 672 | 0.2% |
| HTML | 6 | 452 | 4 | 58 | 514 | 0.2% |
| YAML | 10 | 225 | 40 | 10 | 275 | 0.1% |
| SVG | 18 | 171 | 0 | 0 | 171 | 0.1% |
| **TOTAL** | **2,607** | **276,089** | **37,266** | **30,296** | **343,651** | **100.0%** |


## Breakdown by Component/Directory

| Component | Files | Code | Comments | Blank | Total | % of Total Code |
|-----------|------:|-----:|---------:|------:|------:|----------------:|
| crates/amzn-codewhisperer-client | 602 | 63,434 | 10,156 | 5,450 | 79,040 | 23.0% |
| crates/amzn-consolas-client | 300 | 32,305 | 4,408 | 2,504 | 39,217 | 11.7% |
| crates/amzn-codewhisperer-streaming-client | 296 | 22,471 | 5,067 | 2,015 | 29,553 | 8.1% |
| crates/amzn-qdeveloper-streaming-client | 267 | 19,640 | 4,621 | 1,785 | 26,046 | 7.1% |
| crates/zbus | 63 | 14,043 | 3,333 | 2,236 | 19,612 | 5.1% |
| crates/q_chat | 28 | 12,669 | 1,147 | 1,394 | 15,210 | 4.6% |
| crates/q_cli | 56 | 11,892 | 475 | 1,424 | 13,791 | 4.3% |
| crates/fig_desktop | 54 | 9,791 | 323 | 1,177 | 11,291 | 3.5% |
| crates/figterm | 30 | 7,157 | 582 | 923 | 8,662 | 2.6% |
| packages/autocomplete | 60 | 6,847 | 232 | 756 | 7,835 | 2.5% |
| packages/autocomplete-app | 60 | 6,847 | 232 | 756 | 7,835 | 2.5% |
| crates/alacritty_terminal | 146 | 6,049 | 1,058 | 1,151 | 8,258 | 2.2% |
| packages/dashboard-app | 85 | 5,657 | 281 | 437 | 6,375 | 2.0% |
| crates/amzn-toolkit-telemetry | 55 | 4,810 | 1,423 | 544 | 6,777 | 1.7% |
| crates/fig_integrations | 19 | 3,583 | 322 | 627 | 4,532 | 1.3% |
| crates/fig_util | 17 | 3,402 | 299 | 483 | 4,184 | 1.2% |
| crates/macos-utils | 39 | 2,963 | 50 | 405 | 3,418 | 1.1% |
| packages/autocomplete-parser | 18 | 2,635 | 124 | 350 | 3,109 | 1.0% |
| crates/fig_install | 10 | 2,603 | 81 | 273 | 2,957 | 0.9% |
| packages/api-bindings | 30 | 2,564 | 63 | 201 | 2,828 | 0.9% |
| crates/fig_api_client | 17 | 2,448 | 55 | 302 | 2,805 | 0.9% |
| extensions | 51 | 2,213 | 840 | 512 | 3,565 | 0.8% |
| crates/fig_desktop_api | 21 | 2,183 | 84 | 270 | 2,537 | 0.8% |
| crates/zbus_names | 12 | 2,050 | 371 | 441 | 2,862 | 0.7% |
| root | 24 | 2,011 | 90 | 319 | 2,420 | 0.7% |
| crates/fig_settings | 10 | 1,971 | 86 | 326 | 2,383 | 0.7% |
| crates/mcp_client | 11 | 1,940 | 113 | 141 | 2,194 | 0.7% |
| build-system | 16 | 1,706 | 145 | 373 | 2,224 | 0.6% |
| tests | 35 | 1,695 | 32 | 295 | 2,022 | 0.6% |
| crates/fig_auth | 12 | 1,594 | 145 | 238 | 1,977 | 0.6% |
| crates/fig_os_shim | 11 | 1,488 | 151 | 230 | 1,869 | 0.5% |
| crates/fig_telemetry | 8 | 1,392 | 60 | 191 | 1,643 | 0.5% |
| proto | 12 | 1,320 | 132 | 307 | 1,759 | 0.5% |
| crates/fig_proto | 12 | 1,134 | 40 | 187 | 1,361 | 0.4% |
| packages/shell-parser | 16 | 1,062 | 121 | 165 | 1,348 | 0.4% |
| crates/dbus | 5 | 995 | 147 | 168 | 1,310 | 0.4% |
| crates/fig_ipc | 11 | 938 | 25 | 139 | 1,102 | 0.3% |
| crates/fig_remote_ipc | 4 | 782 | 18 | 69 | 869 | 0.3% |
| crates/aws-toolkit-telemetry-definitions | 5 | 710 | 6 | 54 | 770 | 0.3% |
| crates/fig_request | 5 | 624 | 12 | 95 | 731 | 0.2% |
| crates/fig_telemetry_core | 3 | 600 | 13 | 32 | 645 | 0.2% |
| crates/shell-color | 2 | 555 | 52 | 65 | 672 | 0.2% |
| crates/fig_aws_common | 5 | 489 | 17 | 74 | 580 | 0.2% |
| crates/fig_input_method | 5 | 409 | 17 | 65 | 491 | 0.1% |
| packages/shared | 11 | 405 | 30 | 57 | 492 | 0.1% |
| packages/api-bindings-wrappers | 10 | 304 | 15 | 37 | 356 | 0.1% |
| crates/fig_diagnostic | 2 | 275 | 4 | 33 | 312 | 0.1% |
| packages/fuzzysort | 4 | 274 | 55 | 31 | 360 | 0.1% |
| crates/fig_log | 2 | 247 | 48 | 44 | 339 | 0.1% |
| scripts | 2 | 180 | 10 | 35 | 225 | 0.1% |
| documentation | 9 | 165 | 0 | 46 | 211 | 0.1% |
| packages/eslint-config | 6 | 163 | 21 | 12 | 196 | 0.1% |
| crates/fig_test_utils | 4 | 159 | 28 | 23 | 210 | 0.1% |
| crates/fig_test_macro | 2 | 83 | 0 | 15 | 98 | 0.0% |
| packages/types | 2 | 72 | 6 | 3 | 81 | 0.0% |
| crates/fig_test | 2 | 49 | 0 | 8 | 57 | 0.0% |
| packages/tsconfig | 3 | 42 | 0 | 3 | 45 | 0.0% |


## Detailed Component Analysis

### crates/amzn-codewhisperer-client

**Total Files:** 602 | **Code Lines:** 63,434 | **Comment Lines:** 10,156

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 601 | 63,356 | 10,146 | 5,431 | 78,933 |
| TOML | 1 | 78 | 10 | 19 | 107 |


### crates/amzn-consolas-client

**Total Files:** 300 | **Code Lines:** 32,305 | **Comment Lines:** 4,408

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 299 | 32,228 | 4,398 | 2,485 | 39,111 |
| TOML | 1 | 77 | 10 | 19 | 106 |


### crates/amzn-codewhisperer-streaming-client

**Total Files:** 296 | **Code Lines:** 22,471 | **Comment Lines:** 5,067

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 295 | 22,392 | 5,057 | 1,996 | 29,445 |
| TOML | 1 | 79 | 10 | 19 | 108 |


### crates/amzn-qdeveloper-streaming-client

**Total Files:** 267 | **Code Lines:** 19,640 | **Comment Lines:** 4,621

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 266 | 19,562 | 4,611 | 1,766 | 25,939 |
| TOML | 1 | 78 | 10 | 19 | 107 |


### crates/zbus

**Total Files:** 63 | **Code Lines:** 14,043 | **Comment Lines:** 3,333

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 61 | 13,806 | 3,327 | 2,185 | 19,318 |
| TOML | 1 | 129 | 6 | 11 | 146 |
| Markdown | 1 | 108 | 0 | 40 | 148 |


### crates/q_chat

**Total Files:** 28 | **Code Lines:** 12,669 | **Comment Lines:** 1,147

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 26 | 12,437 | 1,147 | 1,391 | 14,975 |
| JSON | 1 | 176 | 0 | 0 | 176 |
| TOML | 1 | 56 | 0 | 3 | 59 |


### crates/q_cli

**Total Files:** 56 | **Code Lines:** 11,892 | **Comment Lines:** 475

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 47 | 11,264 | 457 | 1,344 | 13,065 |
| JSON | 7 | 353 | 0 | 0 | 353 |
| Shell | 1 | 176 | 18 | 72 | 266 |
| TOML | 1 | 99 | 0 | 8 | 107 |


### crates/fig_desktop

**Total Files:** 54 | **Code Lines:** 9,791 | **Comment Lines:** 323

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 48 | 9,342 | 318 | 1,122 | 10,782 |
| HTML | 2 | 254 | 2 | 38 | 294 |
| TOML | 2 | 149 | 3 | 13 | 165 |
| JSON | 1 | 37 | 0 | 0 | 37 |
| Markdown | 1 | 9 | 0 | 4 | 13 |


### crates/figterm

**Total Files:** 30 | **Code Lines:** 7,157 | **Comment Lines:** 582

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 27 | 6,993 | 581 | 888 | 8,462 |
| TOML | 1 | 83 | 1 | 6 | 90 |
| Markdown | 2 | 81 | 0 | 29 | 110 |


### packages/autocomplete

**Total Files:** 60 | **Code Lines:** 6,847 | **Comment Lines:** 232

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| TypeScript | 47 | 6,143 | 209 | 702 | 7,054 |
| JSON | 4 | 335 | 0 | 3 | 338 |
| CSS | 1 | 211 | 7 | 32 | 250 |
| JavaScript | 3 | 63 | 15 | 1 | 79 |
| Markdown | 1 | 59 | 0 | 17 | 76 |
| SVG | 2 | 22 | 0 | 0 | 22 |
| HTML | 1 | 13 | 0 | 0 | 13 |
| Shell | 1 | 1 | 1 | 1 | 3 |


### packages/autocomplete-app

**Total Files:** 60 | **Code Lines:** 6,847 | **Comment Lines:** 232

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| TypeScript | 47 | 6,143 | 209 | 702 | 7,054 |
| JSON | 4 | 335 | 0 | 3 | 338 |
| CSS | 1 | 211 | 7 | 32 | 250 |
| JavaScript | 3 | 63 | 15 | 1 | 79 |
| Markdown | 1 | 59 | 0 | 17 | 76 |
| SVG | 2 | 22 | 0 | 0 | 22 |
| HTML | 1 | 13 | 0 | 0 | 13 |
| Shell | 1 | 1 | 1 | 1 | 3 |


### crates/alacritty_terminal

**Total Files:** 146 | **Code Lines:** 6,049 | **Comment Lines:** 1,058

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 13 | 5,891 | 1,058 | 1,148 | 8,097 |
| JSON | 132 | 132 | 0 | 0 | 132 |
| TOML | 1 | 26 | 0 | 3 | 29 |


### packages/dashboard-app

**Total Files:** 85 | **Code Lines:** 5,657 | **Comment Lines:** 281

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| TypeScript | 71 | 5,203 | 244 | 397 | 5,844 |
| JavaScript | 3 | 143 | 35 | 2 | 180 |
| CSS | 1 | 138 | 2 | 32 | 172 |
| JSON | 4 | 118 | 0 | 3 | 121 |
| SVG | 4 | 36 | 0 | 0 | 36 |
| HTML | 1 | 13 | 0 | 0 | 13 |
| Markdown | 1 | 6 | 0 | 3 | 9 |


### crates/amzn-toolkit-telemetry

**Total Files:** 55 | **Code Lines:** 4,810 | **Comment Lines:** 1,423

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 54 | 4,744 | 1,413 | 526 | 6,683 |
| TOML | 1 | 66 | 10 | 18 | 94 |


### crates/fig_integrations

**Total Files:** 19 | **Code Lines:** 3,583 | **Comment Lines:** 322

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 14 | 3,176 | 133 | 528 | 3,837 |
| Shell | 4 | 363 | 189 | 92 | 644 |
| TOML | 1 | 44 | 0 | 7 | 51 |


### crates/fig_util

**Total Files:** 17 | **Code Lines:** 3,402 | **Comment Lines:** 299

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 16 | 3,345 | 299 | 475 | 4,119 |
| TOML | 1 | 57 | 0 | 8 | 65 |


### crates/macos-utils

**Total Files:** 39 | **Code Lines:** 2,963 | **Comment Lines:** 50

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 34 | 2,862 | 50 | 396 | 3,308 |
| TOML | 5 | 101 | 0 | 9 | 110 |


### packages/autocomplete-parser

**Total Files:** 18 | **Code Lines:** 2,635 | **Comment Lines:** 124

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| TypeScript | 13 | 2,573 | 123 | 350 | 3,046 |
| JSON | 3 | 57 | 0 | 0 | 57 |
| JavaScript | 1 | 4 | 1 | 0 | 5 |
| Markdown | 1 | 1 | 0 | 0 | 1 |


### crates/fig_install

**Total Files:** 10 | **Code Lines:** 2,603 | **Comment Lines:** 81

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 8 | 1,857 | 81 | 258 | 2,196 |
| JSON | 1 | 697 | 0 | 8 | 705 |
| TOML | 1 | 49 | 0 | 7 | 56 |


### packages/api-bindings

**Total Files:** 30 | **Code Lines:** 2,564 | **Comment Lines:** 63

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| TypeScript | 26 | 2,465 | 62 | 190 | 2,717 |
| JSON | 2 | 51 | 0 | 0 | 51 |
| Markdown | 1 | 44 | 0 | 11 | 55 |
| JavaScript | 1 | 4 | 1 | 0 | 5 |


### crates/fig_api_client

**Total Files:** 17 | **Code Lines:** 2,448 | **Comment Lines:** 55

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 16 | 2,405 | 55 | 298 | 2,758 |
| TOML | 1 | 43 | 0 | 4 | 47 |


### extensions

**Total Files:** 51 | **Code Lines:** 2,213 | **Comment Lines:** 840

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| JavaScript | 19 | 1,322 | 458 | 314 | 2,094 |
| TypeScript | 8 | 523 | 382 | 147 | 1,052 |
| JSON | 8 | 166 | 0 | 0 | 166 |
| Markdown | 7 | 112 | 0 | 51 | 163 |
| SVG | 9 | 90 | 0 | 0 | 90 |


### crates/fig_desktop_api

**Total Files:** 21 | **Code Lines:** 2,183 | **Comment Lines:** 84

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 20 | 2,138 | 84 | 265 | 2,487 |
| TOML | 1 | 45 | 0 | 5 | 50 |


### crates/zbus_names

**Total Files:** 12 | **Code Lines:** 2,050 | **Comment Lines:** 371

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 10 | 2,013 | 371 | 427 | 2,811 |
| TOML | 1 | 23 | 0 | 5 | 28 |
| Markdown | 1 | 14 | 0 | 9 | 23 |


### root

**Total Files:** 24 | **Code Lines:** 2,011 | **Comment Lines:** 90

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| JSON | 3 | 643 | 0 | 0 | 643 |
| Markdown | 8 | 472 | 0 | 199 | 671 |
| TOML | 8 | 436 | 23 | 25 | 484 |
| Python | 1 | 432 | 65 | 94 | 591 |
| JavaScript | 1 | 12 | 0 | 0 | 12 |
| TypeScript | 2 | 8 | 2 | 1 | 11 |
| YAML | 1 | 8 | 0 | 0 | 8 |


### crates/fig_settings

**Total Files:** 10 | **Code Lines:** 1,971 | **Comment Lines:** 86

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 8 | 1,728 | 86 | 323 | 2,137 |
| JSON | 1 | 216 | 0 | 0 | 216 |
| TOML | 1 | 27 | 0 | 3 | 30 |


### crates/mcp_client

**Total Files:** 11 | **Code Lines:** 1,940 | **Comment Lines:** 113

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 10 | 1,914 | 113 | 137 | 2,164 |
| TOML | 1 | 26 | 0 | 4 | 30 |


### build-system

**Total Files:** 16 | **Code Lines:** 1,706 | **Comment Lines:** 145

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Python | 9 | 1,496 | 100 | 352 | 1,948 |
| YAML | 5 | 155 | 36 | 9 | 200 |
| Shell | 1 | 53 | 9 | 12 | 74 |
| TOML | 1 | 2 | 0 | 0 | 2 |


### tests

**Total Files:** 35 | **Code Lines:** 1,695 | **Comment Lines:** 32

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| TypeScript | 18 | 1,005 | 20 | 199 | 1,224 |
| Rust | 4 | 332 | 4 | 59 | 395 |
| JSON | 4 | 119 | 0 | 1 | 120 |
| Python | 1 | 71 | 0 | 14 | 85 |
| Markdown | 1 | 49 | 0 | 17 | 66 |
| JavaScript | 3 | 48 | 4 | 3 | 55 |
| YAML | 2 | 36 | 4 | 0 | 40 |
| TOML | 2 | 35 | 0 | 2 | 37 |


### crates/fig_auth

**Total Files:** 12 | **Code Lines:** 1,594 | **Comment Lines:** 145

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 10 | 1,395 | 143 | 215 | 1,753 |
| HTML | 1 | 159 | 2 | 20 | 181 |
| TOML | 1 | 40 | 0 | 3 | 43 |


### crates/fig_os_shim

**Total Files:** 11 | **Code Lines:** 1,488 | **Comment Lines:** 151

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 10 | 1,467 | 151 | 226 | 1,844 |
| TOML | 1 | 21 | 0 | 4 | 25 |


### crates/fig_telemetry

**Total Files:** 8 | **Code Lines:** 1,392 | **Comment Lines:** 60

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 7 | 1,352 | 60 | 188 | 1,600 |
| TOML | 1 | 40 | 0 | 3 | 43 |


### proto

**Total Files:** 12 | **Code Lines:** 1,320 | **Comment Lines:** 132

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Protocol Buffers | 7 | 1,218 | 132 | 289 | 1,639 |
| JSON | 2 | 41 | 0 | 0 | 41 |
| Markdown | 1 | 35 | 0 | 17 | 52 |
| YAML | 2 | 26 | 0 | 1 | 27 |


### crates/fig_proto

**Total Files:** 12 | **Code Lines:** 1,134 | **Comment Lines:** 40

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 11 | 1,104 | 40 | 183 | 1,327 |
| TOML | 1 | 30 | 0 | 4 | 34 |


### packages/shell-parser

**Total Files:** 16 | **Code Lines:** 1,062 | **Comment Lines:** 121

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| TypeScript | 7 | 943 | 56 | 105 | 1,104 |
| Shell | 4 | 64 | 64 | 60 | 188 |
| JSON | 3 | 50 | 0 | 0 | 50 |
| JavaScript | 1 | 4 | 1 | 0 | 5 |
| Markdown | 1 | 1 | 0 | 0 | 1 |


### crates/dbus

**Total Files:** 5 | **Code Lines:** 995 | **Comment Lines:** 147

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 4 | 972 | 147 | 165 | 1,284 |
| TOML | 1 | 23 | 0 | 3 | 26 |


### crates/fig_ipc

**Total Files:** 11 | **Code Lines:** 938 | **Comment Lines:** 25

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 10 | 907 | 25 | 135 | 1,067 |
| TOML | 1 | 31 | 0 | 4 | 35 |


### crates/fig_remote_ipc

**Total Files:** 4 | **Code Lines:** 782 | **Comment Lines:** 18

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 3 | 759 | 18 | 67 | 844 |
| TOML | 1 | 23 | 0 | 2 | 25 |


### crates/aws-toolkit-telemetry-definitions

**Total Files:** 5 | **Code Lines:** 710 | **Comment Lines:** 6

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| JSON | 1 | 426 | 0 | 0 | 426 |
| Rust | 2 | 263 | 6 | 49 | 318 |
| TOML | 1 | 19 | 0 | 4 | 23 |
| Markdown | 1 | 2 | 0 | 1 | 3 |


### crates/fig_request

**Total Files:** 5 | **Code Lines:** 624 | **Comment Lines:** 12

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 4 | 590 | 12 | 91 | 693 |
| TOML | 1 | 34 | 0 | 4 | 38 |


### crates/fig_telemetry_core

**Total Files:** 3 | **Code Lines:** 600 | **Comment Lines:** 13

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 1 | 578 | 13 | 27 | 618 |
| TOML | 1 | 17 | 0 | 1 | 18 |
| Markdown | 1 | 5 | 0 | 4 | 9 |


### crates/shell-color

**Total Files:** 2 | **Code Lines:** 555 | **Comment Lines:** 52

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 1 | 539 | 52 | 62 | 653 |
| TOML | 1 | 16 | 0 | 3 | 19 |


### crates/fig_aws_common

**Total Files:** 5 | **Code Lines:** 489 | **Comment Lines:** 17

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 4 | 469 | 17 | 71 | 557 |
| TOML | 1 | 20 | 0 | 3 | 23 |


### crates/fig_input_method

**Total Files:** 5 | **Code Lines:** 409 | **Comment Lines:** 17

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 4 | 370 | 17 | 61 | 448 |
| TOML | 1 | 39 | 0 | 4 | 43 |


### packages/shared

**Total Files:** 11 | **Code Lines:** 405 | **Comment Lines:** 30

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| TypeScript | 6 | 349 | 29 | 55 | 433 |
| JSON | 3 | 49 | 0 | 0 | 49 |
| JavaScript | 1 | 4 | 1 | 0 | 5 |
| Markdown | 1 | 3 | 0 | 2 | 5 |


### packages/api-bindings-wrappers

**Total Files:** 10 | **Code Lines:** 304 | **Comment Lines:** 15

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| TypeScript | 6 | 252 | 14 | 37 | 303 |
| JSON | 2 | 47 | 0 | 0 | 47 |
| JavaScript | 1 | 4 | 1 | 0 | 5 |
| Markdown | 1 | 1 | 0 | 0 | 1 |


### crates/fig_diagnostic

**Total Files:** 2 | **Code Lines:** 275 | **Comment Lines:** 4

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 1 | 250 | 4 | 31 | 285 |
| TOML | 1 | 25 | 0 | 2 | 27 |


### packages/fuzzysort

**Total Files:** 4 | **Code Lines:** 274 | **Comment Lines:** 55

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| JavaScript | 1 | 207 | 31 | 19 | 257 |
| TypeScript | 1 | 52 | 24 | 11 | 87 |
| JSON | 1 | 13 | 0 | 0 | 13 |
| Markdown | 1 | 2 | 0 | 1 | 3 |


### crates/fig_log

**Total Files:** 2 | **Code Lines:** 247 | **Comment Lines:** 48

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 1 | 226 | 46 | 40 | 312 |
| TOML | 1 | 21 | 2 | 4 | 27 |


### scripts

**Total Files:** 2 | **Code Lines:** 180 | **Comment Lines:** 10

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Shell | 2 | 180 | 10 | 35 | 225 |


### documentation

**Total Files:** 9 | **Code Lines:** 165 | **Comment Lines:** 0

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Markdown | 7 | 88 | 0 | 46 | 134 |
| JSON | 1 | 76 | 0 | 0 | 76 |
| SVG | 1 | 1 | 0 | 0 | 1 |


### packages/eslint-config

**Total Files:** 6 | **Code Lines:** 163 | **Comment Lines:** 21

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| TypeScript | 3 | 106 | 21 | 9 | 136 |
| JSON | 2 | 51 | 0 | 0 | 51 |
| Markdown | 1 | 6 | 0 | 3 | 9 |


### crates/fig_test_utils

**Total Files:** 4 | **Code Lines:** 159 | **Comment Lines:** 28

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 2 | 134 | 28 | 18 | 180 |
| TOML | 1 | 23 | 0 | 3 | 26 |
| Markdown | 1 | 2 | 0 | 2 | 4 |


### crates/fig_test_macro

**Total Files:** 2 | **Code Lines:** 83 | **Comment Lines:** 0

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 1 | 68 | 0 | 12 | 80 |
| TOML | 1 | 15 | 0 | 3 | 18 |


### packages/types

**Total Files:** 2 | **Code Lines:** 72 | **Comment Lines:** 6

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| TypeScript | 1 | 60 | 6 | 3 | 69 |
| JSON | 1 | 12 | 0 | 0 | 12 |


### crates/fig_test

**Total Files:** 2 | **Code Lines:** 49 | **Comment Lines:** 0

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| Rust | 1 | 36 | 0 | 6 | 42 |
| TOML | 1 | 13 | 0 | 2 | 15 |


### packages/tsconfig

**Total Files:** 3 | **Code Lines:** 42 | **Comment Lines:** 0

| Language | Files | Code | Comments | Blank | Total |
|----------|------:|-----:|---------:|------:|------:|
| JSON | 3 | 42 | 0 | 3 | 45 |


## Key Insights

1. **Dominant Language:** Rust accounts for 85.2% of the codebase (235,264 lines)
2. **Largest Component:** crates/amzn-codewhisperer-client contains 23.0% of the codebase (63,434 lines)
3. **Documentation Level:** Comment-to-code ratio is 0.13, indicating moderate code documentation
4. **Language Diversity:** The project uses 13 different programming languages/formats
5. **Rust Crates:** The project contains 38 Rust crates with 239,927 lines of code (86.9%)
6. **TypeScript/JavaScript Packages:** The project contains 12 packages with 26,872 lines of code (9.7%)
7. **Code Density:** 88.1% of non-blank lines are code (vs comments)


## Top 10 Largest Rust Crates

| Crate | Code Lines | Files | Primary Languages |
|-------|------------|-------|-------------------|
| amzn-codewhisperer-client | 63,434 | 602 | TOML, Rust |
| amzn-consolas-client | 32,305 | 300 | TOML, Rust |
| amzn-codewhisperer-streaming-client | 22,471 | 296 | TOML, Rust |
| amzn-qdeveloper-streaming-client | 19,640 | 267 | TOML, Rust |
| zbus | 14,043 | 63 | TOML, Markdown, Rust |
| q_chat | 12,669 | 28 | TOML, Rust, JSON |
| q_cli | 11,892 | 56 | TOML, Rust, Shell |
| fig_desktop | 9,791 | 54 | TOML, Rust, Markdown |
| figterm | 7,157 | 30 | TOML, Markdown, Rust |
| alacritty_terminal | 6,049 | 146 | TOML, Rust, JSON |


## Top 10 Largest TypeScript/JavaScript Packages

| Package | Code Lines | Files | Primary Languages |
|---------|------------|-------|-------------------|
| autocomplete | 6,847 | 60 | JavaScript, TypeScript, JSON |
| autocomplete-app | 6,847 | 60 | JavaScript, TypeScript, JSON |
| dashboard-app | 5,657 | 85 | JavaScript, JSON, Markdown |
| autocomplete-parser | 2,635 | 18 | TypeScript, JSON, Markdown |
| api-bindings | 2,564 | 30 | JSON, Markdown, JavaScript |
| shell-parser | 1,062 | 16 | TypeScript, JSON, Markdown |
| shared | 405 | 11 | TypeScript, JSON, Markdown |
| api-bindings-wrappers | 304 | 10 | JSON, Markdown, JavaScript |
| fuzzysort | 274 | 4 | JSON, Markdown, TypeScript |
| eslint-config | 163 | 6 | JSON, Markdown, TypeScript |


## Methodology

This analysis was performed using a custom Python-based LOC analyzer that:
- Identifies file types by extension
- Distinguishes between code, comments (line and block), and blank lines
- Handles multiple comment styles for different languages
- Excludes build artifacts, dependencies, and generated files
- Groups files by logical components and directories

**Excluded directories:** .cache, .git, .github, .next, .pytest_cache, .turbo, .venv, __pycache__, build, bundle, coverage, dist, env, node_modules, out, target, temp, tmp, venv

**Excluded files:** .dockerignore, .gitignore, .npmignore, Cargo.lock, package-lock.json, pnpm-lock.yaml, yarn.lock


---

*Report generated by LOC Analysis Tool*
