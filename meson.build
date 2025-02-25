project(
  'allegro',
  'c',
  version: '4.2.2-xc',
  license: 'Giftware')

add_project_arguments(
  '-DALLEGRO_SRC',
  '-DALLEGRO_LIB_BUILD',
  '-DALLEGRO_VERSION=4',
  '-DALLEGRO_SUB_VERSION=2',
  '-fgnu89-inline',
  '-Wno-unused',
  '-mtune=i586',
  '-funroll-loops',
  '-ffast-math',
  '-fomit-frame-pointer',
  language : 'c')
incdir = include_directories('include')

sources = files(
  'src/allegro.c',
  'src/blit.c',
  'src/bmp.c',
  'src/clip3d.c',
  'src/clip3df.c',
  'src/colblend.c',
  'src/color.c',
  'src/config.c',
  'src/datafile.c',
  'src/dataregi.c',
  'src/digmid.c',
  'src/dither.c',
  'src/dispsw.c',
  'src/drvlist.c',
  'src/file.c',
  'src/fli.c',
  'src/flood.c',
  'src/font.c',
  'src/fontbios.c',
  'src/fontbmp.c',
  'src/fontdat.c',
  'src/fontgrx.c',
  'src/fonttxt.c',
  'src/fsel.c',
  'src/gfx.c',
  'src/glyph.c',
  'src/graphics.c',
  'src/gsprite.c',
  'src/gui.c',
  'src/guiproc.c',
  'src/inline.c',
  'src/joystick.c',
  'src/keyboard.c',
  'src/lbm.c',
  'src/libc.c',
  'src/lzss.c',
  'src/math.c',
  'src/math3d.c',
  'src/midi.c',
  'src/mixer.c',
  'src/modesel.c',
  'src/mouse.c',
  'src/pcx.c',
  'src/poly3d.c',
  'src/polygon.c',
  'src/quantize.c',
  'src/quat.c',
  'src/readbmp.c',
  'src/readfont.c',
  'src/readsmp.c',
  'src/rle.c',
  'src/rotate.c',
  'src/scene3d.c',
  'src/sound.c',
  'src/spline.c',
  'src/stream.c',
  'src/text.c',
  'src/tga.c',
  'src/timer.c',
  'src/unicode.c',
  'src/vtable.c',
  'src/vtable15.c',
  'src/vtable16.c',
  'src/vtable24.c',
  'src/vtable32.c',
  'src/vtable8.c',
  'src/i386/iblit16.S',
  'src/i386/iblit24.S',
  'src/i386/iblit32.S',
  'src/i386/iblit8.S',
  'src/i386/icpu.c',
  'src/i386/icpus.S',
  'src/i386/icsprite.c',
  'src/i386/igfx15.S',
  'src/i386/igfx16.S',
  'src/i386/igfx24.S',
  'src/i386/igfx32.S',
  'src/i386/igfx8.S',
  'src/i386/imisc.S',
  'src/i386/iscan.S',
  'src/i386/iscanmmx.S',
  'src/i386/ispr15.S',
  'src/i386/ispr16.S',
  'src/i386/ispr24.S',
  'src/i386/ispr32.S',
  'src/i386/ispr8.S',
  'src/i386/istretch.c',
  'src/i386/izbuf.S',
  'src/misc/icolconv.S',
  'src/dos/adlib.c',
  'src/dos/awedata.c',
  'src/dos/dfile.c',
  'src/dos/dgfxdrv.c',
  'src/dos/djoydrv.c',
  'src/dos/dkeybd.c',
  'src/dos/dma.c',
  'src/dos/dmouse.c',
  'src/dos/dpmi.c',
  'src/dos/dsnddrv.c',
  'src/dos/dsystem.c',
  'src/dos/dtimer.c',
  'src/dos/emu8k.c',
  'src/dos/emu8kmid.c',
  'src/dos/essaudio.c',
  'src/dos/gpro.c',
  'src/dos/grip.c',
  'src/dos/gripjoy.c',
  'src/dos/gripfnc.S',
  'src/dos/ifsega.c',
  'src/dos/ifsega2f.c',
  'src/dos/ifsega2p.c',
  'src/dos/joystd.c',
  'src/dos/mpu.c',
  'src/dos/multijoy.c',
  'src/dos/n64pad.c',
  'src/dos/pic.c',
  'src/dos/psxpad.c',
  'src/dos/sb.c',
  'src/dos/sndscape.c',
  'src/dos/snespad.c',
  'src/dos/sw.c',
  'src/dos/swpp.c',
  'src/dos/swpps.S',
  'src/dos/vesa.c',
  'src/dos/vesas.S',
  'src/dos/wss.c',
  'src/dos/ww.c',
  'src/misc/modex.c',
  'src/misc/modexgfx.S',
  'src/misc/modexsms.c',
  'src/misc/pckeys.c',
  'src/misc/vbeaf.c',
  'src/misc/vbeafs.S',
  'src/misc/vbeafex.c',
  'src/misc/vga.c',
  'src/misc/vgaregs.c',
  'src/dos/djirq.c',
  'src/dos/djirqs.S')

static_library(
  'alleg',
  sources,
  include_directories : incdir)
