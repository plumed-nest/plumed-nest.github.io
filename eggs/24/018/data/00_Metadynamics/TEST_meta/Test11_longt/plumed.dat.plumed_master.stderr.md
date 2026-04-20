**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test11_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmeorf1:06210] *** Process received signal ***
[runnervmeorf1:06210] Signal: Aborted (6)
[runnervmeorf1:06210] Signal code:  (-6)
[runnervmeorf1:06210] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7211845330]
[runnervmeorf1:06210] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f721189eb2c]
[runnervmeorf1:06210] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f721184527e]
[runnervmeorf1:06210] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f72118288ff]
[runnervmeorf1:06210] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7211ca5ff5]
[runnervmeorf1:06210] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7211cbb0da]
[runnervmeorf1:06210] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7211ca5a55]
[runnervmeorf1:06210] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7211ca5a6f]
[runnervmeorf1:06210] [ 8] plumed_master(+0x146dd)[0x55622a0ef6dd]
[runnervmeorf1:06210] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f721182a1ca]
[runnervmeorf1:06210] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f721182a28b]
[runnervmeorf1:06210] [11] plumed_master(+0x15365)[0x55622a0f0365]
[runnervmeorf1:06210] *** End of error message ***
</pre>
{% endraw %}
