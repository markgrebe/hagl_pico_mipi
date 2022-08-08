from building import *
import os

cwd = GetCurrentDir()
src = ['mipi_display.c','hagl_hal_single.c','hagl_hal_double.c','hagl_hal_triple.c','times.c']
CPPPATH = [cwd]

CPPDEFINES = ['MIPI_DISPLAY_WIDTH=240',
              'MIPI_DISPLAY_HEIGHT=240',
              'MIPI_DISPLAY_OFFSET_X=0',
              'MIPI_DISPLAY_OFFSET_Y=0', 
              'HAGL_HAL_USE_DOUBLE_BUFFER',
              'HAGL_HAL_USE_DMA']
  
group = DefineGroup('FileSystem', src, depend = [''], CPPPATH = CPPPATH, CPPDEFINES=CPPDEFINES)

Return('group')

