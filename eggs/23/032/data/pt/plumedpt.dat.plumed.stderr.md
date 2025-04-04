**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  pt/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[fv-az1360-658:08100] *** Process received signal ***
[fv-az1360-658:08100] Signal: Aborted (6)
[fv-az1360-658:08100] Signal code:  (-6)
[fv-az1360-658:08100] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fed62845330]
[fv-az1360-658:08100] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fed6289eb2c]
[fv-az1360-658:08100] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fed6284527e]
[fv-az1360-658:08100] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fed628288ff]
[fv-az1360-658:08100] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fed62ca5ff5]
[fv-az1360-658:08100] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fed62cbb0da]
[fv-az1360-658:08100] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fed62ca5a55]
[fv-az1360-658:08100] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fed62ca5a6f]
[fv-az1360-658:08100] [ 8] plumed(+0x146dd)[0x55dfcf1ad6dd]
[fv-az1360-658:08100] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fed6282a1ca]
[fv-az1360-658:08100] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fed6282a28b]
[fv-az1360-658:08100] [11] plumed(+0x15365)[0x55dfcf1ae365]
[fv-az1360-658:08100] *** End of error message ***
</pre>
{% endraw %}
