from building import *
import os

cwd = GetCurrentDir()
src = ['mipi_display.c','hagl_hal_single.c','hagl_hal_double.c','hagl_hal_triple.c','times.c']
CPPPATH = [cwd]
group = DefineGroup('FileSystem', src, depend = [''], CPPPATH = CPPPATH)

Return('group')

