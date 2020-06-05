# mutexis
A Low overhead Pin based lock-sensitive appication performance analysis tool

Usage:
LD_PRELOAD=$PWD/totallocks.so "Application to be analyzed"

pin -probe -t mutexis.so -- "Application to be analyzed"

