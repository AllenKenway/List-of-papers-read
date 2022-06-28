# List-of-papers-read

## linux
+ An Analysis of Performance Evolution of Linux's Core Operations. SOSP(2019) [[pdf]](https://dl.acm.org/doi/10.1145/3341301.3359640) [[slides]](https://sosp19.rcs.uwaterloo.ca/slides/ren.pdf) [[video]](https://sosp19.rcs.uwaterloo.ca/videos/D3-S3-P1.mp4) [[github]](https://github.com/LinuxPerfStudy/LEBench)

## scheduler
+ Exploiting FIFO Scheduler to Improve Parallel Garbage Collection Performance. VEE(2016) [[pdf]](https://dl.acm.org/doi/10.1145/3007611.2892248) [[github]](https://github.com/junjieqian/ARES)
+ Arachne: Core-Aware Thread Management. OSDI(2018) [[pdf]](https://www.usenix.org/conference/osdi18/presentation/qin) [[slides]](https://www.usenix.org/sites/default/files/conference/protected-files/osdi18_slides_qin.pdf) [[github]](https://github.com/PlatformLab/Arachne)
+ Resource Efficient Stream Processing Platform with Latency-Aware Scheduling Algorithms. HotCloud(2020) [[pdf]](https://www.usenix.org/conference/hotcloud20/presentation/morisawa) [[slides]](https://www.usenix.org/system/files/hotcloud20-paper67-slides-morisawa.pdf) [[video]](https://www.youtube.com/watch?v=mjzyc16FYC8&ab_channel=USENIX)
+ Provable Multicore Schedulers with Ipanema:Application to Work Conservation. EuroSys(2020) [[pdf]](https://dl.acm.org/doi/abs/10.1145/3342195.3387544) [[slides]](https://www.eurosys2020.org/wp-content/uploads/2020/04/slides/411_lepers_slides.pdf) [[video]](https://www.youtube.com/watch?v=6xA4Z6_0diI&ab_channel=EuroSys2020Conference)
+ The Linux Scheduler a Decade of Wasted Cores. EuroSys(2016) [[pdf]](https://dl.acm.org/doi/10.1145/2901318.2901326)
+ The Battle of the Schedulers FreeBSD ULE vs. Linux CFS. ATC(2018) [[pdf]](https://www.usenix.org/conference/atc18/presentation/bouron) [[slides]](https://www.usenix.org/sites/default/files/conference/protected-files/atc18_slides_bouron.pdf)
+ FLsched: A Lockless and Lightweight Approach to OS Scheduler for Xeon Phi. APSys(2017) [[pdf]](https://dl.acm.org/doi/abs/10.1145/3124680.3124724)
+ Towards achieving fairness in the Linux scheduler. ACM(2008) [[pdf]](https://dl.acm.org/doi/abs/10.1145/1400097.1400102)
+ Linux 调度器免锁优化方法研究. 小型微型计算机系统(2017) [[pdf]](http://xwxt.sict.ac.cn/CN/Y2017/V38/I4/690)
+ Linux 内核完全公平调度器改进的研究. 计算机工程与应用(2014) [[pdf]](http://cea.ceaj.org/CN/abstract/abstract32511.shtml)
+ SmartHarvest:harvesting idle CPUs safely and efficiently in the cloud. EuroSys(2021) [[pdf]](https://dl.acm.org/doi/10.1145/3447786.3456225) [[slides]](https://2021.eurosys.org/docs/presentations/4-wang%20-%20Yawen%20Wang.pdf) [[video]](https://www.youtube.com/watch?v=bEtO5oKMMlk&list=PLzDuHU-z7gNjuSbEYCFXZtWAl3nAdNF2f&index=20&ab_channel=%EC%9E%84%ED%9C%98%EC%A4%80)
+ ghOSt: Fast & Flexible User-Space Delegation of Linux Scheduling. SOSP(2021). [[pdf]](https://dl.acm.org/doi/10.1145/3477132.3483542) [[slides]](https://netdevconf.info/0x15/slides/25/ghOSt%20Talk%20(Netdev).pdf) [[video]](https://www.youtube.com/watch?v=j4ABe4dsbIY) [[github]](https://github.com/google/ghost-kernel)

## CPU Frequencies 
+ Fewer Cores, More Hertz:Leveraging High-Frequency Cores in the OS Scheduler for Improved Application Performance. ATC(2020) [[pdf]](https://www.usenix.org/conference/atc20/presentation/gouicern) [[slides]](https://www.usenix.org/system/files/atc20-paper683-slides-gouicem.pdf) [[video]](https://www.youtube.com/watch?v=UCBJLTmzpwE&ab_channel=USENIX)
+ Fair Scheduling for AVX2 and AVX-512 Workloads. ATC(2021) [[PDF]](https://www.usenix.org/system/files/atc21-gottschlag.pdf) [[slides]](https://www.usenix.org/system/files/atc21_slides_gottschlag.pdf)
+ Automatic Core Specialization for AVX-512 Applications. SYSTOR(2020) [[PDF]](https://dl.acm.org/doi/10.1145/3383669.3398282) [[slides]](https://www.systor.org/2020/slides/Automatic_Core_Specialization_for_AVX-512_Applications.pdf)
+ OS scheduling with nest:keeping tasks close together on warm cores. EuroSys(2022) [[PDF]](https://dl.acm.org/doi/pdf/10.1145/3492321.3519585)

## GC
+ Platinum: A CPU-Efficient Concurrent Garbage Collector for Tail-Reduction of Interactive Services. ATC(2020) [[pdf]](https://www.usenix.org/conference/atc20/presentation/wu-mingyu) [[slides]](https://www.usenix.org/system/files/atc20-paper758-slides-wu.pdf) [[video]](https://www.youtube.com/watch?v=PjuEN8SxhN0&ab_channel=USENIX)

## syscall
+ Draco: Architectural and Operating System Support for System Call Security. MICRO(2020) [[pdf]](https://www.microarch.org/micro53/papers/738300a042.pdf) [[video]](https://www.youtube.com/watch?v=wvBTGqun7XY&ab_channel=MICROSymposium)

## container
+ X-Containers: Breaking Down Barriers to Improve Performance and Isolation of Cloud-Native Containers. ASPLOS(2019) [[pdf]](https://dl.acm.org/doi/abs/10.1145/3297858.3304016) [[video]](https://www.youtube.com/watch?v=OxAFxS-NgyE&ab_channel=ZhimingShen)
+ Blending Containers and Virtual Machines: A Study of Firecracker and gVisor. VEE(2020) [[pdf]](https://dl.acm.org/doi/abs/10.1145/3381052.3381315) [[slides]](https://research.cs.wisc.edu/multifacet/papers/vee20_blending_talk.pdf) [[video]](https://www.youtube.com/watch?v=qSXbsdr08CQ&ab_channel=ACMSIGOPS)
+ Abusing Privileged and Unprivileged Linux Containers. NCC Group(2016) [[pdf]](https://www.nccgroup.com/ae/our-research/abusing-privileged-and-unprivileged-linux-containers/)
+ Real-Time Containers: A Survey. Fog-IoT(2020) [[pdf]](https://drops.dagstuhl.de/opus/volltexte/2020/12001/pdf/OASIcs-Fog-IoT-2020-7.pdf)
+ Container-based real-time scheduling in the Linux kernel. EWiLi(2018) [[pdf]](https://dl.acm.org/doi/10.1145/3373400.3373405)

## basic
+ A Survey on Fairness and Performance Analysis of Completely Fair Scheduler in Linux Kernel. (2016) [[pdf]](https://www.researchgate.net/publication/318983876_A_Survey_on_Fairness_and_Performance_Analysis_of_Completely_Fair_Scheduler_in_Linux_Kernel)
+ Fairness and interactive performance of O(1) and CFS Linux kernel schedulers. IEEE(2008) [[pdf]](https://ieeexplore.ieee.org/abstract/document/4631872)
+ A Comparison of Two Linux Schedulers. (2012) [[pdf]](https://www.duo.uio.no/bitstream/handle/10852/9093/2/cheng.pdf)

## RT-Linux
+ Using real-time linux.
+ The Real-Time Linux Kernel: A Survey on PREEMPT_RT. ACM Comput. Surv(2019). [[pdf]](https://dl.acm.org/doi/fullHtml/10.1145/3297714)
+ Benchmarking Real Time Operating Systems. [[slides]](https://amdls.dorsal.polymtl.ca/files/RTOS%20%20Benchmarking.pdf)
+ Long-term monitoring of apparent latency in PREEMPT_RT Linux real-time systems. OSADL(2010). [[pdf]](https://www.osadl.org/fileadmin/dam/articles/Long-term-latency-monitoring.pdf)
+ Challenges Using Linux as a Real-Time Operating System.  AIAA(2019). [[pdf]](https://ntrs.nasa.gov/api/citations/20200002390/downloads/20200002390.pdf)
+ A state-of-the-art survey on real-time issues in embedded systems virtualization. Journal of Software Engineering and Applications(2012). [[pdf]](https://www.scirp.org/html/7-9301356_18574.htm)


## RT-VM
+ Using KVM as a Real-Time Hypervisor. KVM Forum(2011). [[slides]](https://www.linux-kvm.org/images/0/03/KVM-Forum-2011-RT-KVM.pdf)
+ Real-time KVM from the ground up. KVM Forum(2015). [[slides]](https://wiki.linuxfoundation.org/_media/realtime/events/rt-summit2016/kvm_rik-van-riel.pdf)
+ Using Xen and KVM as real-time hypervisors. Journal of Systems Architecture(2020). [[pdf]](https://www.sciencedirect.com/science/article/pii/S1383762120300035)
+ Towards Linux as a Real-Time Hypervisor. 11th Real-Time Linux Workshop(2009). [[pdf]](https://static.lwn.net/images/conf/rtlws11/papers/proc/p18.pdf)
+ Risa:A Real-time Scheduling Framework Based on Multi-core Dynamic Partitioning in Virtualized Environment. NPC(2014). [[pdf]](http://cgcl.grid.hust.edu.cn/wusong/file/NPC14.pdf)
+ Poris: A Scheduler for Parallel Soft Real-Time Applications in Virtualized Environments. Preliminary version in MASCOTS(2013). [[pdf]](http://cgcl.grid.hust.edu.cn/wusong/file/TPDS(Zhou).pdf)
+ Doris: an adaptive soft real-time scheduler in virtualized environments. IEEE Trans. Serv. Comput. (2017). [[pdf]](https://ieeexplore.ieee.org/document/7961215)
+ Performance analysis towards a KVM-Based embedded real-time virtualization architecture. J. Inf. Sci. Eng.(2013). [[pdf]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=5711095)
+ Challenges in real-time virtualization and predictable cloud computing. Journal of Systems Architecture(2014). [[pdf]](https://www.sciencedirect.com/science/article/pii/S1383762114001015)



[[pdf]]()