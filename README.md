# twaidriver-thesis
NuttX RTOS CAN Bus Driver for Espressif ESP32C3

https://github.com/apache/incubator-nuttx/pull/6005

https://gitlab.fel.cvut.cz/otrees/risc-v-esp32/work-and-ideas/-/wikis/esp32c3-m1-nuttx

The main task of the work was to write
a CAN bus interface driver on ESP32C3
microcontrollers for the NuttX real-time
operating system. This thesis begins with
a theoretical part, which analyses CAN
bus technology, NuttX RTOS and one
of the newest RISC-V boards, ESP32C3-
devkit. The implementation part had a
long-term goal to contribute to NuttX
mainline by implementing a TWAI (CAN)
driver. This part illustrates how the
development operates under the NuttX RTOS
and provides a step-by-step explanation
of all the procedures that led to creating
a functional TWAI driver. The process of
contributing to a large project such as the
NuttX is demonstrated. The result of this
thesis is the driver source code, which was
accepted to the NuttX mainline. The last
section presents meticulous testing and
describes the techniques used.
Keywords: CAN bus, NuttX, driver,
Espressif, ESP32C3, SJA1000