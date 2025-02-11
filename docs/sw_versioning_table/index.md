Software Distros
===

## 🚀 Software Distros Workflow
- 📅 SW Distros are delivered on a **time-based workflow**.
- 4️⃣ SW Distros are released along with **binaries** at the following quarters: **Feb, May, Aug, Nov**.
- 🆓 The feature-freeze lasts **one month**.
- 📛 Naming convention adheres therefore to **YYYY.MM**: e.g. 2020.02, 2020.05...
- 📝 Repositories stay on their usual release convention in order to enable proper **semantic versioning**. To link repos tags to SW Distro and run CI, we rely on the infrastructure provided in [`robotology/robotology-superbuild`](https://github.com/robotology/robotology-superbuild).
- 📦 Occasionally, we may deliver **feature-based releases** (only tags/branches, no binaries) as **YYYY.MM.feat-nn**.
- 🐞 **Patches** are coded as **YYYY.MM.patch-nn** and, like the feature-based releases, are shipped only in terms of tags/branches.
- 📢 We make **announcements** of the distros and their content on a dedicated channel of [Robotology Community](https://github.com/robotology/community/discussions/categories/releases).

## Software Versioning Table
The table hereinafter reports on the versions of the packages (specified in terms of Git tags/branches/commits)
composing our software ecosystem that are bundled as distros.

Once the versions are known, one can download the distro's source code by using Git.

For example, to download the SW Distro `2020.08` do:
```sh
$ git clone https://github.com/robotology/ycm.git -b v0.11.3
$ git clone https://github.com/robotology/yarp.git -b v3.4.0
$ git clone https://github.com/robotology/icub-main.git -b v1.17.0
 ...
```

## Table
This table has been generated automatically by processing data available in [`robotology/robotology-superbuild@v2021.08/releases`](https://github.com/robotology/robotology-superbuild/tree/v2021.08/releases).

Click on the distros below to explore their package versions:

- [📦 Distro **2021.08**](./2021.08.md)
- [📦 Distro **2021.05**](./2021.05.md)
- [📦 Distro **2021.02**](./2021.02.md)
- [📦 Distro **2021.02.feat-01**](./2021.02.feat-01.md)
- [📦 Distro **2020.11**](./2020.11.md)
- [📦 Distro **2020.08**](./2020.08.md)
- [📦 Distro **2020.08.patch-01**](./2020.08.patch-01.md)
- [📦 Distro **2020.08.feat-01**](./2020.08.feat-01.md)
- [📦 Distro **2020.05**](./2020.05.md)
- [📦 Distro **2020.05.feat-01**](./2020.05.feat-01.md)
- [📦 Distro **2020.02**](./2020.02.md)
