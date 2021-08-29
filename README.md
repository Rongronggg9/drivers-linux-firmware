Updated drivers from Linux-Firmware for Debian/Ubuntu (29-08-2021)
==================================================================

### Download:

  * **Debian `Buster`/`Bullseye` or Ubuntu `18.04`/`18.10`/`19.04`/`19.10`/`20.04`/`20.10`/`21.04`:**

    * [`drivers-linux-firmware_20210829-1_all.deb`](https://github.com/q3aql/drivers-linux-firmware/releases/download/v21.0/drivers-linux-firmware_20210829-1_all.deb)

_Important: It is recommended to use kernel 4.15 or higher._

### Old downloads:

  * [`drivers-linux-firmware_20210727-1_all.deb`](https://github.com/q3aql/drivers-linux-firmware/releases/download/v20.0/drivers-linux-firmware_20210727-1_all.deb)
  * [`drivers-linux-firmware_20210604-1_all.deb`](https://github.com/q3aql/drivers-linux-firmware/releases/download/v19.0/drivers-linux-firmware_20210604-1_all.deb)
  * [`drivers-linux-firmware_20210327-1_all.deb`](https://github.com/q3aql/drivers-linux-firmware/releases/download/v18.0/drivers-linux-firmware_20210327-1_all.deb)
  * [`drivers-linux-firmware_20210222-1_all.deb`](https://github.com/q3aql/drivers-linux-firmware/releases/download/v17.0/drivers-linux-firmware_20210222-1_all.deb)
  * [`drivers-linux-firmware_20201004-1_all.deb`](https://github.com/q3aql/drivers-linux-firmware/releases/download/v16.0/drivers-linux-firmware_20201004-1_all.deb)


### Important:

  * To ensure package compatibility with Debian and Ubuntu at the same time, but also not to conflict with other packages, the drivers directory is located at `/opt/drivers-linux-firmware/` instead of `/lib/firmware/`.
  * If you want to add new modules, firmwares or drivers, they should always be left in the directory `/opt/drivers-linux-firmware/` and then execute the following command:

    * `$ sudo drivers-linux-firmware`

  * After executing the above command, all files will be synced to the `/lib/firmware/` directory. In case of not executing the command manually, it will be executed automatically every hour.

### External links:

  * [Git linux-firmware](https://git.kernel.org/pub/scm/linux/kernel/git/firmware/linux-firmware.git)
  * [Git Kernel.org](https://git.kernel.org/)
