+++
+++

<h1><img src="assets/icons/inventory.svg"><span>inventory at candar</span></h1>

<div class="inventory-container">
    {{ 
        inventory_item(
            image="pi5" 
            name="ARM (arm.local)"
            model="Raspberry Pi 5" 
            cpu="ARM Cortex-A76 (4)" 
            arch="ARM aarch64"
            ram="8 GB" 
            disk="SanDisk 128GB A2" 
            amount="1" 
        ) 
    }}
    {{ 
        inventory_item(
            image="mars" 
            name="MARS (mars.local)" 
            model="Milk-V Mars" 
            cpu="StarFive JH7110 (4)"
            arch="RISC-V rv64gc"
            ram="4 GB" 
            disk="SanDisk 64GB A2" 
            amount="1" 
        ) 
    }}
    {{ 
        inventory_item(
            image="zero" 
            name="ZERO (zero.local)" 
            model="Raspberry Pi Zero 2W" 
            cpu="ARM Cortex-A53 (4)" 
            arch="ARM aarch64"
            ram="512 MB" 
            disk="SanDisk 64GB A2" 
            amount="1" 
        ) 
    }}
    {{ 
        inventory_item(
            image="duo" 
            name="DUO" 
            model="Milk-V Duo 256M" 
            cpu="XuanTie C906 (2)" 
            arch="RISC-V rv64gc"
            ram="256 MB" 
            disk="SanDisk 128GB A1" 
            amount="1" 
        ) 
    }}
    {{ 
        inventory_item(
            image="esp32" 
            name="ESP" 
            model="ESP-WROOM-32" 
            cpu="Xtensa LX6 (2)"
            arch="Xtensa xtensa"
            ram="520 KB"
            disk="448 KB ROM" 
            amount="2" 
        ) 
    }}
    {{ 
        inventory_item(
            image="pico" 
            name="PICO" 
            model="Raspberry Pi Pico WH" 
            cpu="ARM Cortex-M0+ (2)"
            arch="ARM ARMv6-M"
            ram="520 KB"
            disk="448 KB ROM" 
            amount="1" 
        ) 
    }}
</div>