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
[fv-az1693-957:65713] *** Process received signal ***
[fv-az1693-957:65713] Signal: Aborted (6)
[fv-az1693-957:65713] Signal code:  (-6)
[fv-az1693-957:65713] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f84f1445330]
[fv-az1693-957:65713] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f84f149eb2c]
[fv-az1693-957:65713] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f84f144527e]
[fv-az1693-957:65713] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f84f14288ff]
[fv-az1693-957:65713] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f84f18a5ff5]
[fv-az1693-957:65713] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f84f18bb0da]
[fv-az1693-957:65713] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f84f18a5a55]
[fv-az1693-957:65713] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f84f18a5a6f]
[fv-az1693-957:65713] [ 8] plumed(+0x146dd)[0x560280a9a6dd]
[fv-az1693-957:65713] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f84f142a1ca]
[fv-az1693-957:65713] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f84f142a28b]
[fv-az1693-957:65713] [11] plumed(+0x15365)[0x560280a9b365]
[fv-az1693-957:65713] *** End of error message ***
</pre>
{% endraw %}
