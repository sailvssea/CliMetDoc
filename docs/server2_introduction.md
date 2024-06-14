# Server Introduction

## Server

<div class="grid cards" markdown>

- :octicons-cpu-16:{ .lg .middle } __CPU Information__ (1)
  { .annotate }

      1.  using `#!bat lscpu` to get the cpu information, and `#!bat nproc` to get the number of process units.

      ---

      - :material-clock-fast: Model: Intel(R) Xeon(R) Glod 6326 CPU @ 2.90GHz
      - :material-clock-fast: Architecture: x86_64
      - :material-clock-fast: Number of process units: 64
      - :material-clock-fast: Threads per core: 2
      - :material-clock-fast: Cores per socket: 16
      - :material-clock-fast: Sockets: 2

      ---

- :simple-nvidia:{ .lg .middle } __GPU Information__ (1)
  { .annotate }

      1. using `#!bat nvidia-msi` to get the gpu information

      ---

      - :octicons-video-16: Model: NVIDIA A40
      - :octicons-video-16: Number of Graphic Cards: 2
      - :octicons-video-16: Size per cards: 48G
      - :octicons-video-16: Driver Version: 535.171.04
      - :octicons-video-16: CUDA Version: 12.2

      ---

- :material-harddisk:{ .lg .middle } __Storage Information__ (1)
  { .annotate }

      1. using `#!bat df -h` to get the disk storage information

      ---

      - :fontawesome-solid-floppy-disk: system on 2T SSD with 1T RAM
      - :fontawesome-solid-floppy-disk: workspace on 15T SSD (RAID5)
      - :fontawesome-solid-floppy-disk: workspace1 on 28T SSD (RAID5)

      ---

  </div>

??? tip "Detailed Disk Configuration"
    <div class="result" markdown>
    ![diskstorage](img/CliMetServerDisk_forServer2.png "diskstorage"){width="1000"}
    </div>

## Server Account

Please contact [Jesse](mailto:jessellyu@ust.hk) to request your server account.
