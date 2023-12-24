# "Reset" this PC

What it does: removes all personal files and settings, and **reset** windows as if it were brand new.

# Creating a "restore point"

What it does: Rolls back the **Windows registry** to a previous checkpoint.

When to use: create a **restore point** when you are about to make a Windows-level change. Eg:

* installing new network adapters

* installing a new program

* playing with sus settings

* etc.

NOTE: **restore points** take up space in the hard drive.

NOTE: **System Protection** should be "on" if you want Windows to create **restore points** automatically.

# Creating a "recovery drive"

When to use:

* in case of hardware failure
* when your PC cannot boot up
* when windows cannot fix itself

What it does: stores a copy of Windows OS on an external USB/DVD.

NOTE: Personal files and apps that did not come with the OS will not be coming along for the ride

NOTE: Make sure you use an empty USB/DVD with atleast 16 GB capacity.

NOTE: If you had previously partitioned your drive, the drive will be restored to its original state (whatever it was). You will have to set up the partitions again.

Official article on [creating a recovery drive](https://support.microsoft.com/en-us/windows/create-a-recovery-drive-abb4691b-5324-6d4a-8766-73fab304c246).

Official article on [recovering from a recovery drive](https://support.microsoft.com/en-us/windows/recovery-options-in-windows-31ce2444-7de3-818c-d626-e3b5a3024da5).

# Creating a "System Image"

A **system image** = Windows + your apps + settings + personal files
