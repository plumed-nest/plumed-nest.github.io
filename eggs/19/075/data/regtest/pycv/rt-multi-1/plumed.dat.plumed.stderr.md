**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-multi-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az1440-40:65998] *** Process received signal ***
[fv-az1440-40:65998] Signal: Aborted (6)
[fv-az1440-40:65998] Signal code:  (-6)
[fv-az1440-40:65998] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7d0d045330]
[fv-az1440-40:65998] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7d0d09eb2c]
[fv-az1440-40:65998] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7d0d04527e]
[fv-az1440-40:65998] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7d0d0288ff]
[fv-az1440-40:65998] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7d0d4a5ff5]
[fv-az1440-40:65998] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7d0d4bb0da]
[fv-az1440-40:65998] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7d0d4a5a55]
[fv-az1440-40:65998] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7d0d4a5a6f]
[fv-az1440-40:65998] [ 8] plumed(+0x146dd)[0x55f342cda6dd]
[fv-az1440-40:65998] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7d0d02a1ca]
[fv-az1440-40:65998] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7d0d02a28b]
[fv-az1440-40:65998] [11] plumed(+0x15365)[0x55f342cdb365]
[fv-az1440-40:65998] *** End of error message ***
</pre>
{% endraw %}
