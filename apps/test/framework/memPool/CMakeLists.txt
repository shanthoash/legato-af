#*******************************************************************************
# Copyright (C) Sierra Wireless Inc.
#
# Contributors:
#     Sierra Wireless - initial API and implementation
#*******************************************************************************

set(APP_TARGET testFwMemPool)

mkexe(  ${APP_TARGET}
            main.c
        )

add_test(${APP_TARGET} ${EXECUTABLE_OUTPUT_PATH}/${APP_TARGET})

