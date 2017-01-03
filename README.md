# Intel Cheat Sheet

## Background

For many years, Intel has been releasing its integrated circuits according to a strategy known as Tick-Tock, where a Tock is a new microarchitecture and a Tick is a die shrink of the current Tock. Each generation is given a codename which, although almost never seen in marketing, is frequently used among enthusiasts. Examples include Sandy Bridge, a new microarchitecture on the 32 nm manufacturing process, released in 2011, and its successor of 2012, Ivy Bridge, which is a 22 nm die shrink of Sandy Bridge.

In each generation, Intel usually segments its processors into workstation/performance (High-End Desktop, HEDT) and mainstream. The latter is then further divided into subsegments marketed as Core i7, Core i5, Core i3, Pentium and Celeron. Within these segments, each SKU is given a model number which will serve as its primary means of identification.

Each generation is usually released alongside a chipset, an IC soldered onto the motherboard and which is central to many aspects of the computer's functionality, such as overclocking, iGPU support and peripheral device connectivity.


## Purpose

The purpose of this table is to provide an overview of the processor generations released by Intel since the introduction of Nehalem in 2008, with focus only on the desktop market (not laptop or server). Nehalem was chosen as the starting point for several reasons:
* It was often seen as the oldest generation that was still somewhat relevant for performance computing as of 2015.
* Offering a wide range of (for Intel CPUs) new functionality such as DDR3, SMT, integrated Northbridge and memory controller, QPI, and L3 cache, it could be considered a distinct starting point of the then current era.
* It introduced the familiar Core i3/i5/i7 naming scheme, so it fits nicely into the table.

The Celeron market segment has been entirely omitted since it was not considered interesting enough to justify the increase in visual complexity caused by including it.


## Interpretation

The cheat sheet presents some essential properties of each generation back to Nehalem as well as its most common SKUs and some basic information about them.

Generation information includes:
* whether it is a Tick or a Tock;
* manufacturing process (lithography);
* codename and (semi-official) abbreviation;
* the most common chipset(s) associated with it, with codename(s); and
* notable examples of SKUs.

Processor information includes:
* model number;
* codename;
* number of cores and threads;
* amount of L3 cache;
* memory configuration (number of channels and memory type); and
* release date (year and quarter).

In addition, the sheet shows socket compatibility.


### Example

![LGA 1155; 2600K "Sandy Bridge" (4C/8T, 8M, 2×DDR3, Q1'11); 3770K "Ivy Bridge" (4C/8T, 8M, 2×DDR3, Q2'12)](https://raw.githubusercontent.com/SimonAlling/intel-cheat-sheet/master/Example-2600K-3770K.png)

From this info, we can tell that the Core i7-2600K:
* is codenamed "Sandy Bridge";
* has four cores with Hyperthreading (SMT) for a total number of eight threads;
* sports 8 MiB (eight mebibytes, abbreviated to 8M for simplicity) of L3 cache;
* supports two channels of DDR3 memory; and
* was released in the first quarter of 2011.

We can also see that, since they lie within the LGA 1155 subtable, 2600K and 3770K are both compatible with that socket. It is also apparent that they are both supported by the Z68 and Z77 chipsets, but that (as indicated by the styling of the chipset names) Z68 was released alongside 2600K and Z77 together with 3770K.


## Usage

It can often be practical to link to or embed the cheat sheet as an image. The latest version will always be available here in these sizes:
* [`ICS100.png`](https://raw.githubusercontent.com/SimonAlling/intel-cheat-sheet/master/ICS100.png) – 100% (3200×841, ~700 KB)
* [`ICS200.png`](https://raw.githubusercontent.com/SimonAlling/intel-cheat-sheet/master/ICS200.png) – 200% (6400×1682, ~2 MB)
* [`ICS400.png`](https://raw.githubusercontent.com/SimonAlling/intel-cheat-sheet/master/ICS400.png) – 400% (12800×3364, ~7 MB)

Please note that the 400% version is generally too large to embed on a discussion board. (It will take around 10 seconds to load it over an 8Mbit/s connection.) Therefore, it is recommended to use the smaller versions for embedding.