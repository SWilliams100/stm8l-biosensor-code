# stm8l-biosensor-code
Biosensor-code-STM8L

*

    THE PRESENT FIRMWARE WHICH IS FOR GUIDANCE ONLY AIMS AT PROVIDING CUSTOMERS
    WITH CODING INFORMATION REGARDING THEIR PRODUCTS IN ORDER FOR THEM TO SAVE
    TIME. AS A RESULT, STMICROELECTRONICS SHALL NOT BE HELD LIABLE FOR ANY
    DIRECT, INDIRECT OR CONSEQUENTIAL DAMAGES WITH RESPECT TO ANY CLAIMS ARISING
    FROM THE CONTENT OF SUCH FIRMWARE AND/OR THE USE MADE BY CUSTOMERS OF THE
    CODING INFORMATION CONTAINED HEREIN IN CONNECTION WITH THEIR PRODUCTS. * */

this firmware has been developped on M24LR04 discovery board by using STVD 4.2.1.

===versions===

1.0 : - first release (21-12-11)

1.1 : - clock management : switch to Low frequency clock during the LCD display

1.2 : - use the active halt mode for the display of the NDEF message - display the negative temperature

1.3 : - optimize the current consumption in the three modes - add the revision number of the firware (writen in the lost block of the M24LR04E-R) - save the current working mode

=== How to?===

===How program STM8Ldiscovery board with STVD? ===

    connect the Pin19 of the Jtag connector to the DC of the M24LR04 discovery board
    connect the Pin19 of the Jtag connector to the GND of the M24LR04 discovery board
    Plug the SWIM connector on the discovery board
    set the JP1 jumper on REG3.3 position
    upload the firmware

