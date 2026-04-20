**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test14_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmeorf1:06364] *** Process received signal ***
[runnervmeorf1:06364] Signal: Aborted (6)
[runnervmeorf1:06364] Signal code:  (-6)
[runnervmeorf1:06364] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f543e845330]
[runnervmeorf1:06364] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f543e89eb2c]
[runnervmeorf1:06364] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f543e84527e]
[runnervmeorf1:06364] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f543e8288ff]
[runnervmeorf1:06364] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f543eca5ff5]
[runnervmeorf1:06364] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f543ecbb0da]
[runnervmeorf1:06364] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f543eca5a55]
[runnervmeorf1:06364] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f543eca5a6f]
[runnervmeorf1:06364] [ 8] plumed_master(+0x146dd)[0x557e30b6d6dd]
[runnervmeorf1:06364] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f543e82a1ca]
[runnervmeorf1:06364] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f543e82a28b]
[runnervmeorf1:06364] [11] plumed_master(+0x15365)[0x557e30b6e365]
[runnervmeorf1:06364] *** End of error message ***
</pre>
{% endraw %}
