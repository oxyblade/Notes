GRUB_CMDLINE_LINUX_DEFAULT - Options:

mitigations=off			- Control optional mitigations for CPU vulnerabilities.
verbose					- Debugging mode

libata.noacpi=1			- Disables use of ACPI in libata suspend/resume when set.
acpi=force				- force -- enable ACPI if default was off.
nosgx					- Disables Intel SGX kernel support.
acpi=off					- off -- disable ACPI if default was on.
apm=off (power_off)		- Advanced Power Management
mce=off					- Machine Check Exception
nomce					- Disable Machine Check Exception
loglevel=3
reboot=acpi
powersave=off			- This option disables power saving features.
ipv6.disable=1

nomodeset - Добавление параметра nomodeset инструктирует ядро, что не надо загружать драйверы видео до момента, пока не будет загружена графическая система X. В результате система загружается в текстовом виде, можно видеть сообщения процесса загрузки, проблема "черного экрана загрузки" устраняется.
