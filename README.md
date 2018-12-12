# miniprogram2
小程序崩溃日志

{"app_name":"WeChat","timestamp":"2018-12-11 20:20:06.99 +0800","app_version":"6.7.4","slice_uuid":"ff764416-8936-3a18-bc67-64ead6a25219","adam_id":414478124,"build_version":"6.7.4.44","bundleID":"com.tencent.xin","share_with_app_devs":false,"is_first_party":false,"bug_type":"109","os_version":"iPhone OS 11.3 (15E216)","incident_id":"843F00E8-AE6F-485E-BDA9-A2FE58E234B3","name":"WeChat"}
Incident Identifier: 843F00E8-AE6F-485E-BDA9-A2FE58E234B3
CrashReporter Key:   1e545c10747b7d80bae20975bc2509edbbc976d9
Hardware Model:      iPhone9,1
Process:             WeChat [458]
Path:                /private/var/containers/Bundle/Application/82C6B9C0-6902-45C6-BB98-629308C347E0/WeChat.app/WeChat
Identifier:          com.tencent.xin
Version:             6.7.4.44 (6.7.4)
Code Type:           ARM-64 (Native)
Role:                Foreground
Parent Process:      launchd [1]
Coalition:           com.tencent.xin [451]


Date/Time:           2018-12-11 20:20:06.8178 +0800
Launch Time:         2018-12-11 19:52:36.0855 +0800
OS Version:          iPhone OS 11.3 (15E216)
Baseband Version:    3.66.00
Report Version:      104

Exception Type:  EXC_CRASH (SIGKILL)
Exception Codes: 0x0000000000000000, 0x0000000000000000
Exception Note:  EXC_CORPSE_NOTIFY
Termination Reason: Namespace SPRINGBOARD, Code 0x8badf00d
Termination Description: SPRINGBOARD, scene-update watchdog transgression: com.tencent.xin exhausted real (wall clock) time allowance of 10.00 seconds |  | ProcessVisibility: Foreground | ProcessState: Running | WatchdogEvent: scene-update | WatchdogVisibility: Foreground | WatchdogCPUStatistics: ( | "Elapsed total CPU time (seconds): 5.650 (user 5.650, system 0.000), 95% CPU", | "Elapsed application CPU time (seconds): 1.541, 26% CPU" | )
Triggered by Thread:  0

Application Specific Information:
BUG IN CLIENT OF LIBPLATFORM: Trying to recursively lock an os_unfair_lock
Abort Cause 165939
abort() called

Filtered syslog:
None found

Thread 0 name:  Dispatch queue: com.apple.main-thread
Thread 0 Crashed:
0   libsystem_kernel.dylib        	0x0000000181771be4 0x18174f000 + 142308
1   libsystem_platform.dylib      	0x000000018190ab8c 0x181905000 + 23436
2   libsystem_malloc.dylib        	0x00000001817a7858 0x1817a6000 + 6232
3   libsystem_malloc.dylib        	0x00000001817aa02c 0x1817a6000 + 16428
4   libsystem_malloc.dylib        	0x00000001817a9f60 0x1817a6000 + 16224
5   libobjc.A.dylib               	0x0000000180eb07d0 0x180e9c000 + 83920
6   libobjc.A.dylib               	0x0000000180ec1bc4 0x180e9c000 + 154564
7   UIKit                         	0x000000018b89638c 0x18b874000 + 140172
8   UIKit                         	0x000000018b9dadf4 0x18b874000 + 1469940
9   UIKit                         	0x000000018b9dab3c 0x18b874000 + 1469244
10  UIKit                         	0x000000018bb7da84 0x18b874000 + 3185284
11  UIKit                         	0x000000018bb7d928 0x18b874000 + 3184936
12  AppSupport                    	0x0000000184375160 0x184371000 + 16736
13  CoreFoundation                	0x0000000181c93ae8 0x181ba5000 + 977640
14  CoreFoundation                	0x0000000181c93230 0x181ba5000 + 975408
15  CoreFoundation                	0x0000000181c90c80 0x181ba5000 + 965760
16  CoreFoundation                	0x0000000181bb0da8 0x181ba5000 + 48552
17  GraphicsServices              	0x0000000183b93020 0x183b88000 + 45088
18  UIKit                         	0x000000018bb9178c 0x18b874000 + 3266444
19  WeChat                        	0x0000000102600560 0x102494000 + 1492320
20  libdyld.dylib                 	0x0000000181641fc0 0x181641000 + 4032

