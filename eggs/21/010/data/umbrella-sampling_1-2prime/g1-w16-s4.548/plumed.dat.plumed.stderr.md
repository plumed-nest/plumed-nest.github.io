**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w16-s4.548/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmeorf1:10650] *** Process received signal ***
[runnervmeorf1:10650] Signal: Aborted (6)
[runnervmeorf1:10650] Signal code:  (-6)
[runnervmeorf1:10650] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f521a645330]
[runnervmeorf1:10650] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f521a69eb2c]
[runnervmeorf1:10650] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f521a64527e]
[runnervmeorf1:10650] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f521a6288ff]
[runnervmeorf1:10650] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f521aaa5ff5]
[runnervmeorf1:10650] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f521aabb0da]
[runnervmeorf1:10650] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f521aaa5a55]
[runnervmeorf1:10650] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f521aaa5a6f]
[runnervmeorf1:10650] [ 8] plumed(+0x146dd)[0x5641713636dd]
[runnervmeorf1:10650] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f521a62a1ca]
[runnervmeorf1:10650] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f521a62a28b]
[runnervmeorf1:10650] [11] plumed(+0x15365)[0x564171364365]
[runnervmeorf1:10650] *** End of error message ***
</pre>
{% endraw %}
