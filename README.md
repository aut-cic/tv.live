# AUT TV Live

[![Drone (cloud)](https://img.shields.io/drone/build/aut-cic/tv.live.svg?style=flat-square&logo=drone)](https://cloud.drone.io/aut-cic/tv.live)
![Docker Image Size (tag)](https://img.shields.io/docker/image-size/1995parham/aut-tv-live/latest?style=flat-square&logo=docker)
![Docker Pulls](https://img.shields.io/docker/pulls/1995parham/aut-tv-live?style=flat-square&logo=docker)

## Introduction

Live component for AUT TV, this component serves TV data from the [tvheadend](https://tvheadend.org/) to HLS into a ramdisk.
These information from ramdisk are served with Nginx.
One of the key issues here is the infomation about channel frequencies. These information is required for having a complete tv experience.
Other major issue here is that, only the main TV can have all channels without problem. The secondary TV has unknown issus with channels.

## Channels

Channels must be the same between tvheadend, tv.tive and tv.

|     Name      | Number |
| :-----------: | :----: |
|   IRIB TV1    |   1    |
|   IRIB TV2    |   2    |
|   IRIB TV3    |   3    |
|   IRIB TV4    |   4    |
|   IRIB TV5    |   5    |
|     IRNN      |   6    |
|   AMOOZESH    |   7    |
|  IRIB QURAN   |   8    |
|   MOSTANAD    |   9    |
|     OMID      |   10   |
|   IRIB KALA   |   11   |
|   NAMAYESH    |   12   |
|     OFOGH     |   13   |
|     iFILM     |   14   |
|    TAMASHA    |   15   |
|     SHOMA     |   16   |
|    VARZESH    |   17   |
| POOYA & NAHAL |   18   |
|    SALAMAT    |   19   |
|     NASIM     |   20   |
|    AL-ALAM    |   28   |
|   ALKAWTHAR   |   29   |
|   PRESS TV    |   30   |
|  IRIB TV3 HD  |   52   |
|  TAMASHA HD   |   53   |
|  MOSTANAD HD  |   54   |

## References

- https://www.teknotut.com/en/streaming-tv-online-with-tvheadend/
- https://fa.wikipedia.org/wiki/%D9%81%D8%B1%D8%B3%D8%AA%D9%86%D8%AF%D9%87%E2%80%8C%D9%87%D8%A7%DB%8C_%D8%AF%DB%8C%D8%AC%DB%8C%D8%AA%D8%A7%D9%84_%D8%B5%D8%AF%D8%A7_%D9%88_%D8%B3%DB%8C%D9%85%D8%A7