Thread 1:
0   libsystem_kernel.dylib        	0x00000001817710f4 0x18174f000 + 139508
1   libsystem_pthread.dylib       	0x0000000181913c90 0x18190f000 + 19600
2   Matrix                        	0x0000000106f32320 0x106ecc000 + 418592
3   Matrix                        	0x0000000106f5dcd4 0x106ecc000 + 597204
4   Matrix                        	0x0000000106f34de4 0x106ecc000 + 429540
5   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
6   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
7   libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 2:
0   libsystem_kernel.dylib        	0x00000001817710f4 0x18174f000 + 139508
1   libsystem_pthread.dylib       	0x0000000181913c90 0x18190f000 + 19600
2   mars                          	0x0000000109ed1b3c 0x1099ac000 + 5397308
3   mars                          	0x0000000109b370fc 0x1099ac000 + 1618172
4   mars                          	0x0000000109ed2940 0x1099ac000 + 5400896
5   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
6   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
7   libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 3:
0   libsystem_kernel.dylib        	0x00000001817710f4 0x18174f000 + 139508
1   libsystem_pthread.dylib       	0x0000000181913c90 0x18190f000 + 19600
2   ConfSDK                       	0x0000000109630e24 0x1095b0000 + 527908
3   ConfSDK                       	0x000000010961d784 0x1095b0000 + 448388
4   ConfSDK                       	0x000000010964c1e0 0x1095b0000 + 639456
5   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
6   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
7   libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 4 name:  matrix::mrs
Thread 4:
0   libsystem_kernel.dylib        	0x00000001817710f4 0x18174f000 + 139508
1   libsystem_pthread.dylib       	0x0000000181913c90 0x18190f000 + 19600
2   Matrix                        	0x0000000106f33cbc 0x106ecc000 + 425148
3   Matrix                        	0x0000000106f690c0 0x106ecc000 + 643264
4   Matrix                        	0x0000000106f69eb4 0x106ecc000 + 646836
5   Matrix                        	0x0000000106f34de4 0x106ecc000 + 429540
6   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
7   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
8   libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 5 name:  KSCrash Exception Handler (Secondary)
Thread 5:
0   libsystem_kernel.dylib        	0x000000018174fe08 0x18174f000 + 3592
1   libsystem_kernel.dylib        	0x000000018174fc80 0x18174f000 + 3200
2   libsystem_kernel.dylib        	0x0000000181753fa0 0x18174f000 + 20384
3   Matrix                        	0x0000000106ef5ba0 0x106ecc000 + 170912
4   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
5   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
6   libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 6 name:  KSCrash Exception Handler (Primary)
Thread 6:
0   libsystem_kernel.dylib        	0x000000018174fe08 0x18174f000 + 3592
1   libsystem_kernel.dylib        	0x000000018174fcf8 0x18174f000 + 3320
2   Matrix                        	0x0000000106ef5bcc 0x106ecc000 + 170956
3   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
4   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
5   libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 7:
0   libsystem_kernel.dylib        	0x0000000181771610 0x18174f000 + 140816
1   libsystem_c.dylib             	0x000000018168a12c 0x18167d000 + 53548
2   libsystem_c.dylib             	0x000000018168a04c 0x18167d000 + 53324
3   Matrix                        	0x0000000106f0126c 0x106ecc000 + 217708
4   Foundation                    	0x0000000182735efc 0x18261d000 + 1150716
5   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
6   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
7   libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 8:
0   libsystem_kernel.dylib        	0x00000001817710f4 0x18174f000 + 139508
1   libsystem_pthread.dylib       	0x0000000181913c90 0x18190f000 + 19600
2   mars                          	0x0000000109ed1b3c 0x1099ac000 + 5397308
3   mars                          	0x0000000109ecd170 0x1099ac000 + 5378416
4   mars                          	0x0000000109ed2940 0x1099ac000 + 5400896
5   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
6   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
7   libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 9 name:  com.apple.uikit.eventfetch-thread
Thread 9:
0   libsystem_kernel.dylib        	0x000000018174fe08 0x18174f000 + 3592
1   libsystem_kernel.dylib        	0x000000018174fc80 0x18174f000 + 3200
2   CoreFoundation                	0x0000000181c92e40 0x181ba5000 + 974400
3   CoreFoundation                	0x0000000181c90908 0x181ba5000 + 964872
4   CoreFoundation                	0x0000000181bb0da8 0x181ba5000 + 48552
5   Foundation                    	0x0000000182625674 0x18261d000 + 34420
6   Foundation                    	0x000000018262551c 0x18261d000 + 34076
7   UIKit                         	0x000000018b8767e4 0x18b874000 + 10212
8   Foundation                    	0x0000000182735efc 0x18261d000 + 1150716
9   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
10  libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
11  libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 10 name:  com.Tencent.WCDB.Queue.Corruption
Thread 10:
0   libsystem_kernel.dylib        	0x00000001817710f4 0x18174f000 + 139508
1   libsystem_pthread.dylib       	0x0000000181913c90 0x18190f000 + 19600
2   libc++.1.dylib                	0x0000000180e2825c 0x180e21000 + 29276
3   WCDB                          	0x00000001081adf04 0x108198000 + 89860
4   WCDB                          	0x000000010825fd3c 0x108198000 + 818492
5   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
6   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
7   libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 11 name:  com.Tencent.WCDB.Queue.Checkpoint
Thread 11:
0   libsystem_kernel.dylib        	0x00000001817710f4 0x18174f000 + 139508
1   libsystem_pthread.dylib       	0x0000000181913c90 0x18190f000 + 19600
2   libc++.1.dylib                	0x0000000180e2825c 0x180e21000 + 29276
3   WCDB                          	0x00000001081a5de8 0x108198000 + 56808
4   WCDB                          	0x0000000108236a44 0x108198000 + 649796
5   WCDB                          	0x000000010825fd3c 0x108198000 + 818492
6   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
7   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
8   libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 12 name:  com.Tencent.WCDB.Queue.Backup
Thread 12:
0   libsystem_kernel.dylib        	0x00000001817710f4 0x18174f000 + 139508
1   libsystem_pthread.dylib       	0x0000000181913c90 0x18190f000 + 19600
2   libc++.1.dylib                	0x0000000180e2825c 0x180e21000 + 29276
3   WCDB                          	0x00000001081a5de8 0x108198000 + 56808
4   WCDB                          	0x00000001081a5d00 0x108198000 + 56576
5   WCDB                          	0x000000010825fd3c 0x108198000 + 818492
6   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
7   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
8   libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 13 name:  mars::cdn
Thread 13:
0   libsystem_kernel.dylib        	0x00000001817710f4 0x18174f000 + 139508
1   libsystem_pthread.dylib       	0x0000000181913c90 0x18190f000 + 19600
2   mars                          	0x0000000109ed1b3c 0x1099ac000 + 5397308
3   mars                          	0x0000000109b77540 0x1099ac000 + 1881408
4   mars                          	0x0000000109b7975c 0x1099ac000 + 1890140
5   mars                          	0x0000000109ed2940 0x1099ac000 + 5400896
6   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
7   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
8   libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 14:
0   libsystem_kernel.dylib        	0x00000001817710f4 0x18174f000 + 139508
1   libsystem_pthread.dylib       	0x0000000181913c90 0x18190f000 + 19600
2   mars                          	0x0000000109ed1b3c 0x1099ac000 + 5397308
3   mars                          	0x0000000109b77540 0x1099ac000 + 1881408
4   mars                          	0x0000000109b78d98 0x1099ac000 + 1887640
5   mars                          	0x0000000109ed2940 0x1099ac000 + 5400896
6   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
7   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
8   libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 15 name:  mars::smc
Thread 15:
0   libsystem_kernel.dylib        	0x0000000181771be4 0x18174f000 + 142308
1   libsystem_platform.dylib      	0x000000018190ab8c 0x181905000 + 23436
2   libsystem_malloc.dylib        	0x00000001817a7858 0x1817a6000 + 6232
3   libsystem_malloc.dylib        	0x00000001817a75dc 0x1817a6000 + 5596
4   libsystem_malloc.dylib        	0x00000001817aa0b0 0x1817a6000 + 16560
5   libsystem_c.dylib             	0x00000001816cb3c4 0x18167d000 + 320452
6   libsystem_c.dylib             	0x00000001816d9730 0x18167d000 + 378672
7   libsystem_c.dylib             	0x00000001816ca8f8 0x18167d000 + 317688
8   libsystem_c.dylib             	0x000000018168a304 0x18167d000 + 54020
9   mars                          	0x0000000109b426a0 0x1099ac000 + 1664672
10  mars                          	0x0000000109d5d564 0x1099ac000 + 3872100
11  mars                          	0x0000000109d5d02c 0x1099ac000 + 3870764
12  mars                          	0x0000000109d60bac 0x1099ac000 + 3885996
13  mars                          	0x0000000109d6160c 0x1099ac000 + 3888652
14  mars                          	0x0000000109d55f28 0x1099ac000 + 3841832
15  mars                          	0x0000000109d54d98 0x1099ac000 + 3837336
16  mars                          	0x0000000109d48bdc 0x1099ac000 + 3787740
17  mars                          	0x0000000109d4cc84 0x1099ac000 + 3804292
18  mars                          	0x0000000109b788d4 0x1099ac000 + 1886420
19  mars                          	0x0000000109b7736c 0x1099ac000 + 1880940
20  mars                          	0x0000000109b7975c 0x1099ac000 + 1890140
21  mars                          	0x0000000109ed2940 0x1099ac000 + 5400896
22  libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
23  libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
24  libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 16 name:  mars::stn
Thread 16:
0   libsystem_kernel.dylib        	0x00000001817710f4 0x18174f000 + 139508
1   libsystem_pthread.dylib       	0x0000000181913c90 0x18190f000 + 19600
2   mars                          	0x0000000109ed1b3c 0x1099ac000 + 5397308
3   mars                          	0x0000000109b77540 0x1099ac000 + 1881408
4   mars                          	0x0000000109b78d98 0x1099ac000 + 1887640
5   mars                          	0x0000000109ed2940 0x1099ac000 + 5400896
6   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
7   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
8   libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 17 name:  mars::webnet
Thread 17:
0   libsystem_kernel.dylib        	0x00000001817710f4 0x18174f000 + 139508
1   libsystem_pthread.dylib       	0x0000000181913c90 0x18190f000 + 19600
2   mars                          	0x0000000109ed1b3c 0x1099ac000 + 5397308
3   mars                          	0x0000000109b77540 0x1099ac000 + 1881408
4   mars                          	0x0000000109b78d98 0x1099ac000 + 1887640
5   mars                          	0x0000000109ed2940 0x1099ac000 + 5400896
6   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
7   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
8   libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 18 name:  AVAudioSession Notify Thread
Thread 18:
0   libsystem_kernel.dylib        	0x0000000181771be4 0x18174f000 + 142308
1   libsystem_platform.dylib      	0x000000018190ab8c 0x181905000 + 23436
2   libsystem_malloc.dylib        	0x00000001817a7858 0x1817a6000 + 6232
3   libsystem_malloc.dylib        	0x00000001817aa02c 0x1817a6000 + 16428
4   libsystem_malloc.dylib        	0x00000001817a9f60 0x1817a6000 + 16224
5   CoreFoundation                	0x0000000181bef3c8 0x181ba5000 + 304072
6   CoreFoundation                	0x0000000181bee6bc 0x181ba5000 + 300732
7   CoreFoundation                	0x0000000181bab9ec 0x181ba5000 + 27116
8   CoreFoundation                	0x0000000181bd67d8 0x181ba5000 + 202712
9   AudioToolbox                  	0x0000000185c34508 0x185805000 + 4388104
10  AudioToolbox                  	0x0000000185836d2c 0x185805000 + 204076
11  AudioToolbox                  	0x0000000185836c78 0x185805000 + 203896
12  AudioToolbox                  	0x0000000185c2d358 0x185805000 + 4359000
13  AudioToolbox                  	0x0000000185a907e4 0x185805000 + 2668516
14  AudioToolbox                  	0x000000018594c2a8 0x185805000 + 1340072
15  AudioToolbox                  	0x0000000185c33210 0x185805000 + 4383248
16  CoreFoundation                	0x0000000181c93ae8 0x181ba5000 + 977640
17  CoreFoundation                	0x0000000181c93230 0x181ba5000 + 975408
18  CoreFoundation                	0x0000000181c90c80 0x181ba5000 + 965760
19  CoreFoundation                	0x0000000181bb0da8 0x181ba5000 + 48552
20  AVFAudio                      	0x0000000187696424 0x187610000 + 549924
21  AVFAudio                      	0x00000001876c0834 0x187610000 + 722996
22  libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
23  libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
24  libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 19:
0   libsystem_kernel.dylib        	0x00000001817710f4 0x18174f000 + 139508
1   libsystem_pthread.dylib       	0x0000000181913c90 0x18190f000 + 19600
2   mars                          	0x0000000109ed1b3c 0x1099ac000 + 5397308
3   mars                          	0x0000000109b77540 0x1099ac000 + 1881408
4   mars                          	0x0000000109b78d98 0x1099ac000 + 1887640
5   mars                          	0x0000000109ed2940 0x1099ac000 + 5400896
6   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
7   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
8   libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 20:
0   libsystem_kernel.dylib        	0x00000001817710f4 0x18174f000 + 139508
1   libsystem_pthread.dylib       	0x0000000181913c90 0x18190f000 + 19600
2   libc++.1.dylib                	0x0000000180e2825c 0x180e21000 + 29276
3   JavaScriptCore                	0x00000001893071a4 0x18884c000 + 11252132
4   JavaScriptCore                	0x0000000189306db8 0x18884c000 + 11251128
5   JavaScriptCore                	0x0000000189306b60 0x18884c000 + 11250528
6   JavaScriptCore                	0x0000000189306f7c 0x18884c000 + 11251580
7   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
8   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
9   libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 21 name:  com.apple.NSURLConnectionLoader
Thread 21:
0   libsystem_kernel.dylib        	0x000000018174fe08 0x18174f000 + 3592
1   libsystem_kernel.dylib        	0x000000018174fc80 0x18174f000 + 3200
2   CoreFoundation                	0x0000000181c92e40 0x181ba5000 + 974400
3   CoreFoundation                	0x0000000181c90908 0x181ba5000 + 964872
4   CoreFoundation                	0x0000000181bb0da8 0x181ba5000 + 48552
5   CFNetwork                     	0x00000001824be4b0 0x18226e000 + 2426032
6   Foundation                    	0x0000000182735efc 0x18261d000 + 1150716
7   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
8   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
9   libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 22 name:  mars::stn::lonklink
Thread 22:
0   libsystem_kernel.dylib        	0x00000001817543e4 0x18174f000 + 21476
1   mars                          	0x0000000109b7fb04 0x1099ac000 + 1915652
2   mars                          	0x0000000109c6beb4 0x1099ac000 + 2883252
3   mars                          	0x0000000109c68fac 0x1099ac000 + 2871212
4   mars                          	0x0000000109ed2940 0x1099ac000 + 5400896
5   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
6   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
7   libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 23:
0   libsystem_kernel.dylib        	0x00000001817710f4 0x18174f000 + 139508
1   libsystem_pthread.dylib       	0x0000000181913c90 0x18190f000 + 19600
2   WeChat                        	0x0000000103fe5fc8 0x102494000 + 28647368
3   Foundation                    	0x0000000182735efc 0x18261d000 + 1150716
4   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
5   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
6   libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 24 name:  com.apple.CoreMotion.MotionThread
Thread 24:
0   libsystem_kernel.dylib        	0x000000018174fe08 0x18174f000 + 3592
1   libsystem_kernel.dylib        	0x000000018174fc80 0x18174f000 + 3200
2   CoreFoundation                	0x0000000181c92e40 0x181ba5000 + 974400
3   CoreFoundation                	0x0000000181c90908 0x181ba5000 + 964872
4   CoreFoundation                	0x0000000181bb0da8 0x181ba5000 + 48552
5   CoreFoundation                	0x0000000181c00b28 0x181ba5000 + 375592
6   CoreMotion                    	0x00000001871919dc 0x187110000 + 530908
7   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
8   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
9   libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 25:
0   libsystem_kernel.dylib        	0x00000001817710f4 0x18174f000 + 139508
1   libsystem_pthread.dylib       	0x0000000181913c90 0x18190f000 + 19600
2   mars                          	0x0000000109ed1b3c 0x1099ac000 + 5397308
3   mars                          	0x0000000109e914d4 0x1099ac000 + 5133524
4   mars                          	0x0000000109ed2940 0x1099ac000 + 5400896
5   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
6   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
7   libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 26:
0   libsystem_kernel.dylib        	0x00000001817710f4 0x18174f000 + 139508
1   libsystem_pthread.dylib       	0x0000000181913c90 0x18190f000 + 19600
2   mars                          	0x0000000109ed1b3c 0x1099ac000 + 5397308
3   mars                          	0x0000000109e9af54 0x1099ac000 + 5173076
4   mars                          	0x0000000109ed2940 0x1099ac000 + 5400896
5   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
6   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
7   libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 27:
0   libsystem_kernel.dylib        	0x00000001817710f4 0x18174f000 + 139508
1   libsystem_pthread.dylib       	0x0000000181913c90 0x18190f000 + 19600
2   QBar                          	0x00000001091219cc 0x108fd4000 + 1366476
3   QBar                          	0x00000001091123b8 0x108fd4000 + 1303480
4   QBar                          	0x0000000109111ba8 0x108fd4000 + 1301416
5   QBar                          	0x000000010911218c 0x108fd4000 + 1302924
6   QBar                          	0x0000000109101304 0x108fd4000 + 1233668
7   QBar                          	0x0000000109120ac4 0x108fd4000 + 1362628
8   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
9   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
10  libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 28:
0   libsystem_platform.dylib      	0x0000000181909e38 0x181905000 + 20024
1   libsystem_platform.dylib      	0x000000018190abb8 0x181905000 + 23480
2   libsystem_malloc.dylib        	0x00000001817a7858 0x1817a6000 + 6232
3   libsystem_malloc.dylib        	0x00000001817a75dc 0x1817a6000 + 5596
4   libsystem_malloc.dylib        	0x00000001817aa0b0 0x1817a6000 + 16560
5   Foundation                    	0x000000018264bf8c 0x18261d000 + 192396
6   Foundation                    	0x000000018267d288 0x18261d000 + 393864
7   Foundation                    	0x000000018267cde8 0x18261d000 + 392680
8   Foundation                    	0x0000000182717610 0x18261d000 + 1025552
9   Foundation                    	0x000000018267c300 0x18261d000 + 389888
10  WeChat                        	0x00000001053efb8c 0x102494000 + 49658764
11  WeChat                        	0x00000001054b5534 0x102494000 + 50468148
12  WeChat                        	0x0000000105490ac0 0x102494000 + 50318016
13  WeChat                        	0x00000001054f85ac 0x102494000 + 50742700
14  Matrix                        	0x0000000106efcfd4 0x106ecc000 + 200660
15  libsystem_platform.dylib      	0x000000018190cb58 0x181905000 + 31576
16  libsystem_pthread.dylib       	0x0000000181912288 0x18190f000 + 12936
17  libsystem_c.dylib             	0x00000001816dfd0c 0x18167d000 + 404748
18  libsystem_malloc.dylib        	0x00000001817b2df4 0x1817a6000 + 52724
19  libsystem_malloc.dylib        	0x00000001817b37d8 0x1817a6000 + 55256
20  libsystem_malloc.dylib        	0x00000001817b37a0 0x1817a6000 + 55200
21  libsystem_malloc.dylib        	0x00000001817b39dc 0x1817a6000 + 55772
22  libicucore.A.dylib            	0x0000000181adabdc 0x181971000 + 1481692
23  libicucore.A.dylib            	0x0000000181adac94 0x181971000 + 1481876
24  libicucore.A.dylib            	0x0000000181a528cc 0x181971000 + 923852
25  libicucore.A.dylib            	0x0000000181b09d0c 0x181971000 + 1674508
26  CoreFoundation                	0x0000000181ce0cbc 0x181ba5000 + 1293500
27  CoreFoundation                	0x0000000181c688cc 0x181ba5000 + 800972
28  CoreFoundation                	0x0000000181c684ec 0x181ba5000 + 799980
29  Foundation                    	0x00000001826615b0 0x18261d000 + 279984
30  Foundation                    	0x0000000182661314 0x18261d000 + 279316
31  WeChat                        	0x0000000102b4ad68 0x102494000 + 7040360
32  WeChat                        	0x000000010274b188 0x102494000 + 2847112
33  WeChat                        	0x0000000102b48a78 0x102494000 + 7031416
34  WeChat                        	0x0000000102b48580 0x102494000 + 7030144
35  WeChat                        	0x0000000102b49050 0x102494000 + 7032912
36  CoreFoundation                	0x0000000181cf2580 0x181ba5000 + 1365376
37  CoreFoundation                	0x0000000181bd1748 0x181ba5000 + 182088
38  JavaScriptCore                	0x000000018899ce54 0x18884c000 + 1379924
39  JavaScriptCore                	0x000000018899c960 0x18884c000 + 1378656
40  JavaScriptCore                	0x000000018899c398 0x18884c000 + 1377176
41  JavaScriptCore                	0x000000018898f408 0x18884c000 + 1324040
42  JavaScriptCore                	0x000000018898e758 0x18884c000 + 1320792
43  JavaScriptCore                	0x000000018898e7cc 0x18884c000 + 1320908
44  JavaScriptCore                	0x000000018898e758 0x18884c000 + 1320792
45  JavaScriptCore                	0x000000018898e758 0x18884c000 + 1320792
46  JavaScriptCore                	0x000000018898e758 0x18884c000 + 1320792
47  JavaScriptCore                	0x000000018898e758 0x18884c000 + 1320792
48  JavaScriptCore                	0x000000018898e7cc 0x18884c000 + 1320908
49  JavaScriptCore                	0x000000018898e758 0x18884c000 + 1320792
50  JavaScriptCore                	0x000000018898e758 0x18884c000 + 1320792
51  JavaScriptCore                	0x000000018898eb54 0x18884c000 + 1321812
52  JavaScriptCore                	0x000000018898ec88 0x18884c000 + 1322120
53  JavaScriptCore                	0x000000018898ec88 0x18884c000 + 1322120
54  JavaScriptCore                	0x000000018898ec88 0x18884c000 + 1322120
55  JavaScriptCore                	0x000000018898ec88 0x18884c000 + 1322120
56  JavaScriptCore                	0x000000018898e7cc 0x18884c000 + 1320908
57  JavaScriptCore                	0x000000018898e7cc 0x18884c000 + 1320908
58  JavaScriptCore                	0x000000018898e758 0x18884c000 + 1320792
59  JavaScriptCore                	0x000000018898eb54 0x18884c000 + 1321812
60  JavaScriptCore                	0x000000018898e7cc 0x18884c000 + 1320908
61  JavaScriptCore                	0x000000018898e758 0x18884c000 + 1320792
62  JavaScriptCore                	0x000000018898e758 0x18884c000 + 1320792
63  JavaScriptCore                	0x000000018898e7cc 0x18884c000 + 1320908
64  JavaScriptCore                	0x000000018898e758 0x18884c000 + 1320792
65  JavaScriptCore                	0x000000018898eb54 0x18884c000 + 1321812
66  JavaScriptCore                	0x000000018898e7cc 0x18884c000 + 1320908
67  JavaScriptCore                	0x000000018898e758 0x18884c000 + 1320792
68  JavaScriptCore                	0x000000018898e758 0x18884c000 + 1320792
69  JavaScriptCore                	0x000000018898e7cc 0x18884c000 + 1320908
70  JavaScriptCore                	0x000000018898e758 0x18884c000 + 1320792
71  JavaScriptCore                	0x000000018898eb54 0x18884c000 + 1321812
72  JavaScriptCore                	0x000000018898e758 0x18884c000 + 1320792
73  JavaScriptCore                	0x000000018898ec88 0x18884c000 + 1322120
74  JavaScriptCore                	0x000000018898ec88 0x18884c000 + 1322120
75  JavaScriptCore                	0x00000001889874a0 0x18884c000 + 1291424
76  JavaScriptCore                	0x0000000188f38aa4 0x18884c000 + 7260836
77  JavaScriptCore                	0x000000018889045c 0x18884c000 + 279644
78  JavaScriptCore                	0x00000001890e4018 0x18884c000 + 9011224
79  JavaScriptCore                	0x000000018898f2e4 0x18884c000 + 1323748
80  JavaScriptCore                	0x000000018898ec88 0x18884c000 + 1322120
81  JavaScriptCore                	0x000000018898e758 0x18884c000 + 1320792
82  JavaScriptCore                	0x000000018898ec88 0x18884c000 + 1322120
83  JavaScriptCore                	0x000000018898e758 0x18884c000 + 1320792
84  JavaScriptCore                	0x000000018898e758 0x18884c000 + 1320792
85  JavaScriptCore                	0x000000018898ec88 0x18884c000 + 1322120
86  JavaScriptCore                	0x000000018898e7cc 0x18884c000 + 1320908
87  JavaScriptCore                	0x000000018898e7cc 0x18884c000 + 1320908
88  JavaScriptCore                	0x00000001889874a0 0x18884c000 + 1291424
89  JavaScriptCore                	0x0000000188f38aa4 0x18884c000 + 7260836
90  JavaScriptCore                	0x0000000188f11378 0x18884c000 + 7099256
91  JavaScriptCore                	0x000000018909a92c 0x18884c000 + 8710444
92  JavaScriptCore                	0x00000001889b1bb0 0x18884c000 + 1465264
93  JavaScriptCore                	0x00000001889924ec 0x18884c000 + 1336556
94  WeChat                        	0x0000000102b4da10 0x102494000 + 7051792
95  WeChat                        	0x0000000102b41a8c 0x102494000 + 7002764
96  WeChat                        	0x0000000102b413c0 0x102494000 + 7001024
97  Foundation                    	0x00000001827360ec 0x18261d000 + 1151212
98  CoreFoundation                	0x0000000181c93404 0x181ba5000 + 975876
99  CoreFoundation                	0x0000000181c92c2c 0x181ba5000 + 973868
100 CoreFoundation                	0x0000000181c9079c 0x181ba5000 + 964508
101 CoreFoundation                	0x0000000181bb0da8 0x181ba5000 + 48552
102 CoreFoundation                	0x0000000181c00b28 0x181ba5000 + 375592
103 WeChat                        	0x0000000102b3c40c 0x102494000 + 6980620
104 Foundation                    	0x0000000182735efc 0x18261d000 + 1150716
105 libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
106 libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
107 libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 29:
0   libsystem_kernel.dylib        	0x00000001817710f4 0x18174f000 + 139508
1   libsystem_pthread.dylib       	0x0000000181913c90 0x18190f000 + 19600
2   libc++.1.dylib                	0x0000000180e282ec 0x180e21000 + 29420
3   TXLiteAVSDK_Smart_No_VOD      	0x000000010720c558 0x107148000 + 804184
4   TXLiteAVSDK_Smart_No_VOD      	0x000000010720c4b0 0x107148000 + 804016
5   TXLiteAVSDK_Smart_No_VOD      	0x000000010720c424 0x107148000 + 803876
6   TXLiteAVSDK_Smart_No_VOD      	0x000000010720c108 0x107148000 + 803080
7   TXLiteAVSDK_Smart_No_VOD      	0x000000010720c1d0 0x107148000 + 803280
8   TXLiteAVSDK_Smart_No_VOD      	0x00000001071fead4 0x107148000 + 748244
9   TXLiteAVSDK_Smart_No_VOD      	0x000000010720d5b0 0x107148000 + 808368
10  TXLiteAVSDK_Smart_No_VOD      	0x000000010720d674 0x107148000 + 808564
11  libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
12  libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
13  libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 30:
0   libsystem_kernel.dylib        	0x000000018174fe08 0x18174f000 + 3592
1   libsystem_kernel.dylib        	0x000000018174fc80 0x18174f000 + 3200
2   CoreFoundation                	0x0000000181c92e40 0x181ba5000 + 974400
3   CoreFoundation                	0x0000000181c90908 0x181ba5000 + 964872
4   CoreFoundation                	0x0000000181bb0da8 0x181ba5000 + 48552
5   CoreFoundation                	0x0000000181c00b28 0x181ba5000 + 375592
6   WeChat                        	0x0000000102b3c40c 0x102494000 + 6980620
7   Foundation                    	0x0000000182735efc 0x18261d000 + 1150716
8   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
9   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
10  libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 31 name:  quic_network
Thread 31:
0   libsystem_kernel.dylib        	0x000000018174fe08 0x18174f000 + 3592
1   libsystem_kernel.dylib        	0x000000018174fc80 0x18174f000 + 3200
2   CoreFoundation                	0x0000000181c92e40 0x181ba5000 + 974400
3   CoreFoundation                	0x0000000181c90908 0x181ba5000 + 964872
4   CoreFoundation                	0x0000000181bb0da8 0x181ba5000 + 48552
5   Foundation                    	0x0000000182625674 0x18261d000 + 34420
6   TXLiteAVSDK_Smart_No_VOD      	0x000000010725c85c 0x107148000 + 1132636
7   TXLiteAVSDK_Smart_No_VOD      	0x000000010725b890 0x107148000 + 1128592
8   TXLiteAVSDK_Smart_No_VOD      	0x000000010728b21c 0x107148000 + 1323548
9   TXLiteAVSDK_Smart_No_VOD      	0x0000000107261444 0x107148000 + 1152068
10  TXLiteAVSDK_Smart_No_VOD      	0x0000000107229ed0 0x107148000 + 925392
11  TXLiteAVSDK_Smart_No_VOD      	0x000000010722a38c 0x107148000 + 926604
12  TXLiteAVSDK_Smart_No_VOD      	0x000000010724cc44 0x107148000 + 1068100
13  libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
14  libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
15  libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 32:
0   libsystem_kernel.dylib        	0x0000000181771610 0x18174f000 + 140816
1   libsystem_c.dylib             	0x000000018168a12c 0x18167d000 + 53548
2   TXLiteAVSDK_Smart_No_VOD      	0x00000001072043a4 0x107148000 + 770980
3   TXLiteAVSDK_Smart_No_VOD      	0x000000010720a5d4 0x107148000 + 796116
4   TXLiteAVSDK_Smart_No_VOD      	0x00000001071f11e0 0x107148000 + 692704
5   TXLiteAVSDK_Smart_No_VOD      	0x000000010720d5b0 0x107148000 + 808368
6   TXLiteAVSDK_Smart_No_VOD      	0x000000010720d674 0x107148000 + 808564
7   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
8   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
9   libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 33:
0   libsystem_kernel.dylib        	0x0000000181771be4 0x18174f000 + 142308
1   libsystem_platform.dylib      	0x000000018190ab8c 0x181905000 + 23436
2   libsystem_malloc.dylib        	0x00000001817b3864 0x1817a6000 + 55396
3   CoreFoundation                	0x0000000181c83850 0x181ba5000 + 911440
4   libsystem_pthread.dylib       	0x000000018191057c 0x18190f000 + 5500
5   libsystem_pthread.dylib       	0x00000001819102cc 0x18190f000 + 4812
6   libsystem_pthread.dylib       	0x00000001819100d4 0x18190f000 + 4308
7   libsystem_pthread.dylib       	0x000000018190fb08 0x18190f000 + 2824

Thread 34 name:  Dispatch queue: VideoDecoderQueue
Thread 34:
0   libsystem_kernel.dylib        	0x000000018174fe44 0x18174f000 + 3652
1   libdispatch.dylib             	0x00000001815defcc 0x1815db000 + 16332
2   libdispatch.dylib             	0x00000001815dff04 0x1815db000 + 20228
3   VideoToolbox                  	0x00000001854b7ff8 0x185458000 + 393208
4   VideoToolbox                  	0x00000001854b894c 0x185458000 + 395596
5   TXLiteAVSDK_Smart_No_VOD      	0x000000010736ebc0 0x107148000 + 2255808
6   libdispatch.dylib             	0x00000001815dcb24 0x1815db000 + 6948
7   libdispatch.dylib             	0x00000001815dcae4 0x1815db000 + 6884
8   libdispatch.dylib             	0x00000001815e6a38 0x1815db000 + 47672
9   libdispatch.dylib             	0x00000001815e7380 0x1815db000 + 50048
10  libdispatch.dylib             	0x00000001815e7d4c 0x1815db000 + 52556
11  libdispatch.dylib             	0x00000001815f011c 0x1815db000 + 86300
12  libsystem_pthread.dylib       	0x000000018190fe70 0x18190f000 + 3696
13  libsystem_pthread.dylib       	0x000000018190fb08 0x18190f000 + 2824

