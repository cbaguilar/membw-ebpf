# Chrome perf tool

This is a super basic "hello-world" attempt for us to document
how to interface the linux `perf` tool with `ebpf` by tracking
some perf information about the various chrome processes on
christian's laptop.

I am using the eunomia ebpf tutorial: https://eunomia.dev/en/tutorials/1-helloworld/


Laptop details:

```
                   -`                    cbaguilar@altima 
                  .o+`                   ---------------- 
                 `ooo/                   OS: Arch Linux x86_64 
                `+oooo:                  Host: XPS 13 9315 2-in-1 
               `+oooooo:                 Kernel: 6.12.24-1-lts 
               -+oooooo+:                Uptime: 23 hours, 32 mins 
             `/:-:++oooo+:               Packages: 1154 (pacman) 
            `/++++/+++++++:              Shell: bash 5.2.37 
           `/++++++++++++++:             Resolution: 2880x1920 
          `/+++ooooooooooooo/`           DE: GNOME 48.1 
         ./ooosssso++osssssso+`          WM: Mutter 
        .oossssso-````/ossssss+`         WM Theme: Adwaita 
       -osssssso.      :ssssssso.        Theme: Adwaita [GTK2/3] 
      :osssssss/        osssso+++.       Icons: Adwaita [GTK2/3] 
     /ossssssss/        +ssssooo/-       Terminal: kgx 
   `/ossssso+/:-        -:/+osssso+-     CPU: 12th Gen Intel i7-1250U (12) @ 4.700GHz 
  `+sso+:-`                 `.-/+oso:    GPU: Intel Alder Lake-UP4 GT2 [Iris Xe Graphics] 
 `++:.                           `-/+/   Memory: 3912MiB / 15680MiB 
 .`                                 `/
                                                                 
                                                                 
```

