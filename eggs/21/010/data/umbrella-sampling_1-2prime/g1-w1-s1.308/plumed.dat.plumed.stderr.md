**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w1-s1.308/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmeorf1:10287] *** Process received signal ***
[runnervmeorf1:10287] Signal: Aborted (6)
[runnervmeorf1:10287] Signal code:  (-6)
[runnervmeorf1:10287] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f0c07e45330]
[runnervmeorf1:10287] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f0c07e9eb2c]
[runnervmeorf1:10287] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f0c07e4527e]
[runnervmeorf1:10287] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f0c07e288ff]
[runnervmeorf1:10287] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f0c082a5ff5]
[runnervmeorf1:10287] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f0c082bb0da]
[runnervmeorf1:10287] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f0c082a5a55]
[runnervmeorf1:10287] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f0c082a5a6f]
[runnervmeorf1:10287] [ 8] plumed(+0x146dd)[0x557558dd26dd]
[runnervmeorf1:10287] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f0c07e2a1ca]
[runnervmeorf1:10287] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f0c07e2a28b]
[runnervmeorf1:10287] [11] plumed(+0x15365)[0x557558dd3365]
[runnervmeorf1:10287] *** End of error message ***
</pre>
{% endraw %}
