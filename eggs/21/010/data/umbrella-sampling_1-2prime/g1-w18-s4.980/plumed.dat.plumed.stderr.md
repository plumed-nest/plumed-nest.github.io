**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w18-s4.980/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmeorf1:10754] *** Process received signal ***
[runnervmeorf1:10754] Signal: Aborted (6)
[runnervmeorf1:10754] Signal code:  (-6)
[runnervmeorf1:10754] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f587cc45330]
[runnervmeorf1:10754] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f587cc9eb2c]
[runnervmeorf1:10754] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f587cc4527e]
[runnervmeorf1:10754] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f587cc288ff]
[runnervmeorf1:10754] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f587d0a5ff5]
[runnervmeorf1:10754] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f587d0bb0da]
[runnervmeorf1:10754] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f587d0a5a55]
[runnervmeorf1:10754] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f587d0a5a6f]
[runnervmeorf1:10754] [ 8] plumed(+0x146dd)[0x5555c47506dd]
[runnervmeorf1:10754] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f587cc2a1ca]
[runnervmeorf1:10754] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f587cc2a28b]
[runnervmeorf1:10754] [11] plumed(+0x15365)[0x5555c4751365]
[runnervmeorf1:10754] *** End of error message ***
</pre>
{% endraw %}
