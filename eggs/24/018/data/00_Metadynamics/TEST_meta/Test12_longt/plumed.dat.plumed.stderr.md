**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test12_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmeorf1:06246] *** Process received signal ***
[runnervmeorf1:06246] Signal: Aborted (6)
[runnervmeorf1:06246] Signal code:  (-6)
[runnervmeorf1:06246] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fed92e45330]
[runnervmeorf1:06246] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fed92e9eb2c]
[runnervmeorf1:06246] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fed92e4527e]
[runnervmeorf1:06246] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fed92e288ff]
[runnervmeorf1:06246] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fed932a5ff5]
[runnervmeorf1:06246] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fed932bb0da]
[runnervmeorf1:06246] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fed932a5a55]
[runnervmeorf1:06246] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fed932a5a6f]
[runnervmeorf1:06246] [ 8] plumed(+0x146dd)[0x5646e95486dd]
[runnervmeorf1:06246] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fed92e2a1ca]
[runnervmeorf1:06246] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fed92e2a28b]
[runnervmeorf1:06246] [11] plumed(+0x15365)[0x5646e9549365]
[runnervmeorf1:06246] *** End of error message ***
</pre>
{% endraw %}
