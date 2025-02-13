**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w24-s6.276/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1390-170:11030] *** Process received signal ***
[fv-az1390-170:11030] Signal: Aborted (6)
[fv-az1390-170:11030] Signal code:  (-6)
[fv-az1390-170:11030] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa6c8c45330]
[fv-az1390-170:11030] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa6c8c9eb2c]
[fv-az1390-170:11030] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa6c8c4527e]
[fv-az1390-170:11030] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa6c8c288ff]
[fv-az1390-170:11030] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa6c90a5ff5]
[fv-az1390-170:11030] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa6c90bb0da]
[fv-az1390-170:11030] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa6c90a5a55]
[fv-az1390-170:11030] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa6c90a5a6f]
[fv-az1390-170:11030] [ 8] plumed(+0x146dd)[0x55dd996456dd]
[fv-az1390-170:11030] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa6c8c2a1ca]
[fv-az1390-170:11030] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa6c8c2a28b]
[fv-az1390-170:11030] [11] plumed(+0x15365)[0x55dd99646365]
[fv-az1390-170:11030] *** End of error message ***
</pre>
{% endraw %}