Thread 35 name:  Dispatch queue: com.apple.CoreLocation.ConnectionClient.0x11d4d2170.events
Thread 35:
0   libsystem_kernel.dylib        	0x000000018174fe5c 0x18174f000 + 3676
1   libdispatch.dylib             	0x00000001815df0b0 0x1815db000 + 16560
2   libdispatch.dylib             	0x00000001815df924 0x1815db000 + 18724
3   CoreLocation                  	0x000000018845c888 0x188459000 + 14472
4   CoreLocation                  	0x000000018846243c 0x188459000 + 37948
5   CoreLocation                  	0x000000018846211c 0x188459000 + 37148
6   CoreLocation                  	0x00000001884b8928 0x188459000 + 391464
7   CoreLocation                  	0x00000001884b4988 0x188459000 + 375176
8   CoreLocation                  	0x00000001884b4850 0x188459000 + 374864
9   CoreLocation                  	0x00000001884b62ac 0x188459000 + 381612
10  libxpc.dylib                  	0x000000018194b220 0x181946000 + 21024
11  libxpc.dylib                  	0x0000000181948bb4 0x181946000 + 11188
12  libdispatch.dylib             	0x00000001815dcbb4 0x1815db000 + 7092
13  libdispatch.dylib             	0x00000001815f34c4 0x1815db000 + 99524
14  libdispatch.dylib             	0x00000001815e68f0 0x1815db000 + 47344
15  libdispatch.dylib             	0x00000001815f3f70 0x1815db000 + 102256
16  libdispatch.dylib             	0x00000001815e68f0 0x1815db000 + 47344
17  libdispatch.dylib             	0x00000001815e7380 0x1815db000 + 50048
18  libdispatch.dylib             	0x00000001815e68f0 0x1815db000 + 47344
19  libdispatch.dylib             	0x00000001815e7380 0x1815db000 + 50048
20  libdispatch.dylib             	0x00000001815e7d4c 0x1815db000 + 52556
21  libdispatch.dylib             	0x00000001815f011c 0x1815db000 + 86300
22  libsystem_pthread.dylib       	0x000000018190fe70 0x18190f000 + 3696
23  libsystem_pthread.dylib       	0x000000018190fb08 0x18190f000 + 2824

Thread 36 name:  Dispatch queue: com.apple.root.default-qos
Thread 36:
0   libsystem_kernel.dylib        	0x0000000181771be4 0x18174f000 + 142308
1   libsystem_platform.dylib      	0x000000018190ab8c 0x181905000 + 23436
2   libsystem_malloc.dylib        	0x00000001817a7858 0x1817a6000 + 6232
3   libsystem_malloc.dylib        	0x00000001817abb30 0x1817a6000 + 23344
4   libsystem_malloc.dylib        	0x00000001817ab0ac 0x1817a6000 + 20652
5   libsystem_malloc.dylib        	0x00000001817aaee0 0x1817a6000 + 20192
6   CoreFoundation                	0x0000000181c49f70 0x181ba5000 + 675696
7   Foundation                    	0x000000018267db18 0x18261d000 + 396056
8   Foundation                    	0x000000018264174c 0x18261d000 + 149324
9   TXLiteAVSDK_Smart_No_VOD      	0x00000001071ec154 0x107148000 + 672084
10  TXLiteAVSDK_Smart_No_VOD      	0x00000001071ec47c 0x107148000 + 672892
11  TXLiteAVSDK_Smart_No_VOD      	0x00000001071ecd34 0x107148000 + 675124
12  TXLiteAVSDK_Smart_No_VOD      	0x00000001071d68d4 0x107148000 + 583892
13  TXLiteAVSDK_Smart_No_VOD      	0x00000001071e43d8 0x107148000 + 639960
14  TXLiteAVSDK_Smart_No_VOD      	0x000000010716fa28 0x107148000 + 162344
15  TXLiteAVSDK_Smart_No_VOD      	0x000000010716e274 0x107148000 + 156276
16  TXLiteAVSDK_Smart_No_VOD      	0x0000000107188f58 0x107148000 + 266072
17  TXLiteAVSDK_Smart_No_VOD      	0x0000000107185cf8 0x107148000 + 253176
18  TXLiteAVSDK_Smart_No_VOD      	0x00000001071857fc 0x107148000 + 251900
19  TXLiteAVSDK_Smart_No_VOD      	0x0000000107190b7c 0x107148000 + 297852
20  TXLiteAVSDK_Smart_No_VOD      	0x0000000107190828 0x107148000 + 297000
21  TXLiteAVSDK_Smart_No_VOD      	0x0000000107190644 0x107148000 + 296516
22  TXLiteAVSDK_Smart_No_VOD      	0x000000010718a9e0 0x107148000 + 272864
23  TXLiteAVSDK_Smart_No_VOD      	0x000000010718b240 0x107148000 + 275008
24  libdispatch.dylib             	0x00000001815dcb24 0x1815db000 + 6948
25  libdispatch.dylib             	0x00000001815dcae4 0x1815db000 + 6884
26  libdispatch.dylib             	0x00000001815e3c08 0x1815db000 + 35848
27  libdispatch.dylib             	0x00000001815e9d30 0x1815db000 + 60720
28  libdispatch.dylib             	0x00000001815e9a80 0x1815db000 + 60032
29  libsystem_pthread.dylib       	0x000000018190ffac 0x18190f000 + 4012
30  libsystem_pthread.dylib       	0x000000018190fb08 0x18190f000 + 2824

Thread 37 name:  Dispatch queue: com.apple.coremedia.decompressionsession.clientcallback
Thread 37:
0   libsystem_kernel.dylib        	0x0000000181771be4 0x18174f000 + 142308
1   libsystem_platform.dylib      	0x000000018190ab8c 0x181905000 + 23436
2   libsystem_malloc.dylib        	0x00000001817a7858 0x1817a6000 + 6232
3   libsystem_malloc.dylib        	0x00000001817a75dc 0x1817a6000 + 5596
4   CoreFoundation                	0x0000000181bab468 0x181ba5000 + 25704
5   CoreVideo                     	0x0000000184d9a370 0x184d89000 + 70512
6   CoreVideo                     	0x0000000184d9b944 0x184d89000 + 76100
7   CoreVideo                     	0x0000000184d93bd0 0x184d89000 + 43984
8   CoreMedia                     	0x000000018505fab8 0x184f55000 + 1092280
9   CoreMedia                     	0x000000018505f944 0x184f55000 + 1091908
10  VideoToolbox                  	0x00000001854b9cb4 0x185458000 + 400564
11  libdispatch.dylib             	0x00000001815dcb24 0x1815db000 + 6948
12  libdispatch.dylib             	0x00000001815dcae4 0x1815db000 + 6884
13  libdispatch.dylib             	0x00000001815e6b70 0x1815db000 + 47984
14  libdispatch.dylib             	0x00000001815e7380 0x1815db000 + 50048
15  libdispatch.dylib             	0x00000001815e7d4c 0x1815db000 + 52556
16  libdispatch.dylib             	0x00000001815f011c 0x1815db000 + 86300
17  libsystem_pthread.dylib       	0x000000018190fe70 0x18190f000 + 3696
18  libsystem_pthread.dylib       	0x000000018190fb08 0x18190f000 + 2824

Thread 38 name:  AURemoteIO::IOThread
Thread 38:
0   libsystem_kernel.dylib        	0x0000000181771be4 0x18174f000 + 142308
1   libsystem_platform.dylib      	0x000000018190ab8c 0x181905000 + 23436
2   libsystem_malloc.dylib        	0x00000001817a7858 0x1817a6000 + 6232
3   libsystem_malloc.dylib        	0x00000001817a75dc 0x1817a6000 + 5596
4   libsystem_malloc.dylib        	0x00000001817aa0b0 0x1817a6000 + 16560
5   TXLiteAVSDK_Smart_No_VOD      	0x00000001071e015c 0x107148000 + 622940
6   TXLiteAVSDK_Smart_No_VOD      	0x00000001071de3c0 0x107148000 + 615360
7   AudioToolbox                  	0x00000001859ddd24 0x185805000 + 1936676
8   AudioToolbox                  	0x00000001858c466c 0x185805000 + 783980
9   AudioToolbox                  	0x0000000185c4a8e4 0x185805000 + 4479204
10  AudioToolbox                  	0x0000000185c49f74 0x185805000 + 4476788
11  AudioToolbox                  	0x00000001858c42e4 0x185805000 + 783076
12  AudioToolbox                  	0x00000001858c5730 0x185805000 + 788272
13  AudioToolbox                  	0x0000000185a50618 0x185805000 + 2405912
14  AudioToolbox                  	0x0000000185c33210 0x185805000 + 4383248
15  AudioToolbox                  	0x0000000185c3342c 0x185805000 + 4383788
16  AudioToolbox                  	0x00000001858c4a84 0x185805000 + 785028
17  AudioToolbox                  	0x00000001858c92f0 0x185805000 + 803568
18  AudioToolbox                  	0x0000000185c3b128 0x185805000 + 4415784
19  libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
20  libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
21  libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 39 name:  Dispatch queue: VideoJitterBufferQueue
Thread 39:
0   libsystem_kernel.dylib        	0x000000018177113c 0x18174f000 + 139580
1   libsystem_pthread.dylib       	0x0000000181914604 0x18190f000 + 22020
2   libsystem_pthread.dylib       	0x0000000181914550 0x18190f000 + 21840
3   libc++.1.dylib                	0x0000000180e5bfc4 0x180e21000 + 241604
4   TXLiteAVSDK_Smart_No_VOD      	0x00000001071e5384 0x107148000 + 643972
5   TXLiteAVSDK_Smart_No_VOD      	0x00000001071701a8 0x107148000 + 164264
6   TXLiteAVSDK_Smart_No_VOD      	0x0000000107211ecc 0x107148000 + 827084
7   TXLiteAVSDK_Smart_No_VOD      	0x0000000107211de0 0x107148000 + 826848
8   TXLiteAVSDK_Smart_No_VOD      	0x000000010721166c 0x107148000 + 824940
9   libdispatch.dylib             	0x00000001815dcae4 0x1815db000 + 6884
10  libdispatch.dylib             	0x00000001815e4f18 0x1815db000 + 40728
11  libdispatch.dylib             	0x00000001815ee808 0x1815db000 + 79880
12  libdispatch.dylib             	0x00000001815e68f0 0x1815db000 + 47344
13  libdispatch.dylib             	0x00000001815e7380 0x1815db000 + 50048
14  libdispatch.dylib             	0x00000001815e7d4c 0x1815db000 + 52556
15  libdispatch.dylib             	0x00000001815f011c 0x1815db000 + 86300
16  libsystem_pthread.dylib       	0x000000018190fe70 0x18190f000 + 3696
17  libsystem_pthread.dylib       	0x000000018190fb08 0x18190f000 + 2824

Thread 40:
0   libsystem_kernel.dylib        	0x0000000181771be4 0x18174f000 + 142308
1   libsystem_platform.dylib      	0x000000018190ab8c 0x181905000 + 23436
2   libsystem_malloc.dylib        	0x00000001817b3864 0x1817a6000 + 55396
3   CoreFoundation                	0x0000000181c83850 0x181ba5000 + 911440
4   libsystem_pthread.dylib       	0x000000018191057c 0x18190f000 + 5500
5   libsystem_pthread.dylib       	0x00000001819102cc 0x18190f000 + 4812
6   libsystem_pthread.dylib       	0x00000001819100d4 0x18190f000 + 4308
7   libsystem_pthread.dylib       	0x000000018190fb08 0x18190f000 + 2824

Thread 41:
0   libsystem_kernel.dylib        	0x0000000181771be4 0x18174f000 + 142308
1   libsystem_platform.dylib      	0x000000018190ab8c 0x181905000 + 23436
2   libsystem_malloc.dylib        	0x00000001817a7858 0x1817a6000 + 6232
3   libsystem_malloc.dylib        	0x00000001817aa02c 0x1817a6000 + 16428
4   libsystem_malloc.dylib        	0x00000001817a9f60 0x1817a6000 + 16224
5   libobjc.A.dylib               	0x0000000180eb07d0 0x180e9c000 + 83920
6   libdispatch.dylib             	0x00000001815dcb5c 0x1815db000 + 7004
7   libdispatch.dylib             	0x00000001815f46a8 0x1815db000 + 104104
8   libdispatch.dylib             	0x00000001815f1794 0x1815db000 + 92052
9   libdispatch.dylib             	0x00000001815f82e0 0x1815db000 + 119520
10  libdispatch.dylib             	0x00000001815f006c 0x1815db000 + 86124
11  libsystem_pthread.dylib       	0x000000018190fe70 0x18190f000 + 3696
12  libsystem_pthread.dylib       	0x000000018190fb08 0x18190f000 + 2824

Thread 42 name:  Dispatch queue: com.apple.UIKit.KeyboardManagement
Thread 42:
0   libsystem_kernel.dylib        	0x0000000181771be4 0x18174f000 + 142308
1   libsystem_platform.dylib      	0x000000018190ab8c 0x181905000 + 23436
2   libsystem_malloc.dylib        	0x00000001817a7858 0x1817a6000 + 6232
3   libsystem_malloc.dylib        	0x00000001817aa02c 0x1817a6000 + 16428
4   libsystem_malloc.dylib        	0x00000001817a9f60 0x1817a6000 + 16224
5   libobjc.A.dylib               	0x0000000180eb07d0 0x180e9c000 + 83920
6   libobjc.A.dylib               	0x0000000180ec2d8c 0x180e9c000 + 159116
7   Foundation                    	0x0000000182650e84 0x18261d000 + 212612
8   Foundation                    	0x0000000182673ac0 0x18261d000 + 355008
9   libxpc.dylib                  	0x000000018194b220 0x181946000 + 21024
10  libxpc.dylib                  	0x0000000181948bb4 0x181946000 + 11188
11  libdispatch.dylib             	0x00000001815dcbb4 0x1815db000 + 7092
12  libdispatch.dylib             	0x00000001815f34c4 0x1815db000 + 99524
13  libdispatch.dylib             	0x00000001815e68f0 0x1815db000 + 47344
14  libdispatch.dylib             	0x00000001815f3f70 0x1815db000 + 102256
15  libdispatch.dylib             	0x00000001815e68f0 0x1815db000 + 47344
16  libdispatch.dylib             	0x00000001815e7380 0x1815db000 + 50048
17  libdispatch.dylib             	0x00000001815e7d4c 0x1815db000 + 52556
18  libdispatch.dylib             	0x00000001815f011c 0x1815db000 + 86300
19  libsystem_pthread.dylib       	0x000000018190fe70 0x18190f000 + 3696
20  libsystem_pthread.dylib       	0x000000018190fb08 0x18190f000 + 2824

Thread 43 name:  Dispatch queue: com.apple.CoreLocation.ConnectionClient.0x11ece4150.events
Thread 43:
0   libsystem_kernel.dylib        	0x0000000181771be4 0x18174f000 + 142308
1   libsystem_platform.dylib      	0x000000018190ab8c 0x181905000 + 23436
2   libsystem_malloc.dylib        	0x00000001817a7858 0x1817a6000 + 6232
3   libsystem_malloc.dylib        	0x00000001817aa02c 0x1817a6000 + 16428
4   libsystem_malloc.dylib        	0x00000001817a9f60 0x1817a6000 + 16224
5   CoreFoundation                	0x0000000181bab02c 0x181ba5000 + 24620
6   CoreFoundation                	0x0000000181ca5e24 0x181ba5000 + 1052196
7   CoreFoundation                	0x0000000181bac6a0 0x181ba5000 + 30368
8   Foundation                    	0x00000001826240d8 0x18261d000 + 28888
9   CoreLocation                  	0x00000001884b4934 0x188459000 + 375092
10  CoreLocation                  	0x00000001884b4850 0x188459000 + 374864
11  CoreLocation                  	0x00000001884b62ac 0x188459000 + 381612
12  libxpc.dylib                  	0x000000018194b220 0x181946000 + 21024
13  libxpc.dylib                  	0x0000000181948bb4 0x181946000 + 11188
14  libdispatch.dylib             	0x00000001815dcbb4 0x1815db000 + 7092
15  libdispatch.dylib             	0x00000001815f34c4 0x1815db000 + 99524
16  libdispatch.dylib             	0x00000001815e68f0 0x1815db000 + 47344
17  libdispatch.dylib             	0x00000001815f3f70 0x1815db000 + 102256
18  libdispatch.dylib             	0x00000001815e68f0 0x1815db000 + 47344
19  libdispatch.dylib             	0x00000001815e7380 0x1815db000 + 50048
20  libdispatch.dylib             	0x00000001815e68f0 0x1815db000 + 47344
21  libdispatch.dylib             	0x00000001815e7380 0x1815db000 + 50048
22  libdispatch.dylib             	0x00000001815e7d4c 0x1815db000 + 52556
23  libdispatch.dylib             	0x00000001815f011c 0x1815db000 + 86300
24  libsystem_pthread.dylib       	0x000000018190fe70 0x18190f000 + 3696
25  libsystem_pthread.dylib       	0x000000018190fb08 0x18190f000 + 2824

Thread 44 name:  Dispatch queue: com.apple.MediaRemote.clientCallbackPriorityQueue
Thread 44:
0   libsystem_kernel.dylib        	0x0000000181771be4 0x18174f000 + 142308
1   libsystem_platform.dylib      	0x000000018190ab8c 0x181905000 + 23436
2   libsystem_malloc.dylib        	0x00000001817a7858 0x1817a6000 + 6232
3   libsystem_malloc.dylib        	0x00000001817aa02c 0x1817a6000 + 16428
4   libsystem_malloc.dylib        	0x00000001817a9f60 0x1817a6000 + 16224
5   CoreFoundation                	0x0000000181bab02c 0x181ba5000 + 24620
6   CoreFoundation                	0x0000000181ca5e24 0x181ba5000 + 1052196
7   CoreFoundation                	0x0000000181bb1fc4 0x181ba5000 + 53188
8   MediaRemote                   	0x000000018db73160 0x18dae3000 + 590176
9   MediaRemote                   	0x000000018db2b890 0x18dae3000 + 297104
10  libdispatch.dylib             	0x00000001815ea6fc 0x1815db000 + 63228
11  libdispatch.dylib             	0x00000001815dcae4 0x1815db000 + 6884
12  libdispatch.dylib             	0x00000001815e6a38 0x1815db000 + 47672
13  libdispatch.dylib             	0x00000001815e7380 0x1815db000 + 50048
14  libdispatch.dylib             	0x00000001815e7d4c 0x1815db000 + 52556
15  libdispatch.dylib             	0x00000001815f011c 0x1815db000 + 86300
16  libsystem_pthread.dylib       	0x000000018190fe70 0x18190f000 + 3696
17  libsystem_pthread.dylib       	0x000000018190fb08 0x18190f000 + 2824

Thread 45:
0   libsystem_pthread.dylib       	0x000000018190fb04 0x18190f000 + 2820

