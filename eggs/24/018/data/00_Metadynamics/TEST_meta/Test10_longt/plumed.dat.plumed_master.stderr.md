**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test10_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmeorf1:06157] *** Process received signal ***
[runnervmeorf1:06157] Signal: Aborted (6)
[runnervmeorf1:06157] Signal code:  (-6)
[runnervmeorf1:06157] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb8f8645330]
[runnervmeorf1:06157] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb8f869eb2c]
[runnervmeorf1:06157] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb8f864527e]
[runnervmeorf1:06157] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb8f86288ff]
[runnervmeorf1:06157] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb8f8aa5ff5]
[runnervmeorf1:06157] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb8f8abb0da]
[runnervmeorf1:06157] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb8f8aa5a55]
[runnervmeorf1:06157] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb8f8aa5a6f]
[runnervmeorf1:06157] [ 8] plumed_master(+0x146dd)[0x556bba2fe6dd]
[runnervmeorf1:06157] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb8f862a1ca]
[runnervmeorf1:06157] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb8f862a28b]
[runnervmeorf1:06157] [11] plumed_master(+0x15365)[0x556bba2ff365]
[runnervmeorf1:06157] *** End of error message ***
</pre>
{% endraw %}
