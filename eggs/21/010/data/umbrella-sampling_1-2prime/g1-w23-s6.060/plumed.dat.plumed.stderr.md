**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w23-s6.060/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmeorf1:11061] *** Process received signal ***
[runnervmeorf1:11061] Signal: Aborted (6)
[runnervmeorf1:11061] Signal code:  (-6)
[runnervmeorf1:11061] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7feeaea45330]
[runnervmeorf1:11061] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7feeaea9eb2c]
[runnervmeorf1:11061] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7feeaea4527e]
[runnervmeorf1:11061] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7feeaea288ff]
[runnervmeorf1:11061] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7feeaeea5ff5]
[runnervmeorf1:11061] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7feeaeebb0da]
[runnervmeorf1:11061] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7feeaeea5a55]
[runnervmeorf1:11061] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7feeaeea5a6f]
[runnervmeorf1:11061] [ 8] plumed(+0x146dd)[0x558b21c856dd]
[runnervmeorf1:11061] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7feeaea2a1ca]
[runnervmeorf1:11061] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7feeaea2a28b]
[runnervmeorf1:11061] [11] plumed(+0x15365)[0x558b21c86365]
[runnervmeorf1:11061] *** End of error message ***
</pre>
{% endraw %}