Thread 46:
0   libsystem_kernel.dylib        	0x000000018174fe5c 0x18174f000 + 3676
1   libdispatch.dylib             	0x00000001815df0b0 0x1815db000 + 16560
2   libdispatch.dylib             	0x00000001815df924 0x1815db000 + 18724
3   libdispatch.dylib             	0x00000001815eb23c 0x1815db000 + 66108
4   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
5   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
6   libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 47:
0   libsystem_kernel.dylib        	0x000000018174fe5c 0x18174f000 + 3676
1   libdispatch.dylib             	0x00000001815df0b0 0x1815db000 + 16560
2   libdispatch.dylib             	0x00000001815df924 0x1815db000 + 18724
3   libdispatch.dylib             	0x00000001815eb23c 0x1815db000 + 66108
4   libsystem_pthread.dylib       	0x0000000181911220 0x18190f000 + 8736
5   libsystem_pthread.dylib       	0x0000000181911110 0x18190f000 + 8464
6   libsystem_pthread.dylib       	0x000000018190fb10 0x18190f000 + 2832

Thread 48 name:  Dispatch queue: com.apple.coremedia.routediscoverer.xpc.notifications
Thread 48:
0   libsystem_kernel.dylib        	0x0000000181771be4 0x18174f000 + 142308
1   libsystem_platform.dylib      	0x000000018190ab8c 0x181905000 + 23436
2   libsystem_malloc.dylib        	0x00000001817a7858 0x1817a6000 + 6232
3   libsystem_malloc.dylib        	0x00000001817aa02c 0x1817a6000 + 16428
4   libsystem_malloc.dylib        	0x00000001817a9f60 0x1817a6000 + 16224
5   CoreFoundation                	0x0000000181bab02c 0x181ba5000 + 24620
6   CoreFoundation                	0x0000000181baaf60 0x181ba5000 + 24416
7   CoreFoundation                	0x0000000181bb3cd8 0x181ba5000 + 60632
8   CoreFoundation                	0x0000000181bc2d74 0x181ba5000 + 122228
9   CoreFoundation                	0x0000000181d49048 0x181ba5000 + 1720392
10  CoreFoundation                	0x0000000181cf97cc 0x181ba5000 + 1394636
11  CoreFoundation                	0x0000000181bb2f38 0x181ba5000 + 57144
12  AVFoundation                  	0x0000000187818f24 0x187707000 + 1122084
13  CoreFoundation                	0x0000000181c7cc3c 0x181ba5000 + 883772
14  CoreFoundation                	0x0000000181c7c1b8 0x181ba5000 + 881080
15  CoreFoundation                	0x0000000181c7bf14 0x181ba5000 + 880404
16  CoreFoundation                	0x0000000181cf984c 0x181ba5000 + 1394764
17  CoreFoundation                	0x0000000181bb2f38 0x181ba5000 + 57144
18  CoreFoundation                	0x0000000181bd68f0 0x181ba5000 + 202992
19  CoreMedia                     	0x0000000184f7d488 0x184f55000 + 165000
20  CoreMedia                     	0x0000000185089314 0x184f55000 + 1262356
21  libdispatch.dylib             	0x00000001815dcb24 0x1815db000 + 6948
22  libdispatch.dylib             	0x00000001815dcae4 0x1815db000 + 6884
23  libdispatch.dylib             	0x00000001815e6a38 0x1815db000 + 47672
24  libdispatch.dylib             	0x00000001815e7380 0x1815db000 + 50048
25  libdispatch.dylib             	0x00000001815e7d4c 0x1815db000 + 52556
26  libdispatch.dylib             	0x00000001815f011c 0x1815db000 + 86300
27  libsystem_pthread.dylib       	0x000000018190fe70 0x18190f000 + 3696
28  libsystem_pthread.dylib       	0x000000018190fb08 0x18190f000 + 2824

Thread 0 crashed with ARM Thread State (64-bit):
    x0: 0xfffffffffffffffc   x1: 0x0000000000000000   x2: 0x0000000000028832   x3: 0x0000000000000000
    x4: 0x0000000000000000   x5: 0x0000000000000010   x6: 0x0000000000000000   x7: 0x0000000000000000
    x8: 0x0000000000028832   x9: 0x0000000000028833  x10: 0x0000000000000001  x11: 0x0000000200000003
   x12: 0x000000011ec0ff90  x13: 0x000001a1b40e5419  x14: 0x40bea83578604024  x15: 0x0000000000000000
   x16: 0x0000000000000203  x17: 0x0000000180ec303c  x18: 0x0000000000000000  x19: 0x0000000000000303
   x20: 0x0000000000010000  x21: 0x000000010a6e8a00  x22: 0x0000000001010002  x23: 0x0000000000028832
   x24: 0x0000000000000303  x25: 0x0000000000000000  x26: 0x000000010a6e8a00  x27: 0x0000000000000ac0
   x28: 0x0000000000000000   fp: 0x000000016d968c60   lr: 0x000000018190ab8c
    sp: 0x000000016d968c30   pc: 0x0000000181771be4 cpsr: 0x40000000

