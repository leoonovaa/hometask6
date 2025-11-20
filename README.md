# Anna Leonova 4CS-32
# hometask6

**Topic:** Vagrant VM provisioning + attaching extra disks + LVM configuration  Objective

* Creates and attaches 4 extra HDDs, each 400MB
* Creates a primary partition on each disk using parted script
* Creates single volume group
* Configures two LVM volumes, each 750MB
* Mount each volume into /mnt/vol0 /mnt/vol1

Steps to Run

**Step 1 — Start the Vagrant VM**

            vagrant up

**Step 2 — SSH into the VM**

            vagrant ssh

**Step 3 — Verify disks, partitions, and LVM**

            lsblk

**Step 4 — Verify mount points**

            df -h

**Step 5 — Verify fstab configuration**

            cat /etc/fstab
