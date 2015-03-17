# AT-2 #
  * AT Command Test Suite
  * Date   : Sun Jan 10, 4.40PM, 2010
  * Auther : Atul Raut

# AT Command #

/local/mnt/workspace/donut/hardware/ril/reference-ril/atchannel.c
/local/mnt/workspace/donut/hardware/ril/reference-ril/atchannel.h

int at\_send\_command (const char **command, ATResponse****pp\_outResponse);**


# Function To Use #

  * Start Daemon
  * Open AT Handle
  * Do AT Command Testing [ACT Suite](Using.md)
  * e.g. at\_send\_command("AT+CNMI=1,2,2,1,1", NULL);

# Platform header file #
#include <telephony/ril.h>
#include "atchannel.h"
