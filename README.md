# Homelab

A list of software and hardware I use to keep my curiosity going. Some is used for work. Some is used for fun.

### Software

| Operating Systems | Virtualization Software | Current Projects |
| --- | --- |---|
| [Ubuntu](https://ubuntu.com/)          | [Proxmox](https://www.proxmox.com/en/)                            | [Portainer](https://www.portainer.io/) |
| [Debian](https://www.debian.org/)      | [Docker](https://www.docker.com/)                                 | [Ansible](https://www.ansible.com/) |
| [Alpine](https://www.alpinelinux.org/) | [VMware ESXi](https://www.vmware.com/products/esxi-and-esx.html)  | [Kubernetes](https://kubernetes.io/) |
| [Fedora](https://getfedora.org/)       | [XCP-ng](https://xcp-ng.org/)                                     | [Terraform](https://www.terraform.io/) |
| [CentOS](https://www.centos.org/)      | [Hyper-V Server 2019](https://www.microsoft.com/en-us/evalcenter/evaluate-hyper-v-server-2019) | [Apache](https://apache.org/) |
| [Rocky Linux](https://rockylinux.org/) | [VirtualBox](https://www.virtualbox.org/)                         | [Apache Tomcat](https://tomcat.apache.org/) |
| [openSUSE](https://www.opensuse.org/)  | [LXD](https://linuxcontainers.org/lxd/introduction/)              | [piHole](https://pi-hole.net/) |
| [Windows](https://www.microsoft.com/en-us/windows) (All) |  |  |
| [MacOS](https://www.apple.com/macos/) (VM) |  |  |

## Gear

### Server (pve1)
* 4U Rosewill [RSV-L4000](https://www.rosewill.com/rosewill-rsv-l4000u-black/p/9SIA072GJ92809) Chassis | [ASRock X470D4U](https://www.asrockrack.com/general/productdetail.asp?Model=X470D4U#Specifications)
  * AMD Ryzen™ 7 ([3700X](https://www.amd.com/en/products/cpu/amd-ryzen-7-3700x))
  * 128 GB RAM 4x 32GB DDR4-2666 UDIMM ([CT32G4DFD8266](https://www.crucial.com/memory/ddr4/ct32g4dfd8266))
  * Synology M.2 Adapter Card ([M2D18](https://www.synology.com/en-us/products/M2D18#specs))
  * Boot/OS: 2x Seagate Barracuda 510 500GB (NVMe) ([ZP500CM30001](https://www.seagate.com/support/internal-hard-drives/ssd/barracuda-510-ssd/))
  * SSD: 2x Seagate BarraCuda 120 250GB (SSD) ([ZA250CM10003](https://www.seagate.com/support/internal-hard-drives/ssd/barracuda-120-ssd/))

### Server (pve2)

* 3U Supermicro [SC836](https://www.supermicro.com/manuals/chassis/3U/SC836.pdf) Chassis | Supermicro [X10SRH-CF](https://www.supermicro.com/en/products/motherboard/X10SRH-CF)
  * Intel® Xeon® ([E5-2690 v3](https://www.intel.com/content/www/us/en/products/sku/81713/intel-xeon-processor-e52690-v3-30m-cache-2-60-ghz/specifications.html))
  * 128 GB RAM 2x 64GB Registered ECC LRDIMM, DDR4-2400MHz ([HMAA8GL7MMR4N-TF](https://store.supermicro.com/64gb-ddr4-2133-mem-dr464l-hl01-lr21.html))
  * Synology M.2 Adapter Card ([M2D18](https://www.synology.com/en-us/products/M2D18#specs))
  * Boot/OS: 1 TB Samsung 980 (NVMe) ([MZ-V8V1T0B/AM](https://www.samsung.com/us/computing/memory-storage/solid-state-drives/980-pcie-3-0-nvme-gaming-ssd-1tb-mz-v8v1t0b-am/))
  * SSD0: Crucial MX500 2TB (SSD) ([CT2000MX500SSD1](https://www.crucial.com/ssd/mx500/ct2000mx500ssd1))
  * SSD1: Samsung 850 EVO 500GB (SSD) ([MZ-75E500B/AM](https://www.samsung.com/us/computing/memory-storage/solid-state-drives/ssd-850-evo-2-5-sata-iii-500gb-mz-75e500b-am/))
  * SSD2: Samsung 850 EVO 250GB (M.2 SATA III) ([MZ-N5E250BW](https://www.samsung.com/us/computing/memory-storage/solid-state-drives/ssd-850-evo-m-2-250gb-mz-n5e250bw/#specs))

### Server (down for repairs)
* 2U Chassis Supermicro [SC825](https://www.supermicro.com/manuals/chassis/2U/SC825.pdf) | Supermicro [X8DTi-F](https://www.supermicro.com/manuals/motherboard/5500/MNL-1062.pdf)
  * 2x Intel® Xeon® ([L5640](https://ark.intel.com/content/www/us/en/ark/products/47926/intel-xeon-processor-l5640-12m-cache-2-26-ghz-5-86-gts-intel-qpi.html))
  * 32 GB RAM DDR3

### NAS (RackStation)
* 2U Chassis Synology [RS3617xs](https://global.download.synology.com/download/Document/Hardware/DataSheet/RackStation/17-year/RS3617xs/enu/Synology_RS3617xs_Data_Sheet_enu.pdf)
  * Volume 1: 4x Western Digital 1TB WD Red (SSD) ([WDS100T1R0A](https://www.westerndigital.com/products/internal-drives/wd-red-sata-2-5-ssd#WDS100T1R0A))
  * Volume 2: 4x Western Digital 10TB WD Gold Enterprise (SSD) ([WD102KRYZ](https://www.westerndigital.com/products/internal-drives/wd-gold-sata-hdd#WD102KRYZ))
  * Volume 3: 4x Western Digital 10TB WD Gold Enterprise (SSD) ([WD102KRYZ](https://www.westerndigital.com/products/internal-drives/wd-gold-sata-hdd#WD102KRYZ))

### Networking
* [Ubiquiti](https://www.ui.com/)
  * Cloud Key Gen2 Plus ([UniFi-CloudKey-Gen2-Plus](https://store.ui.com/products/unifi-cloudkey-plus))
  * Security Gateway ([USG-3P](https://store.ui.com/products/unifi-security-gateway))
  * Switch 48 ([US-48-G1](https://store.ui.com/collections/unifi-network-switching/products/unifi-switch-48))
  * Switch Flex Mini ([USW-Flex-Mini](https://store.ui.com/products/usw-flex-mini))
  * Access Point AC Long-Range ([UAP-AC-LR](https://store.ui.com/products/unifi-ac-lr))
  * 2 x Access Point AC Pro ([UAP-AC-Pro](https://store.ui.com/products/uap-ac-pro))

### Additional Hardware
* StarTech.com 42U 19" Open Frame Server Rack ([4POSTRACK42](https://www.startech.com/en-us/server-management/4postrack42))
* 12-Port Gigabit Passive Rack Mount PoE Injector ([GPOE-12AB-48v120w](https://shop.poetexas.com/products/gpoe-12-48v120w))