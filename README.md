# FreeRtos-for-arm-cortex-M

SEGGER Sysview tool is integrated with freertos which allows snapshot or real-time based visualization of our RTOS.

Include exported path file (includepathSettings.XML)into your project.

Copy FreeRtosConfig.h to your inc folder.

Use timer other than systick for sysTick generation because systick will be used for rtos tick generation.
