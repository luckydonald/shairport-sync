bin_PROGRAMS = shairport
shairport_SOURCES = shairport.c daemon.c rtsp.c mdns.c mdns_external.c mdns_tinysvcmdns.c common.c rtp.c player.c alac.c audio.c audio_dummy.c audio_pipe.c tinysvcmdns.c mdns_avahi.c  getopt_long.c

if USE_ALSA
shairport_SOURCES += audio_alsa.c
endif

if USE_SNDIO
shairport_SOURCES += audio_sndio.c
endif

if USE_AO
shairport_SOURCES += audio_ao.c
endif

if USE_PULSE
shairport_SOURCES += audio_pulse.c
endif

if USE_DNS_SD
shairport_SOURCES += mdns_dns_sd.c
endif