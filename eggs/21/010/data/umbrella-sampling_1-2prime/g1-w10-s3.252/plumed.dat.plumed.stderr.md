**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w10-s3.252/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1693-957:65608] *** Process received signal ***
[fv-az1693-957:65608] Signal: Aborted (6)
[fv-az1693-957:65608] Signal code:  (-6)
[fv-az1693-957:65608] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb45d045330]
[fv-az1693-957:65608] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb45d09eb2c]
[fv-az1693-957:65608] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb45d04527e]
[fv-az1693-957:65608] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb45d0288ff]
[fv-az1693-957:65608] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb45d4a5ff5]
[fv-az1693-957:65608] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb45d4bb0da]
[fv-az1693-957:65608] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb45d4a5a55]
[fv-az1693-957:65608] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb45d4a5a6f]
[fv-az1693-957:65608] [ 8] plumed(+0x146dd)[0x55c032ad16dd]
[fv-az1693-957:65608] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb45d02a1ca]
[fv-az1693-957:65608] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb45d02a28b]
[fv-az1693-957:65608] [11] plumed(+0x15365)[0x55c032ad2365]
[fv-az1693-957:65608] *** End of error message ***
</pre>
{% endraw %}
