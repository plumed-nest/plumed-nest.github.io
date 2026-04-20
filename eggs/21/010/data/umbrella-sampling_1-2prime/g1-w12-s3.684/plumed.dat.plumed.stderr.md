**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w12-s3.684/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmeorf1:10441] *** Process received signal ***
[runnervmeorf1:10441] Signal: Aborted (6)
[runnervmeorf1:10441] Signal code:  (-6)
[runnervmeorf1:10441] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f761b245330]
[runnervmeorf1:10441] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f761b29eb2c]
[runnervmeorf1:10441] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f761b24527e]
[runnervmeorf1:10441] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f761b2288ff]
[runnervmeorf1:10441] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f761b6a5ff5]
[runnervmeorf1:10441] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f761b6bb0da]
[runnervmeorf1:10441] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f761b6a5a55]
[runnervmeorf1:10441] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f761b6a5a6f]
[runnervmeorf1:10441] [ 8] plumed(+0x146dd)[0x5634a6c606dd]
[runnervmeorf1:10441] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f761b22a1ca]
[runnervmeorf1:10441] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f761b22a28b]
[runnervmeorf1:10441] [11] plumed(+0x15365)[0x5634a6c61365]
[runnervmeorf1:10441] *** End of error message ***
</pre>
{% endraw %}
