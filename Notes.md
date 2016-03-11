# load module for camera
modprobe facetimehd

# Clear interrupt so that laptop does not spin kworker at 100%
echo disable > /sys/firmware/acpi/interrupts/gpe16

