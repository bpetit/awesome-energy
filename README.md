# ICT focussed power/energy publications, documentations and tools

Based on my personnal researches. For environmental impact of ICT (final energy/electricity not being an environmental metric), see [Boavizta's blog](https://boavizta.org/en/blog).

## ICT energy consumption

### Publications

- [The Problem of Power Consumption in Servers](https://www.infoq.com/articles/power-consumption-servers/) - 2009
- [PowerAPI: A Software Library to Monitor the Energy Consumed at the Process-Level](https://ercim-news.ercim.eu/en92/special/powerapi-a-software-library-to-monitor-the-energy-consumed-at-the-process-level)
- [VMeter (research paper): Power modelling for virtualized clouds](https://ieeexplore.ieee.org/document/5470907)
- [Measure the server-side impact of your application with PowerAPI - Blog Theodo](https://blog.theodo.com/2020/05/greenit-measure-server-energy-consumption-powerapi/)
- [WattsKit: Software-Defined Power Monitoring of Distributed Systems](https://hal.inria.fr/hal-01439889)
- [Energy Aware Scheduling (EAS) in Linux 5.0](https://community.arm.com/developer/ip-products/processors/b/processors-ip-blog/posts/energy-aware-scheduling-in-linux)
- [Energy Aware Scheduling - The Linux Kernel Documentation](https://www.kernel.org/doc/html/v5.5-rc2/scheduler/sched-energy.html)
- [Device Power Management Basics - The Linux Kernel Documentation](https://www.kernel.org/doc/html/v4.14/driver-api/pm/devices.html)
- [Power Management - The Linux Kernel Documentation](https://www.kernel.org/doc/html/latest/power/index.html)
- [Energy models of CPUs - The Linux Kernel Documentation](https://www.kernel.org/doc/html/latest/power/energy-model.html)
- [Kernel driver power_meter](https://www.kernel.org/doc/html/latest/hwmon/acpi_power_meter.html)
- [Pour une sobriété numérique - The Shift Projectl](https://theshiftproject.org/article/pour-une-sobriete-numerique-rapport-shift/)
- [http://gauthierroussilhe.com/fr/posts/convert-low-tech](http://gauthierroussilhe.com/fr/posts/convert-low-tech#energy)
- [Data Centres and Data Transmission Networks](https://www.iea.org/reports/data-centres-and-data-transmission-networks#resources)
- [The carbon footprint of streaming video: fact-checking the headlines](https://www.iea.org/commentaries/the-carbon-footprint-of-streaming-video-fact-checking-the-headlines)
- [Digitalization and energy](https://www.iea.org/reports/digitalisation-and-energy)
- [MOOC INR - Sensibilisation au numérique responsable](https://www.academie-nr.org/sensibilisation/#/)
- [Green is the new web - Medium Ippon](https://medium.com/ippon/green-is-the-new-web-75d56226a4b)
- [Concilier architecture data et écologie - Blog Ippon](https://blog.ippon.fr/2019/12/16/concilier-architecture-data-et-ecologie-cest-possible-une-introduction-au-green-it/)
- [Green Data is the new Big Data](https://www.youtube.com/watch?v=gIb2KeSINp4)
- [La sobriété numérique oui mais pourquoi faire ?](https://signal.eu.org/blog/2020/07/15/la-sobriete-numerique-oui-mais-pour-quoi-faire/)
- [The Entire World's Carbon Emissions Will Finally Be Trackable In Real Time ](https://news.slashdot.org/story/20/07/17/2057205/the-entire-worlds-carbon-emissions-will-finally-be-trackable-in-real-time)

### Organizations

- [GreenIT](https://www.greenit.fr/)
- [all2all](http://www.all2all.org)
- [Greenlab](https://greenlab.di.uminho.pt/)
- [Spirals](https://team.inria.fr/spirals/)
- [The Shift Project](https://theshiftproject.org/)
- [Boavizta](https://boavizta.org/en)

### Companies

- [Greenspector](https://greenspector.com/en/home/)
- [EcoHost: Premium Eco-Friendly Website Hosting](https://www.eco-host.co/)
- [Infomaniak](https://www.infomaniak.com)
- [Aiso](https://www.aiso.net/)
- [GreenGeeks](https://www.greengeeks.com/)
- [Datacenterlight](https://datacenterlight.ch/) + [Ungleich](https://ungleich.ch/)
- [Datafarm](https://datafarm.io/)
- [Hubblo](https://hubblo.org)
- [Easyvirt](https://www.easyvirt.com/)
- [Sopht](https://sopht.com/)

### Energy production and smart grids

- [Stanford bits and watts program publications](https://energy.stanford.edu/bitsandwatts/research/publications)

### Tech blog posts

- [Firefox 104 energy measurements - Green Coding Berlin](https://www.green-coding.org/blog/firefox-104-energy-measurements/)

## Measure power with a physical device

- [Apprenez à utiliser l'api locale Philips Hue... - NextImpact](https://www.nextinpact.com/article/66882/apprenez-a-utiliser-api-locale-philips-hue-et-a-utiliser-dans-premier-script-python)
- [Retour sur la gamme Hue Philips et quelques applications... - NextImpact](https://www.nextinpact.com/article/66883/retour-sur-gamme-hue-philips-et-quelques-applications-creees-par-communaute)
- [Best smart plug for energy monitoring with api - Reddit](https://www.reddit.com/r/homeautomation/comments/f87iho/best_smart_plug_for_energy_monitoring_with_api/)

## Measure power usage by software

### GNU/Linux

#### Tools

- [PowerAPI (software)](https://powerapi-ng.github.io): middleware toolkit for building software-defined power meters
- [Bittwatts (software)](https://github.com/Spirals-Team/bitwatts): software-defined power meter for virtualized environments
- [Hwloc tutorial](https://www.open-mpi.org/projects/hwloc/tutorials/20120702-POA-hwloc-tutorial.html): hierarchical view of the machine (useful to spot consumption improvements)
- [Intel PCM](https://software.intel.com/content/www/us/en/develop/articles/intel-performance-counter-monitor.html)
- [Reading RAPL energy measurements from Linux](http://web.eece.maine.edu/~vweaver/projects/rapl/)
- [Intel® 64 and IA-32 Architectures Software Developer Manuals](https://software.intel.com/content/www/us/en/develop/articles/intel-sdm.html)
- [PAPI](https://icl.utk.edu/papi/), [source](https://bitbucket.org/icl/papi/src/master/) and its [manual](https://linux.die.net/man/3/papi)
- [RAPL msr interface](https://community.intel.com/t5/Software-Tuning-Performance/RAPL-MSR-Interface/td-p/938123)
- [Brendan Gregg's insights](http://www.brendangregg.com/linuxperf.html)
- [perfmon2](http://perfmon2.sourceforge.net/)
- [Colin Ian King's power management tools (including powerstat)](https://launchpad.net/~colin-king/+archive/ubuntu/powermanagement)
- [s-tui](https://github.com/amanusk/s-tui)
- [Intel Power Gadget](https://software.intel.com/content/www/us/en/develop/articles/intel-power-gadget.html#attachment-heading)
- [energymon](https://github.com/energymon/energymon)
- [codecarbon](https://github.com/mlco2/codecarbon): python library to measure CPU/GPU consumption of machine learning or any ressource intensive python code
- [hostghost](https://gitlab.com/localg-host/hostghost): to measure power consumption thanks to wattmeter and raspberry pi
- [scaphandre](https://github.com/hubblo-org/scaphandre/): Electrical power consumption metrology agent. Let scaph dive and bring back the metrics that will help you make your systems and applications more sustainable !
- [arduino wattmeter](https://circuitdigest.com/microcontroller-projects/arduino-wattmeter-to-measure-voltage-current-power-consumption)
- [Green metrics tools from Green Coding Berling](https://github.com/green-coding-berlin/green-metrics-tool)
- [Sentry Hardware OpenTelemetry Collector](https://www.sentrysoftware.com/docs/hws-otel-collector/2.0.00/index.html)

#### Internals

##### RAPL

- [Structured explanations from Scaphandre documentation](https://hubblo-org.github.io/scaphandre-documentation/explanations/about-containers.html)
- [Running Average Power Limit – RAPL](https://01.org/blogs/2014/running-average-power-limit-%E2%80%93-rapl)
- [RAPL, DRAM and PCM](https://community.intel.com/t5/Software-Tuning-Performance/RAPL-DRAM-and-PCM/td-p/942608)
- [RAPL for energy measurements](https://community.intel.com/t5/Software-Tuning-Performance/RAPL-for-energy-measurement/td-p/919723)
- [RAPL: memory power estimation and capping](https://dl.acm.org/doi/10.1145/1840845.1840883)
- [Understanding Intel's RAPL driver on Linux](https://www.phoronix.com/scan.php?page=news_item&px=MTcxMjY)
- [Intel Introduces PowerClamp Driver For Linux](https://www.phoronix.com/scan.php?page=news_item&px=MTIyOTE)
- [Linux kernel archive: RAPL (Running Average Power Limit) driver](http://lkml.iu.edu/hypermail/linux/kernel/1304.0/01322.html)
- [Turbostat manpage](https://www.linux.org/docs/man8/turbostat.html)
- [https://zhenkai-zhang.github.io/papers/rapl.pdf](https://zhenkai-zhang.github.io/papers/rapl.pdf)
- Scaphandre issues/threads about RAPL : [116](https://github.com/hubblo-org/scaphandre/issues/116), [241](https://github.com/hubblo-org/scaphandre/issues/241), [140](https://github.com/hubblo-org/scaphandre/issues/140), [289](https://github.com/hubblo-org/scaphandre/issues/289), [117](https://github.com/hubblo-org/scaphandre/issues/117), [25](https://github.com/hubblo-org/scaphandre/issues/25), [316](https://github.com/hubblo-org/scaphandre/issues/316), [318](https://github.com/hubblo-org/scaphandre/issues/318)

##### RAPL PSYS Domain (WIP)

- [Kepler documentation](https://sustainable-computing.io/design/metrics/) says PSYS "is the energy consumed by the "System on a chipt" (SOC)."
"Generally, this metric is the host energy consumption (from acpi)." but also "Generally, this metric is the **host energy consumption (from acpi) less the RAPL Package and DRAM**."
- [https://www.arcsi.fr/doc/platypus.pdf](https://www.arcsi.fr/doc/platypus.pdf) says PSYS is "covering the entire SoC.".
- http://www.micheledellipaoli.com/documents/EnergyConsumptionAnalysis.pdf says "PSys: (introduced with Intel Skylake) monitors and controls the thermal and power specifications of the entire SoC and it is useful especially when the source of the power consumption is neither the CPU nor the GPU. For multi-socket server systems, each socket reports its own RAPL values."
- https://hal.science/hal-03809858/document says "PSys. Domain available on some Intel architectures, to monitor and control the thermal end power specifications of the entire system on the chip (SoC), instead of just CPU or GPU. It includes the power consumption of the package domain, System Agent, PCH, eDRAM, and a few more domains on a single-socket SoC"
- PSYS MSR is "MSR_PLATFORM_ENERGY_STATUS" : https://copyprogramming.com/howto/perf-power-consumption-measure-how-does-it-work
- https://pyjoules.readthedocs.io/en/stable/devices/intel_cpu.html
- Problems of RAPL on Saphire Rapids : https://community.intel.com/t5/Software-Tuning-Performance/RAPL-quirks-on-Sapphire-Rapids/td-p/1446761
- Misc info on RAPL: https://web.eece.maine.edu/~vweaver/projects/rapl/
- PSYS MSR have a different layout than PKG and dram : https://patchwork.kernel.org/project/linux-pm/patch/20211207131734.2607104-1-rui.zhang@intel.com/
- https://edc.intel.com/content/www/us/en/design/ipla/software-development-platforms/client/platforms/alder-lake-desktop/12th-generation-intel-core-processors-datasheet-volume-1-of-2/010/power-management/ ==> intel doc about thermal and power management
- https://edc.intel.com/content/www/us/en/design/ipla/software-development-platforms/client/platforms/alder-lake-desktop/12th-generation-intel-core-processors-datasheet-volume-1-of-2/002/platform-power-control/ ==> about psys
https://www.intel.com/content/www/us/en/developer/articles/technical/intel-sdm.html ==> intel software developer manual
- CVE-8694/8695 and mitigation by intel : https://www.intel.com/content/www/us/en/developer/articles/technical/software-security-guidance/advisory-guidance/running-average-power-limit-energy-reporting.html
- Patch in the kernel: https://groups.google.com/g/linux.kernel/c/x_7RbqcrxAs
- Patch in powercap: https://lkml.iu.edu/hypermail/linux/kernel/1603.2/02415.html and https://lkml.kernel.org/lkml/1460930581-29748-1-git-send-email-srinivas.pandruvada@linux.intel.com/T/
- Random: https://stackoverflow.com/questions/55956287/perf-power-consumption-measure-how-does-it-work

##### RAPL MMIO

- [MMIO on wikipedia](https://en.wikipedia.org/wiki/Memory-mapped_I/O_and_port-mapped_I/O)
- [early 2023 patch for MMIO that affects RAPL](https://lwn.net/Articles/929547/)
- [Explanations on TPMI driver](https://www.phoronix.com/news/Intel-TPMI-Linux-Driver)

### Windows

#### Tools

- [Energy Meter Interface](https://docs.microsoft.com/en-us/windows-hardware/drivers/powermeter/energy-meter-interface)
- [Windows RAPL (MSR) Driver](https://github.com/hubblo-org/windows-rapl-driver/)

### MacOS

#### Internals

- [Task info code should give access to data per process](https://github.com/apple/darwin-xnu/blob/8f02f2a044b9bb1ad951987ef5bab20ec9486310/osfmk/mach/task_info.h#L464)
- [How firefox uses task info](https://hg.mozilla.org/mozilla-central/file/tip/tools/profiler/core/PowerCounters-mac.cpp#l35)

### Bulk links (WIP) for estimating power usage of other components than CPU/RAM/GPU

#### Disks (ssd/hdd/nvme)

- https://www.infoq.com/articles/power-consumption-servers/
- [Description of SSDs and HDDs power usage mechanics](https://superuser.com/questions/1545690/why-do-2-5-ssds-use-more-power-than-2-5-hdds)
- https://computerhardwareparts.com/ssd-vs-hdd-power-consumption/
- [Be careful to disk states/activity](https://superuser.com/questions/565653/how-much-power-does-a-hard-drive-use)
- https://www.anandtech.com/show/6725/the-full-intel-ssd-525-review-30gb-60gb-120gb-180gb-240gb-tested/7
- https://innobytech.com/does-ssd-need-power/
- https://devicetests.com/how-many-watts-does-an-ssd-use
- https://digitalworld839.com/hdd-vs-ssd-power-consumption/
- https://computerhardwareparts.com/ssd-vs-hdd-power-consumption/
- https://www.officexpress.fr/pdf-techdoc/256SSD370.pdf

## Improve energy measurements/estimations : collaborative science

- [Energizta project](https://github.com/Boavizta/Energizta/)