Binary Images:
0x102494000 - 0x105dc7fff WeChat arm64  <ff76441689363a18bc6764ead6a25219> /var/containers/Bundle/Application/82C6B9C0-6902-45C6-BB98-629308C347E0/WeChat.app/WeChat
0x106ecc000 - 0x106f9ffff Matrix arm64  <68f8ef7d3e7d33d08ac83ba7c37b23a3> /var/containers/Bundle/Application/82C6B9C0-6902-45C6-BB98-629308C347E0/WeChat.app/Frameworks/Matrix.framework/Matrix
0x1070b4000 - 0x1070effff dyld arm64  <06dc98224ae03573bf72c78810c81a78> /usr/lib/dyld
0x107148000 - 0x107423fff TXLiteAVSDK_Smart_No_VOD arm64  <b4916eb15e683264a00885908af5cc26> /var/containers/Bundle/Application/82C6B9C0-6902-45C6-BB98-629308C347E0/WeChat.app/Frameworks/TXLiteAVSDK_Smart_No_VOD.framework/TXLiteAVSDK_Smart_No_VOD
0x107884000 - 0x107d97fff YTFaceProSDK arm64  <c0ff3fc868563b96b5e4853888b3487a> /var/containers/Bundle/Application/82C6B9C0-6902-45C6-BB98-629308C347E0/WeChat.app/Frameworks/YTFaceProSDK.framework/YTFaceProSDK
0x108060000 - 0x1080d7fff GPUImage arm64  <847b060687ca3896ae1690df0370dc94> /var/containers/Bundle/Application/82C6B9C0-6902-45C6-BB98-629308C347E0/WeChat.app/Frameworks/GPUImage.framework/GPUImage
0x108198000 - 0x10836ffff WCDB arm64  <21cec2a7dc043d878d4efc4afdaf0ae9> /var/containers/Bundle/Application/82C6B9C0-6902-45C6-BB98-629308C347E0/WeChat.app/Frameworks/WCDB.framework/WCDB
0x1085d4000 - 0x10872bfff MMCommon arm64  <d3736e9165e73e54ab99d32bbb48d00d> /var/containers/Bundle/Application/82C6B9C0-6902-45C6-BB98-629308C347E0/WeChat.app/Frameworks/MMCommon.framework/MMCommon
0x108784000 - 0x108c8bfff MultiMedia arm64  <17e66798bb6e347387ea016be0a26acf> /var/containers/Bundle/Application/82C6B9C0-6902-45C6-BB98-629308C347E0/WeChat.app/Frameworks/MultiMedia.framework/MultiMedia
0x108fd4000 - 0x109157fff QBar arm64  <763a6548939c3ddcaa8ae935d3a61451> /var/containers/Bundle/Application/82C6B9C0-6902-45C6-BB98-629308C347E0/WeChat.app/Frameworks/QBar.framework/QBar
0x109258000 - 0x10942bfff QMapKit arm64  <814b78aff08934f9a869f76bebed1e49> /var/containers/Bundle/Application/82C6B9C0-6902-45C6-BB98-629308C347E0/WeChat.app/Frameworks/QMapKit.framework/QMapKit
0x1095b0000 - 0x10994bfff ConfSDK arm64  <a1841ff4797c327f896c0a747b3cb699> /var/containers/Bundle/Application/82C6B9C0-6902-45C6-BB98-629308C347E0/WeChat.app/Frameworks/ConfSDK.framework/ConfSDK
0x1099ac000 - 0x10a097fff mars arm64  <c49c700ae8b53f4093adae8cfd56c332> /var/containers/Bundle/Application/82C6B9C0-6902-45C6-BB98-629308C347E0/WeChat.app/Frameworks/mars.framework/mars
0x180e1f000 - 0x180e20fff libSystem.B.dylib arm64  <1cbfa6a1a0fb3fc99264d3d30ca0e543> /usr/lib/libSystem.B.dylib
0x180e21000 - 0x180e79fff libc++.1.dylib arm64  <c7c7e60bd59e3193a63b35cc54e32e79> /usr/lib/libc++.1.dylib
0x180e7a000 - 0x180e9bfff libc++abi.dylib arm64  <086faefd537e3954b23565f56653a2cb> /usr/lib/libc++abi.dylib
0x180e9c000 - 0x181557fff libobjc.A.dylib arm64  <bedd6199d0d33b52a5387380f9350b30> /usr/lib/libobjc.A.dylib
0x181558000 - 0x18155dfff libcache.dylib arm64  <9234c7627b253d1ba2b18cd9aaadbe2e> /usr/lib/system/libcache.dylib
0x18155e000 - 0x181569fff libcommonCrypto.dylib arm64  <50eeb933dceb3aa28a43dd3a791139ce> /usr/lib/system/libcommonCrypto.dylib
0x18156a000 - 0x18156dfff libcompiler_rt.dylib arm64  <d2ba481dad4f3cb0b5a2ba5abc20196f> /usr/lib/system/libcompiler_rt.dylib
0x18156e000 - 0x181576fff libcopyfile.dylib arm64  <d97ef07e910c32c385b8d1ee23759cf0> /usr/lib/system/libcopyfile.dylib
0x181577000 - 0x1815dafff libcorecrypto.dylib arm64  <e9cc7328986b3319a9475935e62e29cb> /usr/lib/system/libcorecrypto.dylib
0x1815db000 - 0x181640fff libdispatch.dylib arm64  <42fe29ae709d39d9bc00f31af92baaf1> /usr/lib/system/libdispatch.dylib
0x181641000 - 0x18165bfff libdyld.dylib arm64  <b0123d033ab93dc7a5e2c35556740a26> /usr/lib/system/libdyld.dylib
0x18165c000 - 0x18165cfff liblaunch.dylib arm64  <5d50c01da0fb3538bce8415db84cf1eb> /usr/lib/system/liblaunch.dylib
0x18165d000 - 0x181662fff libmacho.dylib arm64  <c39a1c9473413310a32c271a3f49fd58> /usr/lib/system/libmacho.dylib
0x181663000 - 0x181664fff libremovefile.dylib arm64  <b2d52ec838503fc190db54488d05afd3> /usr/lib/system/libremovefile.dylib
0x181665000 - 0x18167bfff libsystem_asl.dylib arm64  <5d19da723b2d3036b96bbe9569d99d5b> /usr/lib/system/libsystem_asl.dylib
0x18167c000 - 0x18167cfff libsystem_blocks.dylib arm64  <9a69557f7f5d35e6b2bb4c8cb55b43b6> /usr/lib/system/libsystem_blocks.dylib
0x18167d000 - 0x1816fafff libsystem_c.dylib arm64  <253425c2089e3d4d99cc1d073d72efe5> /usr/lib/system/libsystem_c.dylib
0x1816fb000 - 0x1816fffff libsystem_configuration.dylib arm64  <1f70ae27eb2d31ecb98b4b45f5b82ad9> /usr/lib/system/libsystem_configuration.dylib
0x181700000 - 0x181705fff libsystem_containermanager.dylib arm64  <3a312c5c347d3fcab6227fb824849657> /usr/lib/system/libsystem_containermanager.dylib
0x181706000 - 0x181707fff libsystem_coreservices.dylib arm64  <70bb743b7bf53de1afdf6f7afcce1379> /usr/lib/system/libsystem_coreservices.dylib
0x181708000 - 0x181709fff libsystem_darwin.dylib arm64  <90fe2ed455e4396aa662e5e32fd80b84> /usr/lib/system/libsystem_darwin.dylib
0x18170a000 - 0x181710fff libsystem_dnssd.dylib arm64  <45af7516ceab3b94905cd74b35f4eab6> /usr/lib/system/libsystem_dnssd.dylib
0x181711000 - 0x18174efff libsystem_info.dylib arm64  <515624006f30300186f77a218ef98326> /usr/lib/system/libsystem_info.dylib
0x18174f000 - 0x181777fff libsystem_kernel.dylib arm64  <ab53a0ff551a3b63855eb75271fc5909> /usr/lib/system/libsystem_kernel.dylib
0x181778000 - 0x1817a5fff libsystem_m.dylib arm64  <cba9a1ee1d553c189dbaca4f6e13ca5e> /usr/lib/system/libsystem_m.dylib
0x1817a6000 - 0x1817c1fff libsystem_malloc.dylib arm64  <ad49e1b2657639f3a9beea6edc18675c> /usr/lib/system/libsystem_malloc.dylib
0x1817c2000 - 0x1818edfff libsystem_network.dylib arm64  <6762e60b7af83d2e86468be0ac6b4fa0> /usr/lib/system/libsystem_network.dylib
0x1818ee000 - 0x1818f9fff libsystem_networkextension.dylib arm64  <d86851bd3b4d344588462ae9a88344f9> /usr/lib/system/libsystem_networkextension.dylib
0x1818fa000 - 0x181904fff libsystem_notify.dylib arm64  <5bd9385d98c83d0ba9d157e69c429638> /usr/lib/system/libsystem_notify.dylib
0x181905000 - 0x18190efff libsystem_platform.dylib arm64  <038fc12926e83453a11b59ef3b1096c9> /usr/lib/system/libsystem_platform.dylib
0x18190f000 - 0x18191efff libsystem_pthread.dylib arm64  <01327cdfaac23c388fadf36cf440f0e2> /usr/lib/system/libsystem_pthread.dylib
0x18191f000 - 0x181922fff libsystem_sandbox.dylib arm64  <abbe277dbe993c47b59a813ca4797651> /usr/lib/system/libsystem_sandbox.dylib
0x181923000 - 0x18192afff libsystem_symptoms.dylib arm64  <7fc5e7245e09393aa5d003dceeffa74b> /usr/lib/system/libsystem_symptoms.dylib
0x18192b000 - 0x18193efff libsystem_trace.dylib arm64  <9bfe9e9e10b9385787a827c768ba54bf> /usr/lib/system/libsystem_trace.dylib
0x18193f000 - 0x181944fff libunwind.dylib arm64  <7e526b97e5b039e6a1c78107321592aa> /usr/lib/system/libunwind.dylib
0x181945000 - 0x181945fff libvminterpose.dylib arm64  <39d037ec6db036179470ab258fc96c13> /usr/lib/system/libvminterpose.dylib
0x181946000 - 0x181970fff libxpc.dylib arm64  <9bc6486ebaa83cc580e90415889c978d> /usr/lib/system/libxpc.dylib
0x181971000 - 0x181b92fff libicucore.A.dylib arm64  <afad4c33ff30367286e9c60b75a95a5a> /usr/lib/libicucore.A.dylib
0x181b93000 - 0x181ba4fff libz.1.dylib arm64  <39dcd0297ee130c891937f50ce23c2df> /usr/lib/libz.1.dylib
0x181ba5000 - 0x181f3bfff CoreFoundation arm64  <cf162b3ca2883453b2914300d4f19612> /System/Library/Frameworks/CoreFoundation.framework/CoreFoundation
0x181f3c000 - 0x181f4cfff libbsm.0.dylib arm64  <3f8b35c8ab283b78a319327ea597212e> /usr/lib/libbsm.0.dylib
0x181f4d000 - 0x181f4dfff libenergytrace.dylib arm64  <cfbe9a511fd73ee2ba237aa7400137c6> /usr/lib/libenergytrace.dylib
0x181f4e000 - 0x181fd2fff IOKit arm64  <56754e706db43267b2e2bc4387e34f2b> /System/Library/Frameworks/IOKit.framework/Versions/A/IOKit
0x181fd3000 - 0x1820bafff libxml2.2.dylib arm64  <21cc9796ecb933e8b3e12f53e04148f7> /usr/lib/libxml2.2.dylib
0x1820bb000 - 0x1820c8fff libbz2.1.0.dylib arm64  <63ddef9a83dc335a9df0bef913f437a7> /usr/lib/libbz2.1.0.dylib
0x1820c9000 - 0x1820e1fff liblzma.5.dylib arm64  <252187562a8c3e07b7f01473a16c00d7> /usr/lib/liblzma.5.dylib
0x1820e2000 - 0x182246fff libsqlite3.dylib arm64  <caacdb193a86339db7943325571a25af> /usr/lib/libsqlite3.dylib
0x182247000 - 0x18226dfff libMobileGestalt.dylib arm64  <816e5c2426243ca5a8e6b3b2b9521776> /usr/lib/libMobileGestalt.dylib
0x18226e000 - 0x18261cfff CFNetwork arm64  <4f38683f50453eaa9a09eb6222eae139> /System/Library/Frameworks/CFNetwork.framework/CFNetwork
0x18261d000 - 0x182915fff Foundation arm64  <18908b96750c38988eb0d7028c656a6d> /System/Library/Frameworks/Foundation.framework/Foundation
0x182916000 - 0x182a16fff Security arm64  <fccc95fb50db3b55ae66518f7f789f70> /System/Library/Frameworks/Security.framework/Security
0x182a17000 - 0x182a82fff SystemConfiguration arm64  <0caa3f1372c637f791d1aae47629aed1> /System/Library/Frameworks/SystemConfiguration.framework/SystemConfiguration
0x182a83000 - 0x182ab8fff libCRFSuite.dylib arm64  <7d19be0f618136a1a3bc7e81caba4b6d> /usr/lib/libCRFSuite.dylib
0x182ab9000 - 0x182ab9fff libapple_crypto.dylib arm64  <fcf4f720aac03727b5842dd31fd3ef7e> /usr/lib/libapple_crypto.dylib
0x182aba000 - 0x182ad0fff libapple_nghttp2.dylib arm64  <8d5134e490ad3c298330609806547a9e> /usr/lib/libapple_nghttp2.dylib
0x182ad1000 - 0x182afafff libarchive.2.dylib arm64  <93fac4c1f6b73383a9082c6a963da406> /usr/lib/libarchive.2.dylib
0x182afb000 - 0x182ba9fff libboringssl.dylib arm64  <8b812051a23e35b8a22e4c272887ecf7> /usr/lib/libboringssl.dylib
0x182baa000 - 0x182bc0fff libcoretls.dylib arm64  <a016bdc075493ee7a0dd4f4c0daa7f32> /usr/lib/libcoretls.dylib
0x182bc1000 - 0x182bc2fff libcoretls_cfhelpers.dylib arm64  <f3b0bd7eedbe3df8a5944d8a737536f0> /usr/lib/libcoretls_cfhelpers.dylib
0x182bc3000 - 0x182bc4fff liblangid.dylib arm64  <d66b69c96718352ba9c4092aa6416627> /usr/lib/liblangid.dylib
0x182bc5000 - 0x182d3afff libnetwork.dylib arm64  <f087d7ee39b53e7c83a4c1ecb36a3477> /usr/lib/libnetwork.dylib
0x182d3b000 - 0x182d6dfff libpcap.A.dylib arm64  <36ff48f819553b0c9e92c9fb2aa1a4a2> /usr/lib/libpcap.A.dylib
0x182d6e000 - 0x182dcafff libusrtcp.dylib arm64  <b8b2aa241bcd3d1ca213587a9959920d> /usr/lib/libusrtcp.dylib
0x182dcb000 - 0x182dd5fff IOSurface arm64  <a87bce11aabd303c9d9a6cc0009e9f57> /System/Library/Frameworks/IOSurface.framework/IOSurface
0x182dd6000 - 0x182e7bfff libBLAS.dylib arm64  <50b5f5beeab037ffa5810a67e580bdbf> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libBLAS.dylib
0x182e7c000 - 0x18319cfff libLAPACK.dylib arm64  <c8440bf2dc0b39c79ada236a548df940> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libLAPACK.dylib
0x18319d000 - 0x18340cfff vImage arm64  <8f3ffa6be7e43dfdaf027891d655a60e> /System/Library/Frameworks/Accelerate.framework/Frameworks/vImage.framework/vImage
0x18340d000 - 0x18341efff libSparseBLAS.dylib arm64  <d216b492dfb0311a8ccd19e4a930dd04> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libSparseBLAS.dylib
0x18341f000 - 0x183443fff libvMisc.dylib arm64  <483df9b3d90331888b43bb65d802485f> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libvMisc.dylib
0x183444000 - 0x18346bfff libBNNS.dylib arm64  <982f32f4102133d2802ea5f81cdc13a8> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libBNNS.dylib
0x18346c000 - 0x183480fff libLinearAlgebra.dylib arm64  <a3ec23fe236e303384df33cf2fb24d96> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libLinearAlgebra.dylib
0x183481000 - 0x183485fff libQuadrature.dylib arm64  <5a98c0d39e0d38f89ce20797be797ac8> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libQuadrature.dylib
0x183486000 - 0x1834f5fff libSparse.dylib arm64  <6556be33563434b78e2ef1c80da99eb7> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libSparse.dylib
0x1834f6000 - 0x183581fff libvDSP.dylib arm64  <4de8af8c7371382b9183e4dc14245445> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/libvDSP.dylib
0x183582000 - 0x183582fff vecLib arm64  <2d93d3f4573b313d81fc9104810f0f61> /System/Library/Frameworks/Accelerate.framework/Frameworks/vecLib.framework/vecLib
0x183583000 - 0x183583fff Accelerate arm64  <850c55e76100327ea543af936487944c> /System/Library/Frameworks/Accelerate.framework/Accelerate
0x183584000 - 0x18359afff libcompression.dylib arm64  <9a090a94c6463eefa5413f012a34d3a4> /usr/lib/libcompression.dylib
0x18359b000 - 0x183ae2fff CoreGraphics arm64  <ac1e1c54697f3378ac6168a46dcccfe7> /System/Library/Frameworks/CoreGraphics.framework/CoreGraphics
0x183ae3000 - 0x183ae8fff IOAccelerator arm64  <83c3c1fcfd963ec4b3c15ca18ea71efe> /System/Library/PrivateFrameworks/IOAccelerator.framework/IOAccelerator
0x183ae9000 - 0x183aeefff libCoreFSCache.dylib arm64  <e49f9dc0e85f3df0b0cd284c2477b315> /System/Library/Frameworks/OpenGLES.framework/libCoreFSCache.dylib
0x183aef000 - 0x183b87fff Metal arm64  <46fc1e5f11c5316991cb5d7a0aa46523> /System/Library/Frameworks/Metal.framework/Metal
0x183b88000 - 0x183b9bfff GraphicsServices arm64  <85072ece665a3a86807f153e85476fed> /System/Library/PrivateFrameworks/GraphicsServices.framework/GraphicsServices
0x183b9c000 - 0x183cf5fff MobileCoreServices arm64  <cc1d833f73a73822a52d8a9fe16a8dc3> /System/Library/Frameworks/MobileCoreServices.framework/MobileCoreServices
0x183cf6000 - 0x183cf8fff IOSurfaceAccelerator arm64  <7b5129072b7f3d128f701b1b950bcdf3> /System/Library/PrivateFrameworks/IOSurfaceAccelerator.framework/IOSurfaceAccelerator
0x183cf9000 - 0x183d3afff AppleJPEG arm64  <c82f8d506055358d9f786fa34f589827> /System/Library/PrivateFrameworks/AppleJPEG.framework/AppleJPEG
0x183d3b000 - 0x1842ebfff ImageIO arm64  <df52144b9f6f3491a1aaca4affcd69cf> /System/Library/Frameworks/ImageIO.framework/ImageIO
0x1842ec000 - 0x18434ffff BaseBoard arm64  <4a9ddf31f3443b6e9a17e272aebe2b8d> /System/Library/PrivateFrameworks/BaseBoard.framework/BaseBoard
0x184350000 - 0x184367fff AssertionServices arm64  <d4bbd03e4bef3c6d83871dfe9360d2ca> /System/Library/PrivateFrameworks/AssertionServices.framework/AssertionServices
0x184368000 - 0x184370fff CorePhoneNumbers arm64  <2cacbb2a053f314d9c6b6df55b4cea0c> /System/Library/PrivateFrameworks/CorePhoneNumbers.framework/CorePhoneNumbers
0x184371000 - 0x1843b5fff AppSupport arm64  <f518c3a1857533658da18b3c9649da9c> /System/Library/PrivateFrameworks/AppSupport.framework/AppSupport
0x1843b6000 - 0x1843cefff CrashReporterSupport arm64  <f4188f55b716379fb5857229217154a2> /System/Library/PrivateFrameworks/CrashReporterSupport.framework/CrashReporterSupport
0x1843cf000 - 0x1843d4fff AggregateDictionary arm64  <3e27a71f9459361193f3e182dc87d3b0> /System/Library/PrivateFrameworks/AggregateDictionary.framework/AggregateDictionary
0x1843d5000 - 0x184459fff libTelephonyUtilDynamic.dylib arm64  <f78c5716e31c3ce7a566a179b347a55a> /usr/lib/libTelephonyUtilDynamic.dylib
0x18445a000 - 0x184479fff ProtocolBuffer arm64  <ec0dcc2ab28c36c59afaf485b79ebeae> /System/Library/PrivateFrameworks/ProtocolBuffer.framework/ProtocolBuffer
0x18447a000 - 0x1844a6fff MobileKeyBag arm64  <19ed6cab7991380796131d9815a7e3df> /System/Library/PrivateFrameworks/MobileKeyBag.framework/MobileKeyBag
0x1844a7000 - 0x1844dbfff BackBoardServices arm64  <e4567934c6fc3c029a385d0141469c88> /System/Library/PrivateFrameworks/BackBoardServices.framework/BackBoardServices
0x1844dc000 - 0x184537fff FrontBoardServices arm64  <1f63db3e11403909903a700f99bbafe5> /System/Library/PrivateFrameworks/FrontBoardServices.framework/FrontBoardServices
0x184538000 - 0x184574fff SpringBoardServices arm64  <618c22ec2c98329f8bb23caa50a4f53c> /System/Library/PrivateFrameworks/SpringBoardServices.framework/SpringBoardServices
0x184575000 - 0x184583fff PowerLog arm64  <85efbdc068743b57a7dc8cf1115869ae> /System/Library/PrivateFrameworks/PowerLog.framework/PowerLog
0x184584000 - 0x1845a0fff CommonUtilities arm64  <a4dce370f84f3b2c932007b704a3e959> /System/Library/PrivateFrameworks/CommonUtilities.framework/CommonUtilities
0x1845a1000 - 0x1845acfff liblockdown.dylib arm64  <6ca17ea36c9b3d8a80b1b4d147ba35f9> /usr/lib/liblockdown.dylib
0x1845ad000 - 0x1848b1fff CoreData arm64  <c76c9faa57d032dca0adc9c7b82d2791> /System/Library/Frameworks/CoreData.framework/CoreData
0x1848b2000 - 0x1848b8fff TCC arm64  <5b6e4c731ff931a499b5c45cfd742c6c> /System/Library/PrivateFrameworks/TCC.framework/TCC
0x1848b9000 - 0x1848c0fff libcupolicy.dylib arm64  <0ef300210d2a342195796022e2a17e73> /usr/lib/libcupolicy.dylib
0x1848c1000 - 0x184952fff CoreTelephony arm64  <3a7e603987983d8ca966b29eb8aa08fa> /System/Library/Frameworks/CoreTelephony.framework/CoreTelephony
0x184953000 - 0x1849aafff Accounts arm64  <a66a44902f0d333e8334b8561b40e90a> /System/Library/Frameworks/Accounts.framework/Accounts
0x1849ab000 - 0x1849d4fff AppleSauce arm64  <708bf2e767363eaaae3d41e17e0a0e86> /System/Library/PrivateFrameworks/AppleSauce.framework/AppleSauce
0x1849d5000 - 0x1849ddfff DataMigration arm64  <3db16bbf04603c5da1bd70c06c7cb464> /System/Library/PrivateFrameworks/DataMigration.framework/DataMigration
0x1849de000 - 0x1849e4fff Netrb arm64  <bf6409fc10343ba89e6c06a15df7a915> /System/Library/PrivateFrameworks/Netrb.framework/Netrb
0x1849e5000 - 0x184a17fff PersistentConnection arm64  <644d574b0cb33cf0bcaa55f353b636d1> /System/Library/PrivateFrameworks/PersistentConnection.framework/PersistentConnection
0x184a18000 - 0x184a29fff libmis.dylib arm64  <750810cf779d3946964aa5ee4a44f063> /usr/lib/libmis.dylib
0x184a2a000 - 0x184b30fff ManagedConfiguration arm64  <ddb1689e2c493216aa42aefb91f60588> /System/Library/PrivateFrameworks/ManagedConfiguration.framework/ManagedConfiguration
0x184b31000 - 0x184b36fff libReverseProxyDevice.dylib arm64  <7c2f9a593dd03a90855450c4b3b2208e> /usr/lib/libReverseProxyDevice.dylib
0x184b37000 - 0x184b49fff libamsupport.dylib arm64  <6c1d65704dfc3b9b87980cd65560188e> /usr/lib/libamsupport.dylib
0x184b4a000 - 0x184b4ffff libCoreVMClient.dylib arm64  <8cfed6ca663f30748dd58b598a23169d> /System/Library/Frameworks/OpenGLES.framework/libCoreVMClient.dylib
0x184b50000 - 0x184b51fff libCVMSPluginSupport.dylib arm64  <4bf21a6ca33d3222bd1442c13450464d> /System/Library/Frameworks/OpenGLES.framework/libCVMSPluginSupport.dylib
0x184b52000 - 0x184b55fff libutil.dylib arm64  <2f7e5961d4b734b496f3d85eae03acd1> /usr/lib/libutil.dylib
0x184b56000 - 0x184b96fff libGLImage.dylib arm64  <9c2f70ff46913e4f9dc66605475914f9> /System/Library/Frameworks/OpenGLES.framework/libGLImage.dylib
0x184b97000 - 0x184c0dfff APFS arm64  <075ddba3fa093db78988256945f50ff9> /System/Library/PrivateFrameworks/APFS.framework/APFS
0x184c0e000 - 0x184c3ffff MediaKit arm64  <82856e94773c33f5a67a8eb4c1c6148e> /System/Library/PrivateFrameworks/MediaKit.framework/MediaKit
0x184c40000 - 0x184c58fff libSERestoreInfo.dylib arm64  <3cb3e784ed3e389894f58e4b9fc7bb4e> /usr/lib/updaters/libSERestoreInfo.dylib
0x184c5d000 - 0x184c99fff DiskImages arm64  <198c6094f9c237698130c80de266469b> /System/Library/PrivateFrameworks/DiskImages.framework/DiskImages
0x184c9a000 - 0x184ca3fff libGFXShared.dylib arm64  <ed4ebad5d4c33bc28402efe87dbe49a3> /System/Library/Frameworks/OpenGLES.framework/libGFXShared.dylib
0x184ca4000 - 0x184cebfff libauthinstall.dylib arm64  <dd4427dc0adb323fa26a58d1781bf907> /usr/lib/libauthinstall.dylib
0x184cec000 - 0x184cf4fff IOMobileFramebuffer arm64  <f7a97755a31e39119cc617a8d67ca244> /System/Library/PrivateFrameworks/IOMobileFramebuffer.framework/IOMobileFramebuffer
0x184cf5000 - 0x184d00fff OpenGLES arm64  <fcb36165f660338c97d330e51329838f> /System/Library/Frameworks/OpenGLES.framework/OpenGLES
0x184d01000 - 0x184d88fff ColorSync arm64  <5959a19f99dc3ed1b0553dc055c18347> /System/Library/PrivateFrameworks/ColorSync.framework/ColorSync
0x184d89000 - 0x184db2fff CoreVideo arm64  <740eb305ad133ba9ad42b2334b4c4ef5> /System/Library/Frameworks/CoreVideo.framework/CoreVideo
0x184db3000 - 0x184db4fff libCTGreenTeaLogger.dylib arm64  <63de7396e5733ef8a0707e336ea72fd7> /usr/lib/libCTGreenTeaLogger.dylib
0x184db5000 - 0x184f21fff CoreAudio arm64  <8c29fcd6f30b3943bf20b01aeb0e04f6> /System/Library/Frameworks/CoreAudio.framework/CoreAudio
0x184f22000 - 0x184f50fff CoreAnalytics arm64  <97087dc402a73b5d9d71d9e6e230991c> /System/Library/PrivateFrameworks/CoreAnalytics.framework/CoreAnalytics
0x184f51000 - 0x184f54fff UserFS arm64  <26dc70e76d613a75aecc6a3fb815199c> /System/Library/PrivateFrameworks/UserFS.framework/UserFS
0x184f55000 - 0x1850d1fff CoreMedia arm64  <002dc275201c3a4eac49cca5bbfbcbbc> /System/Library/Frameworks/CoreMedia.framework/CoreMedia
0x1850d2000 - 0x1850e4fff libprotobuf-lite.dylib arm64  <1a1686915f8b343ba80bea61f7bfb250> /usr/lib/libprotobuf-lite.dylib
0x1850e5000 - 0x185149fff libprotobuf.dylib arm64  <0f2b421fec773e7a8c4dc240454fd2bd> /usr/lib/libprotobuf.dylib
0x18514a000 - 0x18540dfff libAWDSupportFramework.dylib arm64  <1293c8fa59113426a524963ad2960534> /usr/lib/libAWDSupportFramework.dylib
0x18540e000 - 0x185457fff WirelessDiagnostics arm64  <e29e7932ab30323a8123b52cd1220792> /System/Library/PrivateFrameworks/WirelessDiagnostics.framework/WirelessDiagnostics
0x185458000 - 0x18550ffff VideoToolbox arm64  <1a06c4bc7dd533979bcc2b53b4c9d282> /System/Library/Frameworks/VideoToolbox.framework/VideoToolbox
0x185510000 - 0x185619fff libFontParser.dylib arm64  <4f1c4137cd9a327f9cfe6befb8772ecc> /System/Library/PrivateFrameworks/FontServices.framework/libFontParser.dylib
0x18561a000 - 0x18561bfff FontServices arm64  <f219f06c5d55331980dc38b5b3007a38> /System/Library/PrivateFrameworks/FontServices.framework/FontServices
0x18561c000 - 0x18576ffff CoreText arm64  <77db300ece0c3f60880c9c37d0328f09> /System/Library/Frameworks/CoreText.framework/CoreText
0x185770000 - 0x18577ffff IntlPreferences arm64  <d8d17e8a2b9237598b5b9b2d9bf25ee3> /System/Library/PrivateFrameworks/IntlPreferences.framework/IntlPreferences
0x185780000 - 0x185788fff RTCReporting arm64  <4a3fab43886f3e6a80eff6d701c81c42> /System/Library/PrivateFrameworks/RTCReporting.framework/RTCReporting
0x185789000 - 0x1857f9fff CoreBrightness arm64  <09c973cf66153394aafc1d30404b2124> /System/Library/PrivateFrameworks/CoreBrightness.framework/CoreBrightness
0x1857fa000 - 0x185804fff libAudioStatistics.dylib arm64  <c94b3206337b37e3a14f244078b7ebe5> /usr/lib/libAudioStatistics.dylib
0x185805000 - 0x185d3dfff AudioToolbox arm64  <b16fa0c577e33089afcc27ec669f486f> /System/Library/Frameworks/AudioToolbox.framework/AudioToolbox
0x185d3e000 - 0x185f71fff QuartzCore arm64  <3b0f2dc265b03c6badac432a3bd1a26f> /System/Library/Frameworks/QuartzCore.framework/QuartzCore
0x185f72000 - 0x185f7dfff MediaAccessibility arm64  <3bbdb8fbf36c387fb7ac14d5a0becfd4> /System/Library/Frameworks/MediaAccessibility.framework/MediaAccessibility
0x185f7e000 - 0x186070fff libiconv.2.dylib arm64  <a7f0f50a7a933ec18bd126fa5938b4a3> /usr/lib/libiconv.2.dylib
0x186071000 - 0x18608cfff NetworkStatistics arm64  <4bc8202c17113cbbbedec9d698607ad8> /System/Library/PrivateFrameworks/NetworkStatistics.framework/NetworkStatistics
0x18608d000 - 0x1860a8fff MPSCore arm64  <fdf474d325fb35dbb581c292a55c2a69> /System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSCore.framework/MPSCore
0x1860a9000 - 0x186111fff MPSImage arm64  <bb4eeae3c182348eac0c7afc6cb28ebf> /System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSImage.framework/MPSImage
0x186112000 - 0x186134fff MPSMatrix arm64  <51eed27dc958331185498c57d285488c> /System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSMatrix.framework/MPSMatrix
0x186135000 - 0x186143fff CoreAUC arm64  <2224d1a7332a3d3086784b512a37864c> /System/Library/PrivateFrameworks/CoreAUC.framework/CoreAUC
0x186144000 - 0x186799fff MediaToolbox arm64  <33dca775dcaa367ba2a05ad76239745c> /System/Library/Frameworks/MediaToolbox.framework/MediaToolbox
0x18679a000 - 0x1868c9fff MPSNeuralNetwork arm64  <88bcea2c366b31a68c58df71a7f334ef> /System/Library/Frameworks/MetalPerformanceShaders.framework/Frameworks/MPSNeuralNetwork.framework/MPSNeuralNetwork
0x1868ca000 - 0x1868cafff MetalPerformanceShaders arm64  <19616d7864ed39bd92fa2f834bea5e92> /System/Library/Frameworks/MetalPerformanceShaders.framework/MetalPerformanceShaders
0x1868cb000 - 0x186cf5fff FaceCore arm64  <5e413f9639833bd582d1626f1324d0bf> /System/Library/PrivateFrameworks/FaceCore.framework/FaceCore
0x186cf6000 - 0x186d03fff GraphVisualizer arm64  <8717060f6a11307eb90d4c68ab8026ba> /System/Library/PrivateFrameworks/GraphVisualizer.framework/GraphVisualizer
0x186d04000 - 0x186eabfff libFosl_dynamic.dylib arm64  <bb0a03649109390ba3128fc8f005a891> /usr/lib/libFosl_dynamic.dylib
0x186eac000 - 0x18710ffff CoreImage arm64  <f57ebcfb222c3ac29a30aff8f0a9eb68> /System/Library/Frameworks/CoreImage.framework/CoreImage
0x187110000 - 0x18730efff CoreMotion arm64  <47fb319b10c53669bcef50c4ee34d0c1> /System/Library/Frameworks/CoreMotion.framework/CoreMotion
0x18730f000 - 0x18733dfff CoreBluetooth arm64  <c1761f13e5ed392f96f649c2fa103c36> /System/Library/Frameworks/CoreBluetooth.framework/CoreBluetooth
0x18733e000 - 0x187360fff PlugInKit arm64  <650de2e4f728381d9c6bae39eb3e2768> /System/Library/PrivateFrameworks/PlugInKit.framework/PlugInKit
0x187361000 - 0x18758cfff Celestial arm64  <206bb9240a6c3dbab2fc3bb64d5db1fc> /System/Library/PrivateFrameworks/Celestial.framework/Celestial
0x18758d000 - 0x18760ffff Quagga arm64  <95fb120567723673a0c85b1b91f1a67a> /System/Library/PrivateFrameworks/Quagga.framework/Quagga
0x187610000 - 0x187706fff AVFAudio arm64  <ea5c1b49ecc73321b8c704da493a4150> /System/Library/Frameworks/AVFoundation.framework/Frameworks/AVFAudio.framework/AVFAudio
0x187707000 - 0x1878f8fff AVFoundation arm64  <6fa521ecbea43fb6888cdbf49ed19506> /System/Library/Frameworks/AVFoundation.framework/AVFoundation
0x1878f9000 - 0x18791bfff CacheDelete arm64  <10926c0dd8be35e08090aeae4b6aaabc> /System/Library/PrivateFrameworks/CacheDelete.framework/CacheDelete
0x18791c000 - 0x187941fff StreamingZip arm64  <a8037e11b0fb362caec892930fda6bfa> /System/Library/PrivateFrameworks/StreamingZip.framework/StreamingZip
0x187942000 - 0x187953fff CoreEmoji arm64  <6d18237f09d23ce6aa6abb287d7aa515> /System/Library/PrivateFrameworks/CoreEmoji.framework/CoreEmoji
0x187954000 - 0x1879a1fff CoreLocationProtobuf arm64  <aa410fa0891437519a2a7fec4e6c9649> /System/Library/PrivateFrameworks/CoreLocationProtobuf.framework/CoreLocationProtobuf
0x1879a2000 - 0x1879aafff SymptomDiagnosticReporter arm64  <32a292fd7bac35528f161a9c3d8e24e6> /System/Library/PrivateFrameworks/SymptomDiagnosticReporter.framework/SymptomDiagnosticReporter
0x1879ab000 - 0x1882b4fff GeoServices arm64  <49ecb05055933ff287615105a26c9497> /System/Library/PrivateFrameworks/GeoServices.framework/GeoServices
0x1882b5000 - 0x1882ccfff MobileAsset arm64  <744020a967d23c8682d6e472ad53481f> /System/Library/PrivateFrameworks/MobileAsset.framework/MobileAsset
0x1882cd000 - 0x18830dfff Lexicon arm64  <b510b95a2db637a28d561679f72ca592> /System/Library/PrivateFrameworks/Lexicon.framework/Lexicon
0x18830e000 - 0x18831efff libcmph.dylib arm64  <be5f1569ab5a3b86b461e82105c560aa> /usr/lib/libcmph.dylib
0x18831f000 - 0x188440fff LanguageModeling arm64  <b3d9ec93728b3e6a94dd30097702ccde> /System/Library/PrivateFrameworks/LanguageModeling.framework/LanguageModeling
0x188441000 - 0x188458fff libmarisa.dylib arm64  <2e2b0fba5ce534ddbc4ad00b4b1f528b> /usr/lib/libmarisa.dylib
0x188459000 - 0x1884f2fff CoreLocation arm64  <4864efb67a7438ff83857835185cd8c6> /System/Library/Frameworks/CoreLocation.framework/CoreLocation
0x1884f3000 - 0x1884f3fff PhoneNumbers arm64  <aee5ccde97963ce9adfda907463da0df> /System/Library/PrivateFrameworks/PhoneNumbers.framework/PhoneNumbers
0x1884f4000 - 0x1884fffff libChineseTokenizer.dylib arm64  <8fc360e06ecf39eebfe18fee3d065548> /usr/lib/libChineseTokenizer.dylib
0x188500000 - 0x1885acfff libmecab_em.dylib arm64  <32ab30df1b96345aadc220d9f48bdda8> /usr/lib/libmecab_em.dylib
0x1885ad000 - 0x1885aefff libThaiTokenizer.dylib arm64  <b6df9e5a19923bc386db3594db983449> /usr/lib/libThaiTokenizer.dylib
0x1885af000 - 0x1885b3fff libgermantok.dylib arm64  <2fd41d3c09223f1ebb2bab588c94081c> /usr/lib/libgermantok.dylib
0x1885b4000 - 0x18860bfff CoreNLP arm64  <6ee51de94ef53e0581d2e02a00bdaa96> /System/Library/PrivateFrameworks/CoreNLP.framework/CoreNLP
0x18860c000 - 0x1887ddfff MobileSpotlightIndex arm64  <0dbda49f46fa35a5afff44b2514db83c> /System/Library/PrivateFrameworks/MobileSpotlightIndex.framework/MobileSpotlightIndex
0x1887de000 - 0x18883ffff CoreSpotlight arm64  <b20d897415db34b3a5020f3ed90de711> /System/Library/Frameworks/CoreSpotlight.framework/CoreSpotlight
0x18884c000 - 0x1893adfff JavaScriptCore arm64  <eddcb7b4da7c3a48a21d36371dbde784> /System/Library/Frameworks/JavaScriptCore.framework/JavaScriptCore
0x1893ae000 - 0x1893b3fff libheimdal-asn1.dylib arm64  <e05c6a5c6e9c31b7b77de93bffa04ec6> /usr/lib/libheimdal-asn1.dylib
0x1893b4000 - 0x18942ffff libate.dylib arm64  <9b79be10c08736b397ef06920b5d9a22> /usr/lib/libate.dylib
0x189430000 - 0x1894e4fff TextureIO arm64  <b5852ba51db534d893d1f8b6bf5af3c5> /System/Library/PrivateFrameworks/TextureIO.framework/TextureIO
0x1894e5000 - 0x1895affff CoreUI arm64  <5b1aadadc936328db96ad35b5b301850> /System/Library/PrivateFrameworks/CoreUI.framework/CoreUI
0x1895b0000 - 0x1895b9fff MobileIcons arm64  <1f2e75af8930391396411577077f1680> /System/Library/PrivateFrameworks/MobileIcons.framework/MobileIcons
0x1895ba000 - 0x1895c8fff AppleFSCompression arm64  <0faf45b120053801bbaf97954d6e3dd4> /System/Library/PrivateFrameworks/AppleFSCompression.framework/AppleFSCompression
0x1895c9000 - 0x189621fff TextInput arm64  <3c0b74e0fbe43fe9abbeb20cd9336f2a> /System/Library/PrivateFrameworks/TextInput.framework/TextInput
0x189622000 - 0x18964afff libxslt.1.dylib arm64  <afd62d51467a31f086fd50ba6d522fa0> /usr/lib/libxslt.1.dylib
0x18964b000 - 0x18967ffff DataDetectorsCore arm64  <0a5df1c450143c448bca483b0442deaf> /System/Library/PrivateFrameworks/DataDetectorsCore.framework/DataDetectorsCore
0x189680000 - 0x189713fff FileProvider arm64  <23494a23c54d3372b651e89a5eab8c49> /System/Library/Frameworks/FileProvider.framework/FileProvider
0x1898de000 - 0x1898f2fff libAccessibility.dylib arm64  <c2ae8d98d410345a97add95c19a1d6d7> /usr/lib/libAccessibility.dylib
0x1898f3000 - 0x189d99fff libwebrtc.dylib arm64  <0b40d36332b73129a6374ed7435e676d> /System/Library/PrivateFrameworks/WebCore.framework/Frameworks/libwebrtc.dylib
0x189d9a000 - 0x189dfcfff ContactsFoundation arm64  <957d69d66b6e317d90ce669eda861706> /System/Library/PrivateFrameworks/ContactsFoundation.framework/ContactsFoundation
0x189dfd000 - 0x18b4c6fff WebCore arm64  <551de08a4164334ca2ce69b67d8631c7> /System/Library/PrivateFrameworks/WebCore.framework/WebCore
0x18b4c7000 - 0x18b64afff WebKitLegacy arm64  <dbf85ccf543435c9ba822b08ee7cb314> /System/Library/PrivateFrameworks/WebKitLegacy.framework/WebKitLegacy
0x18b64b000 - 0x18b673fff DataAccessExpress arm64  <8e3311f934e53459b1a50a56a8f072e1> /System/Library/PrivateFrameworks/DataAccessExpress.framework/DataAccessExpress
0x18b674000 - 0x18b70efff AddressBookLegacy arm64  <9f96f3b0e89b37b38c4a0ac13b9fed3d> /System/Library/PrivateFrameworks/AddressBookLegacy.framework/AddressBookLegacy
0x18b70f000 - 0x18b76afff ProtectedCloudStorage arm64  <97c44905d98f3aeda54d5e18852fdb1c> /System/Library/PrivateFrameworks/ProtectedCloudStorage.framework/ProtectedCloudStorage
0x18b76b000 - 0x18b797fff UserNotifications arm64  <af5da8910e8133b7af31685569872ba5> /System/Library/Frameworks/UserNotifications.framework/UserNotifications
0x18b798000 - 0x18b7a3fff AppleIDAuthSupport arm64  <9a58a7b3913a36e7b80931230c9adac1> /System/Library/PrivateFrameworks/AppleIDAuthSupport.framework/AppleIDAuthSupport
0x18b7a4000 - 0x18b7f4fff AuthKit arm64  <7b2eebc84315383e94b83f787ed9a111> /System/Library/PrivateFrameworks/AuthKit.framework/AuthKit
0x18b81f000 - 0x18b873fff DocumentManager arm64  <8263ec0a6c883222a26bc072300c77db> /System/Library/Frameworks/UIKit.framework/Frameworks/DocumentManager.framework/DocumentManager
0x18b874000 - 0x18c8f2fff UIKit arm64  <f8ce0f3965e430a483eb07f32b5ea991> /System/Library/Frameworks/UIKit.framework/UIKit
0x18c8f3000 - 0x18c905fff DocumentManagerCore arm64  <1b0d69ce2d613b8a867a77e9f1b33989> /System/Library/PrivateFrameworks/DocumentManagerCore.framework/DocumentManagerCore
0x18c906000 - 0x18c90afff HangTracer arm64  <03caf892e5c637ae91f8f122ccafcfe3> /System/Library/PrivateFrameworks/HangTracer.framework/HangTracer
0x18c90b000 - 0x18c95cfff PhysicsKit arm64  <1cb1907390353c898fffd99cd5610e81> /System/Library/PrivateFrameworks/PhysicsKit.framework/PhysicsKit
0x18c95d000 - 0x18c95ffff StudyLog arm64  <9b96f921e00c3c28923639f879fbea28> /System/Library/PrivateFrameworks/StudyLog.framework/StudyLog
0x18c960000 - 0x18ca3ffff UIFoundation arm64  <2431175d036e3f2d8cb0e7a6b0d1466f> /System/Library/PrivateFrameworks/UIFoundation.framework/UIFoundation
0x18ca40000 - 0x18cb5efff CloudKit arm64  <e857b65d67d33f92a409ba1f743a399e> /System/Library/Frameworks/CloudKit.framework/CloudKit
0x18cb5f000 - 0x18cb5ffff IntentsFoundation arm64  <a2fbab6d9cef39b4801fc0b07b0ee342> /System/Library/PrivateFrameworks/IntentsFoundation.framework/IntentsFoundation
0x18cb60000 - 0x18cc7cfff Network arm64  <ad0700a8317d378c92c0b3d6b8bd3bd4> /System/Library/PrivateFrameworks/Network.framework/Network
0x18cc7d000 - 0x18ce84fff Intents arm64  <10d12a311d1932ee8aca5151e1b51d88> /System/Library/Frameworks/Intents.framework/Intents
0x18ce85000 - 0x18ce9ffff libresolv.9.dylib arm64  <7c4f57d578193d9fa2b41e55d2df2db2> /usr/lib/libresolv.9.dylib
0x18cea0000 - 0x18cea2fff CoreDuetDebugLogging arm64  <54c6a0c800a536efb318b67f910d62a1> /System/Library/PrivateFrameworks/CoreDuetDebugLogging.framework/CoreDuetDebugLogging
0x18cea3000 - 0x18ced8fff libtidy.A.dylib arm64  <cb3e6b9eb9e132d68a4ff455ab5eb4f7> /usr/lib/libtidy.A.dylib
0x18ced9000 - 0x18d008fff CoreDuet arm64  <9b8c0d8a045c39808e729680f7a02acf> /System/Library/PrivateFrameworks/CoreDuet.framework/CoreDuet
0x18d009000 - 0x18d028fff CoreDuetContext arm64  <c702b6b7aba33523bda6faad8361f38c> /System/Library/PrivateFrameworks/CoreDuetContext.framework/CoreDuetContext
0x18d029000 - 0x18d03dfff CoreDuetDaemonProtocol arm64  <40eb67e397ef314886482b11e8022677> /System/Library/PrivateFrameworks/CoreDuetDaemonProtocol.framework/CoreDuetDaemonProtocol
0x18d03e000 - 0x18d0a9fff IMFoundation arm64  <6b4b6b92108e33baa7f8381d42cccfec> /System/Library/PrivateFrameworks/IMFoundation.framework/IMFoundation
0x18d0aa000 - 0x18d0d8fff vCard arm64  <3752e374279634088834401ad0220ce8> /System/Library/PrivateFrameworks/vCard.framework/vCard
0x18d0d9000 - 0x18d1e6fff Contacts arm64  <1591a177f0c33f73ad8cc2de14c743ff> /System/Library/Frameworks/Contacts.framework/Contacts
0x18d1e7000 - 0x18d1e8fff DiagnosticLogCollection arm64  <cc7806b2a4ad32bfaab285d7323ba272> /System/Library/PrivateFrameworks/DiagnosticLogCollection.framework/DiagnosticLogCollection
0x18d1e9000 - 0x18d1eafff Marco arm64  <865c2a3744c13039941e7f92aaf9bcaf> /System/Library/PrivateFrameworks/Marco.framework/Marco
0x18d1eb000 - 0x18d1f5fff MessageProtection arm64  <6dd7d2b068083337830d3fac1c9cef2b> /System/Library/PrivateFrameworks/MessageProtection.framework/MessageProtection
0x18d1f6000 - 0x18d504fff StoreServices arm64  <fb60d94f6f79343ea2931e936b6de0bc> /System/Library/PrivateFrameworks/StoreServices.framework/StoreServices
0x18d505000 - 0x18d51cfff Engram arm64  <fceb747ff3b531f7b4027a12656fdcca> /System/Library/PrivateFrameworks/Engram.framework/Engram
0x18d51d000 - 0x18d60dfff IDSFoundation arm64  <08d21d4abe023b57bc062df7b9f71f1b> /System/Library/PrivateFrameworks/IDSFoundation.framework/IDSFoundation
0x18d60e000 - 0x18d619fff CaptiveNetwork arm64  <b7526b28ec6b3a089803ed3aee798ca2> /System/Library/PrivateFrameworks/CaptiveNetwork.framework/CaptiveNetwork
0x18d61a000 - 0x18d648fff EAP8021X arm64  <ee33103cb73d375fac78cab0e9a64be2> /System/Library/PrivateFrameworks/EAP8021X.framework/EAP8021X
0x18d649000 - 0x18d683fff MobileWiFi arm64  <82fb4980e6053e0badca33aa5dde8957> /System/Library/PrivateFrameworks/MobileWiFi.framework/MobileWiFi
0x18d684000 - 0x18d686fff OAuth arm64  <5625c4fc795136469ed6983973f33dd5> /System/Library/PrivateFrameworks/OAuth.framework/OAuth
0x18d687000 - 0x18d689fff CommonAuth arm64  <8455c7ba72b938899f6f32067e1de0d9> /System/Library/PrivateFrameworks/CommonAuth.framework/CommonAuth
0x18d68a000 - 0x18d6f8fff Heimdal arm64  <d1aba4a16eee3cee9133bae84f8f3159> /System/Library/PrivateFrameworks/Heimdal.framework/Heimdal
0x18d6f9000 - 0x18d722fff GSS arm64  <3595359311433789b5dd92832540f3aa> /System/Library/Frameworks/GSS.framework/GSS
0x18d723000 - 0x18d73afff ApplePushService arm64  <613a5a854a4c3c87bb81f3177f4b0865> /System/Library/PrivateFrameworks/ApplePushService.framework/ApplePushService
0x18d73b000 - 0x18d7d2fff AccountsDaemon arm64  <1d435ebf3288320b865f40b605b5408f> /System/Library/PrivateFrameworks/AccountsDaemon.framework/AccountsDaemon
0x18d7d3000 - 0x18d7f7fff AppleIDSSOAuthentication arm64  <816bd8130fca33b7a218820dd1d2679b> /System/Library/PrivateFrameworks/AppleIDSSOAuthentication.framework/AppleIDSSOAuthentication
0x18d7f8000 - 0x18d870fff AppleAccount arm64  <7eec817466d93d07bfac97e7cedb4d60> /System/Library/PrivateFrameworks/AppleAccount.framework/AppleAccount
0x18d871000 - 0x18d9a7fff CoreUtils arm64  <6170a002e2203fc8a39b6607d40ede58> /System/Library/PrivateFrameworks/CoreUtils.framework/CoreUtils
0x18d9a8000 - 0x18dabefff IDS arm64  <16a330e0018b33738d123c494e800dbc> /System/Library/PrivateFrameworks/IDS.framework/IDS
0x18dabf000 - 0x18dae2fff MediaServices arm64  <8b5314e242a83855b004ab611ea54e3c> /System/Library/PrivateFrameworks/MediaServices.framework/MediaServices
0x18dae3000 - 0x18dc9afff MediaRemote arm64  <217cb8eb6a7d33b5a9e1032e5488ffd3> /System/Library/PrivateFrameworks/MediaRemote.framework/MediaRemote
0x18dc9b000 - 0x18dcb3fff UserManagement arm64  <64bd9de97b9f359594a20aabe0068e3e> /System/Library/PrivateFrameworks/UserManagement.framework/UserManagement
0x18dcb4000 - 0x18dcc3fff MobileBluetooth arm64  <d5c5f24eb2183443b785505f90797845> /System/Library/PrivateFrameworks/MobileBluetooth.framework/MobileBluetooth
0x18dcc4000 - 0x18dcf4fff Bom arm64  <5ae2739d04103a60860a53eb4f696782> /System/Library/PrivateFrameworks/Bom.framework/Bom
0x18dcf5000 - 0x18dcf9fff CommunicationsFilter arm64  <a31562e7c15830f3a058cac38e6e1181> /System/Library/PrivateFrameworks/CommunicationsFilter.framework/CommunicationsFilter
0x18dcfa000 - 0x18dd1ffff FTAWD arm64  <4eb35e0a28ae30c5bdffec2ff4b899ab> /System/Library/PrivateFrameworks/FTAWD.framework/FTAWD
0x18dd20000 - 0x18dd73fff FTServices arm64  <ee7a0745bd6f3afebb004f6e31abf084> /System/Library/PrivateFrameworks/FTServices.framework/FTServices
0x18dd74000 - 0x18ddc5fff WirelessProximity arm64  <7799210b944235189b44234a063a8be8> /System/Library/PrivateFrameworks/WirelessProximity.framework/WirelessProximity
0x18ddc6000 - 0x18ddd0fff ProactiveEventTracker arm64  <2e40ee934a5e3022a56ff8f8c4228860> /System/Library/PrivateFrameworks/ProactiveEventTracker.framework/ProactiveEventTracker
0x18ddd1000 - 0x18de1ffff ChunkingLibrary arm64  <7672d15e44c93f5f8a3d56488773d22a> /System/Library/PrivateFrameworks/ChunkingLibrary.framework/ChunkingLibrary
0x18de20000 - 0x18de2cfff libnetworkextension.dylib arm64  <272813d05f9430979f4ee0ee6384bf61> /usr/lib/libnetworkextension.dylib
0x18de2d000 - 0x18de51fff AddressBook arm64  <60347d6b0b96393796c3cea7c779a4b2> /System/Library/Frameworks/AddressBook.framework/AddressBook
0x18de52000 - 0x18ec53fff ModelIO arm64  <1c48931b7535303c95f55caedee9e32d> /System/Library/Frameworks/ModelIO.framework/ModelIO
0x18ec54000 - 0x18ede8fff NetworkExtension arm64  <e84f039200df36debb7cb251f82a69b9> /System/Library/Frameworks/NetworkExtension.framework/NetworkExtension
0x18ede9000 - 0x18f235fff SiriTTS arm64  <ca5f1c3d0d893c05bc0790509b89a26d> /System/Library/PrivateFrameworks/SiriTTS.framework/SiriTTS
0x18f236000 - 0x18f290fff SAObjects arm64  <23ce3832c03f34f19accad50e0a0fb7e> /System/Library/PrivateFrameworks/SAObjects.framework/SAObjects
0x18f291000 - 0x18f2cffff VoiceServices arm64  <a17ca03e5e39393aaec10950b9ad8e55> /System/Library/PrivateFrameworks/VoiceServices.framework/VoiceServices
0x18f2d0000 - 0x18f300fff GLKit arm64  <c38901bef3573ed896eb6c7dd3ac6364> /System/Library/Frameworks/GLKit.framework/GLKit
0x18f301000 - 0x18f3e6fff AssistantServices arm64  <056177456cc934dd9c4024dfaab0f6bf> /System/Library/PrivateFrameworks/AssistantServices.framework/AssistantServices
0x18f3e7000 - 0x18f405fff AssetCacheServices arm64  <14148e4386e73186a62a37a4c1436605> /System/Library/PrivateFrameworks/AssetCacheServices.framework/AssetCacheServices
0x18f406000 - 0x18f4c0fff NetworkServiceProxy arm64  <3542ac752ae93bdf8b052b1c864c42a6> /System/Library/PrivateFrameworks/NetworkServiceProxy.framework/NetworkServiceProxy
0x18f4c1000 - 0x18f5b2fff MMCS arm64  <8e94bb24e1ad37b39c3895c32813348b> /System/Library/PrivateFrameworks/MMCS.framework/MMCS
0x18f5b3000 - 0x18f5bffff BluetoothManager arm64  <15402838a4713448b995f158f10a49f7> /System/Library/PrivateFrameworks/BluetoothManager.framework/BluetoothManager
0x18f5c0000 - 0x18f630fff CoreDAV arm64  <378358a925753c8ca1d28ab5335c7849> /System/Library/PrivateFrameworks/CoreDAV.framework/CoreDAV
0x18f631000 - 0x18f666fff iCalendar arm64  <6cd4994cd6ac31dc81707f4cbba4dae3> /System/Library/PrivateFrameworks/iCalendar.framework/iCalendar
0x18f667000 - 0x18f674fff PersonaKit arm64  <dadf0bdaa9bf303baa9e1046da37fd9f> /System/Library/PrivateFrameworks/PersonaKit.framework/PersonaKit
0x18f675000 - 0x18f6cffff CalendarFoundation arm64  <84c86b1af6263b6a82c1fa6c5c94e590> /System/Library/PrivateFrameworks/CalendarFoundation.framework/CalendarFoundation
0x18f6d0000 - 0x18f6fdfff PhotosFormats arm64  <60c666c2594931379d5aebc0b847bfb7> /System/Library/PrivateFrameworks/PhotosFormats.framework/PhotosFormats
0x18f6fe000 - 0x18f79bfff CalendarDatabase arm64  <230ebaa77aa93deeba0d588b35259b10> /System/Library/PrivateFrameworks/CalendarDatabase.framework/CalendarDatabase
0x18f79c000 - 0x18f7ecfff CalendarDaemon arm64  <ee7218ed873c3c2588e1c51768855adb> /System/Library/PrivateFrameworks/CalendarDaemon.framework/CalendarDaemon
0x18f7ed000 - 0x18f906fff CloudPhotoLibrary arm64  <b1025b86e3d831c6836c5cb3698ca289> /System/Library/PrivateFrameworks/CloudPhotoLibrary.framework/CloudPhotoLibrary
0x18f907000 - 0x18f9e9fff EventKit arm64  <6ea4d3e7617b392fbf16b4a4ba99ac72> /System/Library/Frameworks/EventKit.framework/EventKit
0x18f9ea000 - 0x18fa14fff AssetsLibraryServices arm64  <af4dd8bf359a3ab8b02ebe8c418947c9> /System/Library/PrivateFrameworks/AssetsLibraryServices.framework/AssetsLibraryServices
0x18fa15000 - 0x18fa49fff ACTFramework arm64  <977f6698f49038b79fff67c783477b8e> /System/Library/PrivateFrameworks/ACTFramework.framework/ACTFramework
0x18fa4a000 - 0x18fa6afff DCIMServices arm64  <1b541e7837803064af0e9f011991282f> /System/Library/PrivateFrameworks/DCIMServices.framework/DCIMServices
0x18fa6b000 - 0x18fba6fff CoreMediaStream arm64  <193d543866c536cda65047f741c3ed74> /System/Library/PrivateFrameworks/CoreMediaStream.framework/CoreMediaStream
0x18fba7000 - 0x18fbaefff XPCKit arm64  <f4572f263382392fa9cc008fb5c0302e> /System/Library/PrivateFrameworks/XPCKit.framework/XPCKit
0x18fbaf000 - 0x18fc93fff CameraKit arm64  <bed0c4f7ae1c3fe2a3d2868721ae9f8c> /System/Library/PrivateFrameworks/CameraKit.framework/CameraKit
0x18fc94000 - 0x18fcacfff CloudPhotoServices arm64  <0d5f9ccc560d3d7481ba785f975989c1> /System/Library/PrivateFrameworks/CloudPhotoServices.framework/CloudPhotoServices
0x18fcad000 - 0x18fcb8fff CoreRecents arm64  <e53eb9b80a313789a220f1ae5183f9b8> /System/Library/PrivateFrameworks/CoreRecents.framework/CoreRecents
0x18fcb9000 - 0x18fcd7fff MediaStream arm64  <b7408d4da0f838d98408a752c56eeeeb> /System/Library/PrivateFrameworks/MediaStream.framework/MediaStream
0x18fcd8000 - 0x1900fdfff PhotoLibraryServices arm64  <4143d281e62431ee9dfa0c7652ccb0ab> /System/Library/PrivateFrameworks/PhotoLibraryServices.framework/PhotoLibraryServices
0x1900fe000 - 0x190133fff PrototypeTools arm64  <3e6cb4b7b5963c55ac06b1ab7317c69c> /System/Library/PrivateFrameworks/PrototypeTools.framework/PrototypeTools
0x190134000 - 0x1901bdfff CoreSymbolication arm64  <bec7481bde963b16bcab4fc8d2bffbc4> /System/Library/PrivateFrameworks/CoreSymbolication.framework/CoreSymbolication
0x1901be000 - 0x1902eafff SearchFoundation arm64  <541bd939dc853e898a9c279dc9991c87> /System/Library/PrivateFrameworks/SearchFoundation.framework/SearchFoundation
0x1902f2000 - 0x1903a5fff iTunesStore arm64  <b0a79cc44fb637528b9abc03a6f4db92> /System/Library/PrivateFrameworks/iTunesStore.framework/iTunesStore
0x19051c000 - 0x190523fff CoreTime arm64  <a968eb348dc33f83acef60fd12446ceb> /System/Library/PrivateFrameworks/CoreTime.framework/CoreTime
0x190524000 - 0x19068ffff CVML arm64  <3789e7e736b83ea7ac7195c1a042cf6a> /System/Library/PrivateFrameworks/CVML.framework/CVML
0x190690000 - 0x1906ddfff CoreAppleCVA arm64  <305df7eb28b5308bac9815923f4985b1> /System/Library/PrivateFrameworks/CoreAppleCVA.framework/CoreAppleCVA
0x1906de000 - 0x190718fff DifferentialPrivacy arm64  <e36140a770b836e2b3ec41dfab5dc183> /System/Library/PrivateFrameworks/DifferentialPrivacy.framework/DifferentialPrivacy
0x190725000 - 0x19089ffff AppleCVA arm64  <41ef9c9831013bcf86df23db6d3039b0> /System/Library/PrivateFrameworks/AppleCVA.framework/AppleCVA
0x1908a0000 - 0x190930fff Montreal arm64  <c9bf79cd70d33c8fabdeb8dd6d62bf70> /System/Library/PrivateFrameworks/Montreal.framework/Montreal
0x190931000 - 0x190b53fff Espresso arm64  <f0628fb67a37313ea51f514fd3230d76> /System/Library/PrivateFrameworks/Espresso.framework/Espresso
0x190b54000 - 0x190b57fff MobileSystemServices arm64  <e4fd6cedc6103da6b2d05b04e45a5f3d> /System/Library/PrivateFrameworks/MobileSystemServices.framework/MobileSystemServices
0x190b58000 - 0x190ca9fff Photos arm64  <35be6d570edd3d5e8ac8a6b145236685> /System/Library/Frameworks/Photos.framework/Photos
0x190caa000 - 0x190e75fff CoreML arm64  <80ba174d6a153c34a556a7b287344232> /System/Library/Frameworks/CoreML.framework/CoreML
0x190e76000 - 0x190e7afff CoreOptimization arm64  <80f64c09a26b325a9a0a981a23671f2d> /System/Library/PrivateFrameworks/CoreOptimization.framework/CoreOptimization
0x190e7b000 - 0x190ec6fff SafariCore arm64  <08c7ffc274f73d1fbdaa1ec760ea00f2> /System/Library/PrivateFrameworks/SafariCore.framework/SafariCore
0x190ec7000 - 0x190f24fff CorePrediction arm64  <0f9dabcb82053af697ab69533e838fa2> /System/Library/PrivateFrameworks/CorePrediction.framework/CorePrediction
0x190f25000 - 0x191021fff Navigation arm64  <7a9cb461bf02381fa026d736145412c7> /System/Library/PrivateFrameworks/Navigation.framework/Navigation
0x191022000 - 0x191039fff ContactsDonation arm64  <f48974fa738c32a492a5d587d4714378> /System/Library/PrivateFrameworks/ContactsDonation.framework/ContactsDonation
0x19103a000 - 0x191066fff Futhark arm64  <bf235b86b8b73d409cc7fd74592117d8> /System/Library/PrivateFrameworks/Futhark.framework/Futhark
0x191067000 - 0x1910aafff NanoRegistry arm64  <89cd9570595332428856ee28182baabd> /System/Library/PrivateFrameworks/NanoRegistry.framework/NanoRegistry
0x1910fe000 - 0x19110ffff BaseBoardUI arm64  <270d2f006ee23ab581f0b552d45a75a0> /System/Library/PrivateFrameworks/BaseBoardUI.framework/BaseBoardUI
0x191110000 - 0x191167fff ContactsUICore arm64  <76397a63e83735faadde51b9e0a5910e> /System/Library/PrivateFrameworks/ContactsUICore.framework/ContactsUICore
0x191168000 - 0x1912cbfff ContactsUI arm64  <6dc7d0bd0ca53addb3b9752eb80f8fe7> /System/Library/Frameworks/ContactsUI.framework/ContactsUI
0x1912cc000 - 0x1913a7fff CorePDF arm64  <094152970a1d3795bea2193509c9aa7c> /System/Library/PrivateFrameworks/CorePDF.framework/CorePDF
0x1913a8000 - 0x191609fff Vision arm64  <7858f139035533e88f8ece2df4e9779b> /System/Library/Frameworks/Vision.framework/Vision
0x19160a000 - 0x191a67fff WebKit arm64  <2d2db7296daf3cde851738572903eb19> /System/Library/Frameworks/WebKit.framework/WebKit
0x191b1f000 - 0x191b24fff ConstantClasses arm64  <73d3d9dc12313ec89aa75cc4636d65a5> /System/Library/PrivateFrameworks/ConstantClasses.framework/ConstantClasses
0x191b25000 - 0x191b2dfff CertUI arm64  <ebd5a002bf403d0da06a06a3d00237d6> /System/Library/PrivateFrameworks/CertUI.framework/CertUI
0x191c14000 - 0x191cb1fff MediaPlatform arm64  <00f9533651b934eb911938d4d5d9a6ae> /System/Library/PrivateFrameworks/MediaPlatform.framework/MediaPlatform
0x191cb2000 - 0x191d1bfff WebBookmarks arm64  <fa5ebc3f5b9231aab1d322feea0d8357> /System/Library/PrivateFrameworks/WebBookmarks.framework/WebBookmarks
0x191d1c000 - 0x191d23fff DAAPKit arm64  <f32c6621821a318fa0749e99a652abca> /System/Library/PrivateFrameworks/DAAPKit.framework/DAAPKit
0x191e16000 - 0x192138fff MediaLibraryCore arm64  <0c1da3ba61bf3cee99da5119a81a833d> /System/Library/PrivateFrameworks/MediaLibraryCore.framework/MediaLibraryCore
0x192139000 - 0x192139fff AdSupport arm64  <1075f932c9433a9b9611b7e9683220e4> /System/Library/Frameworks/AdSupport.framework/AdSupport
0x19213a000 - 0x1923c3fff MusicLibrary arm64  <3c170b8195fd31b89fd14328e3641f08> /System/Library/PrivateFrameworks/MusicLibrary.framework/MusicLibrary
0x1923c4000 - 0x192a97fff VectorKit arm64  <1985393e1fcb318e88282ecd3161d221> /System/Library/PrivateFrameworks/VectorKit.framework/VectorKit
0x192a98000 - 0x192cd4fff MapKit arm64  <acd4316f75613a13ba1c63b7d5725316> /System/Library/Frameworks/MapKit.framework/MapKit
0x192cd5000 - 0x192e65fff iTunesCloud arm64  <34be1b618d0930ba8be2d70e6682af27> /System/Library/PrivateFrameworks/iTunesCloud.framework/iTunesCloud
0x192e66000 - 0x192f0bfff HomeSharing arm64  <c8dae9643d403eac91d3f4a0217cfde7> /System/Library/PrivateFrameworks/HomeSharing.framework/HomeSharing
0x192f0c000 - 0x192f7ffff WebInspector arm64  <e3c54daa93a7394eb3c3ea26a8d67f12> /System/Library/PrivateFrameworks/WebInspector.framework/WebInspector
0x192f80000 - 0x193077fff ITMLKit arm64  <53d9390f0f0439998075a7dd215a45df> /System/Library/PrivateFrameworks/ITMLKit.framework/ITMLKit
0x193078000 - 0x193087fff NanoPreferencesSync arm64  <293e8eb9c5843f8db0e17b6076bce896> /System/Library/PrivateFrameworks/NanoPreferencesSync.framework/NanoPreferencesSync
0x193088000 - 0x1934e8fff MediaPlayer arm64  <531f64e936f53790b1a69ad2c5804e89> /System/Library/Frameworks/MediaPlayer.framework/MediaPlayer
0x1934e9000 - 0x19350dfff MobileInstallation arm64  <b4bbd3b88c6135e08bd37be4f3d3a627> /System/Library/PrivateFrameworks/MobileInstallation.framework/MobileInstallation
0x19350e000 - 0x193515fff EmailAddressing arm64  <21b9533aaad03cb692c2f6057ef2d0df> /System/Library/PrivateFrameworks/EmailAddressing.framework/EmailAddressing
0x193516000 - 0x193517fff MessageSupport arm64  <1d70381bc2ec3fa89552a521bf5d6005> /System/Library/PrivateFrameworks/MessageSupport.framework/MessageSupport
0x19351b000 - 0x193575fff MIME arm64  <3097f98ea1243d969095a9d3fa48a78f> /System/Library/PrivateFrameworks/MIME.framework/MIME
0x1935a8000 - 0x1935dffff Notes arm64  <c676912c88093465b5c29c752335d8b8> /System/Library/PrivateFrameworks/Notes.framework/Notes
0x193692000 - 0x1936ccfff CalendarUIKit arm64  <6e6df41823013cf2a4bc8c7fb78bcb1e> /System/Library/PrivateFrameworks/CalendarUIKit.framework/CalendarUIKit
0x1936e5000 - 0x193740fff DataAccess arm64  <bdcc0c5677e3325197678bf4e0fff407> /System/Library/PrivateFrameworks/DataAccess.framework/DataAccess
0x193741000 - 0x193754fff AssetsLibrary arm64  <e200a54807d132cb928829063baebe19> /System/Library/Frameworks/AssetsLibrary.framework/AssetsLibrary
0x193755000 - 0x193931fff EventKitUI arm64  <13b4e76e2f4431beaeebb08751688ad1> /System/Library/Frameworks/EventKitUI.framework/EventKitUI
0x193a23000 - 0x193ac3fff Social arm64  <7f23e436784433e89e2eeeb3e9f77bba> /System/Library/Frameworks/Social.framework/Social
0x193ad8000 - 0x193b3dfff RemoteUI arm64  <8a58c4ff4cdf3e55becd531636c82a52> /System/Library/PrivateFrameworks/RemoteUI.framework/RemoteUI
0x193b55000 - 0x193b6bfff CoreFollowUp arm64  <b52808572bf03ac4a1cd47161bf131cb> /System/Library/PrivateFrameworks/CoreFollowUp.framework/CoreFollowUp
0x193bdc000 - 0x193becfff MailServices arm64  <514704b94a2a38c0a6f06e6cf8ab8cdb> /System/Library/PrivateFrameworks/MailServices.framework/MailServices
0x193bed000 - 0x193c7ffff CoreRecognition arm64  <8e71ab6e2dbf3debbb0a68d66c3c4c4e> /System/Library/PrivateFrameworks/CoreRecognition.framework/CoreRecognition
0x193c80000 - 0x193ca0fff MailSupport arm64  <e6f35403fb2a35afbb7e2fb1f7311fef> /System/Library/PrivateFrameworks/MailSupport.framework/MailSupport
0x193ca1000 - 0x193df0fff Message arm64  <2e3abb3301863a819f15ddc98de74833> /System/Library/PrivateFrameworks/Message.framework/Message
0x1940b2000 - 0x1940e1fff AirTraffic arm64  <0af9202734ee3368aed0bd01338c729b> /System/Library/PrivateFrameworks/AirTraffic.framework/AirTraffic
0x1940e2000 - 0x194113fff SharedUtils arm64  <d63aa21fc4d633bcb1c39f3f13b4c75e> /System/Library/Frameworks/LocalAuthentication.framework/Support/SharedUtils.framework/SharedUtils
0x194114000 - 0x19414efff ContactsAutocomplete arm64  <add0707df68830ca84b4b0c48e9404d4> /System/Library/PrivateFrameworks/ContactsAutocomplete.framework/ContactsAutocomplete
0x194219000 - 0x194249fff Pegasus arm64  <75f25085f15b30739b75679e741b1bd8> /System/Library/PrivateFrameworks/Pegasus.framework/Pegasus
0x19424a000 - 0x1942d6fff AVKit arm64  <cdf40b3645dc34ff8cf779571cdf411f> /System/Library/Frameworks/AVKit.framework/AVKit
0x1942d7000 - 0x194300fff AuthKitUI arm64  <285adaeb4db83fe9a7e4c0df2ee463d0> /System/Library/PrivateFrameworks/AuthKitUI.framework/AuthKitUI
0x194301000 - 0x194304fff FTClientServices arm64  <ca8837cec1ae32368074a4f49e2521b8> /System/Library/PrivateFrameworks/FTClientServices.framework/FTClientServices
0x194309000 - 0x194309fff MobileObliteration arm64  <a06b58dfe47e35ecb60f7f828a2f310c> /System/Library/PrivateFrameworks/MobileObliteration.framework/MobileObliteration
0x19430e000 - 0x1944e5fff HealthKit arm64  <6a6fcdff7aff3f38bf1c9eed60d32662> /System/Library/Frameworks/HealthKit.framework/HealthKit
0x1944e6000 - 0x1944fcfff LocalAuthentication arm64  <9feebaa2de7630ba8f248806e30ccdae> /System/Library/Frameworks/LocalAuthentication.framework/LocalAuthentication
0x194500000 - 0x1945a6fff SpringBoardFoundation arm64  <eb7be49ada6a3a939201d41774753c38> /System/Library/PrivateFrameworks/SpringBoardFoundation.framework/SpringBoardFoundation
0x19487f000 - 0x19488cfff SetupAssistantSupport arm64  <e064b303a79336968e6d35634a102dc5> /System/Library/PrivateFrameworks/SetupAssistantSupport.framework/SetupAssistantSupport
0x19488d000 - 0x1948b5fff SetupAssistant arm64  <334293120d713f3b8c6ce065e63864e0> /System/Library/PrivateFrameworks/SetupAssistant.framework/SetupAssistant
0x1948fc000 - 0x1948fffff HSAAuthentication arm64  <d241287073193410ac6dcce54295b23b> /System/Library/PrivateFrameworks/HSAAuthentication.framework/HSAAuthentication
0x194900000 - 0x194909fff MobileStorage arm64  <785f1ca8a50235daa245ad83d62033a1> /System/Library/PrivateFrameworks/MobileStorage.framework/MobileStorage
0x19490a000 - 0x19494cfff ContentIndex arm64  <f9bbc0e903603352b5ce41d8ad7e9803> /System/Library/PrivateFrameworks/ContentIndex.framework/ContentIndex
0x19494d000 - 0x194c4bfff ImageCapture arm64  <b4261a9fc7e9362b986e7d3a981f4b0a> /System/Library/PrivateFrameworks/ImageCapture.framework/ImageCapture
0x194e1d000 - 0x194e33fff iPhotoMigrationSupport arm64  <c8fcd42decb9324db4d19d8ec606f8c3> /System/Library/PrivateFrameworks/iPhotoMigrationSupport.framework/iPhotoMigrationSupport
0x194e34000 - 0x194e45fff DiagnosticExtensions arm64  <3ed45ebdf0183644ae641c2b23b56ade> /System/Library/PrivateFrameworks/DiagnosticExtensions.framework/DiagnosticExtensions
0x19515c000 - 0x1951f2fff PhotoLibrary arm64  <586bbea8b5ed3d1985c209191fc6f3ac> /System/Library/PrivateFrameworks/PhotoLibrary.framework/PhotoLibrary
0x1951f3000 - 0x19553ffff PhotosUICore arm64  <73ee98a4a8f83e69a91a8d64b3205dc2> /System/Library/PrivateFrameworks/PhotosUICore.framework/PhotosUICore
0x195590000 - 0x1955f9fff IMSharedUtilities arm64  <b93c81133d9a32c692a929a544e010fc> /System/Library/PrivateFrameworks/IMSharedUtilities.framework/IMSharedUtilities
0x19561a000 - 0x1956a4fff PhotoEditSupport arm64  <c1bf5560388d3c499a410c44099d8993> /System/Library/PrivateFrameworks/PhotoEditSupport.framework/PhotoEditSupport
0x1956a5000 - 0x1956b8fff SiriTasks arm64  <fe2dab8a3c633400825b9e1cfd1c1e0e> /System/Library/PrivateFrameworks/SiriTasks.framework/SiriTasks
0x1956b9000 - 0x195ad2fff PhotosUI arm64  <9c917527f9b33e9f8bef4e85111e706e> /System/Library/Frameworks/PhotosUI.framework/PhotosUI
0x195bdc000 - 0x195c09fff StoreKit arm64  <b598ba07b95d3376bc3485cf69864eb4> /System/Library/Frameworks/StoreKit.framework/StoreKit
0x195c6d000 - 0x195c88fff EmojiFoundation arm64  <86e9db816e963a5398393175b63f5258> /System/Library/PrivateFrameworks/EmojiFoundation.framework/EmojiFoundation
0x195d9d000 - 0x195db7fff MetalKit arm64  <c2651a5f6c9c39838ccd013c63872dcc> /System/Library/Frameworks/MetalKit.framework/MetalKit
0x195dda000 - 0x196219fff SceneKit arm64  <50686d9209723ff997c2a46c3608325c> /System/Library/Frameworks/SceneKit.framework/SceneKit
0x196446000 - 0x19644efff AddressBookUI arm64  <44ad3bf7d19e33cd92bcf78edcb12026> /System/Library/Frameworks/AddressBookUI.framework/AddressBookUI
0x196d6b000 - 0x196db1fff Pasteboard arm64  <e227d2da53733637af723a8e41a8c5c6> /System/Library/PrivateFrameworks/Pasteboard.framework/Pasteboard
0x196e05000 - 0x196e17fff MobileDeviceLink arm64  <9ffcaac5cb483f4fbf48e5184b54b200> /System/Library/PrivateFrameworks/MobileDeviceLink.framework/MobileDeviceLink
0x196f7f000 - 0x196fc6fff MobileBackup arm64  <7b50b622105e3ba89d186a99c83104ee> /System/Library/PrivateFrameworks/MobileBackup.framework/MobileBackup
0x19713f000 - 0x19717efff AppStoreDaemon arm64  <39b136b7ecef3246bcb337b86dac86fc> /System/Library/PrivateFrameworks/AppStoreDaemon.framework/AppStoreDaemon
0x1972f0000 - 0x1974c5fff iTunesStoreUI arm64  <3e072bac11af3f459e7b0d0d1a705695> /System/Library/PrivateFrameworks/iTunesStoreUI.framework/iTunesStoreUI
0x1974c6000 - 0x1975c0fff MessageUI arm64  <e1158464edef334faa01c49a777ff494> /System/Library/Frameworks/MessageUI.framework/MessageUI
0x1975de000 - 0x19769dfff Radio arm64  <2f8f966c88e434e7a505e9b60d871202> /System/Library/PrivateFrameworks/Radio.framework/Radio
0x1977d2000 - 0x197800fff BookLibrary arm64  <a443d6cedeef361791ba808fa7871896> /System/Library/PrivateFrameworks/BookLibrary.framework/BookLibrary
0x197801000 - 0x1978f5fff MediaPlaybackCore arm64  <fffafdb6ca823c93a44a5d2848321f76> /System/Library/PrivateFrameworks/MediaPlaybackCore.framework/MediaPlaybackCore
0x197ab2000 - 0x197af8fff MPUFoundation arm64  <8ab2f93015193bfc9a9b003971c9f936> /System/Library/PrivateFrameworks/MPUFoundation.framework/MPUFoundation
0x197af9000 - 0x197f4afff StoreKitUI arm64  <7efbe539a56037578ab7070b37511470> /System/Library/PrivateFrameworks/StoreKitUI.framework/StoreKitUI
0x19806c000 - 0x19806cfff LegacyHandle arm64  <6d28874b23413e9b8620fbece8a8ecba> /System/Library/PrivateFrameworks/AVConference.framework/Frameworks/LegacyHandle.framework/LegacyHandle
0x198184000 - 0x1981a0fff MediaPlayerUI arm64  <19a9769cf21b3f7394e9f3f704f976ee> /System/Library/PrivateFrameworks/MediaPlayerUI.framework/MediaPlayerUI
0x1981ae000 - 0x1981aefff libAWDProtobufFacetimeiMessage.dylib arm64  <4e553eb98ccb3971a90a5ab93d740e90> /usr/lib/libAWDProtobufFacetimeiMessage.dylib
0x1981cf000 - 0x1981f5fff ViceroyTrace arm64  <04af74db3f6d30f4baa58f7f6d575790> /System/Library/PrivateFrameworks/AVConference.framework/Frameworks/ViceroyTrace.framework/ViceroyTrace
0x1981f6000 - 0x198201fff AppConduit arm64  <783d2522147830afaa61f0c601a2a5b7> /System/Library/PrivateFrameworks/AppConduit.framework/AppConduit
0x198202000 - 0x19821afff IAP arm64  <d34c6fc08e703fcc8aead2df632e632a> /System/Library/PrivateFrameworks/IAP.framework/IAP
0x1986f9000 - 0x198712fff ExternalAccessory arm64  <737026f3ccbd303aa8ad76b3f858a58d> /System/Library/Frameworks/ExternalAccessory.framework/ExternalAccessory
0x198713000 - 0x19876cfff WatchKit arm64  <5af1958437393d78afec3735306e46f4> /System/Library/Frameworks/WatchKit.framework/WatchKit
0x19876d000 - 0x198778fff SimpleKeyExchange arm64  <ca400d113659368c971198b5845660b7> /System/Library/PrivateFrameworks/AVConference.framework/Frameworks/SimpleKeyExchange.framework/SimpleKeyExchange
0x198779000 - 0x198779fff snatmap arm64  <b5a797c3d9b43661b4e49526909450f6> /System/Library/PrivateFrameworks/AVConference.framework/Frameworks/snatmap.framework/snatmap
0x1987e2000 - 0x198828fff ICE arm64  <8b3008d7a8c43e208ca27fc8052f0a72> /System/Library/PrivateFrameworks/AVConference.framework/Frameworks/ICE.framework/ICE
0x198ad8000 - 0x198b2bfff CallKit arm64  <652d287678e734d78bc29505b1b77c60> /System/Library/Frameworks/CallKit.framework/CallKit
0x198f66000 - 0x198f97fff OpenAL arm64  <62fc76ad963639aa929a917ad0e1c640> /System/Library/Frameworks/OpenAL.framework/OpenAL
0x19b4b0000 - 0x19b4d5fff AppSupportUI arm64  <5dc7a114b30c3678add34775f0680c84> /System/Library/PrivateFrameworks/AppSupportUI.framework/AppSupportUI
0x19bc7e000 - 0x19bd0dfff LinkPresentation arm64  <3eea89bbd66c3d0bbb59bf92ba075987> /System/Library/PrivateFrameworks/LinkPresentation.framework/LinkPresentation
0x19c241000 - 0x19c39afff libGLProgrammability.dylib arm64  <0a42e01ed4063a5087505c4d860b8d8b> /System/Library/Frameworks/OpenGLES.framework/libGLProgrammability.dylib
0x19c62c000 - 0x19c630fff libsysdiagnose.dylib arm64  <0956540a4aef38ef83b49cd0445debce> /usr/lib/libsysdiagnose.dylib
0x19e88e000 - 0x19e8e2fff MultipeerConnectivity arm64  <56d3126d4a103aabb3187bd18ef50ce2> /System/Library/Frameworks/MultipeerConnectivity.framework/MultipeerConnectivity
0x19edf0000 - 0x19ee01fff DeviceIdentity arm64  <4f5d7a89c9a339b4b4fbc101fe35f4e5> /System/Library/PrivateFrameworks/DeviceIdentity.framework/DeviceIdentity
0x1a1e3e000 - 0x1a2102fff RawCamera arm64  <8814153852d83e3986be71abbf2181f0> /System/Library/CoreServices/RawCamera.bundle/RawCamera
0x1a211a000 - 0x1a21c6fff AGXMetalA10 arm64  <a87a769dd2253300b9b161cd9b302905> /System/Library/Extensions/AGXMetalA10.bundle/AGXMetalA10
0x1a21d2000 - 0x1a21effff AppleMetalGLRenderer arm64  <7133f88fac3830cabfd4e668b777dee1> /System/Library/Extensions/AppleMetalGLRenderer.bundle/AppleMetalGLRenderer
0x1a21f0000 - 0x1a2204fff libCGInterfaces.dylib arm64  <a35cdaae6a3f3d0d9d0b776f0d2ccb89> /System/Library/Frameworks/Accelerate.framework/Frameworks/vImage.framework/Libraries/libCGInterfaces.dylib
0x1a2205000 - 0x1a2643fff AudioCodecs arm64  <9aa7cd9a7d423910a369f6e873be8c1f> /System/Library/Frameworks/AudioToolbox.framework/AudioCodecs
0x1a2f3f000 - 0x1a3029fff GLEngine arm64  <58eb59a5c3593cd7ae47be3d8e6e36c9> /System/Library/Frameworks/OpenGLES.framework/GLEngine.bundle/GLEngine
0x1a304e000 - 0x1a3052fff PushKit arm64  <bb546232d36e3c68807eb9f599a47961> /System/Library/Frameworks/PushKit.framework/PushKit
0x1a3077000 - 0x1a30b5fff WatchConnectivity arm64  <e717b54cac623a30acc93f75e44b6c39> /System/Library/Frameworks/WatchConnectivity.framework/WatchConnectivity
0x1a4621000 - 0x1a4637fff CoreAccessories arm64  <f042894762313f929c3d1e07ac221888> /System/Library/PrivateFrameworks/CoreAccessories.framework/CoreAccessories
0x1a47ff000 - 0x1a4826fff CoreServicesInternal arm64  <3e28627e61483e088b028a121a66cbeb> /System/Library/PrivateFrameworks/CoreServicesInternal.framework/CoreServicesInternal
0x1a4dfa000 - 0x1a4e0bfff libGSFontCache.dylib arm64  <9e56e388c1903b99bcd16d21cc3d1ea3> /System/Library/PrivateFrameworks/FontServices.framework/libGSFontCache.dylib
0x1a4e0c000 - 0x1a4e3efff libTrueTypeScaler.dylib arm64  <e584c6d569da381dbda666f0d9ea177b> /System/Library/PrivateFrameworks/FontServices.framework/libTrueTypeScaler.dylib
0x1a577d000 - 0x1a577dfff libmetal_timestamp.dylib arm64  <744ac9041fb63c9ab278a95d74b21c73> /System/Library/PrivateFrameworks/GPUCompiler.framework/Libraries/libmetal_timestamp.dylib
0x1a6685000 - 0x1a6688fff InternationalSupport arm64  <d2f1f0eee8093ae68cdf504f23f305d8> /System/Library/PrivateFrameworks/InternationalSupport.framework/InternationalSupport
0x1a83ff000 - 0x1a8404fff TextInputUI arm64  <debc3f7988543d8eac0cae88f34accf7> /System/Library/PrivateFrameworks/TextInputUI.framework/TextInputUI
0x1a92f4000 - 0x1a92fffff libMobileGestaltExtensions.dylib arm64  <343be95af1c33b20934be8dc2ee6800c> /usr/lib/libMobileGestaltExtensions.dylib
0x1aa38e000 - 0x1aa3a9fff OnBoardingKit arm64  <4f3a60fa92ad30e8b9c1619ba523ed3f> /System/Library/PrivateFrameworks/OnBoardingKit.framework/OnBoardingKit
0x1aa493000 - 0x1aa4c3fff libclosured.dylib arm64  <23ea8cc8f66931e4a59c47fb92b8baaa> /usr/lib/closure/libclosured.dylib

EOF


