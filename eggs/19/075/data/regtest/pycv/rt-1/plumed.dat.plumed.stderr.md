**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az1947-163:67585] *** Process received signal ***
[fv-az1947-163:67585] Signal: Aborted (6)
[fv-az1947-163:67585] Signal code:  (-6)
[fv-az1947-163:67585] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1bcf845330]
[fv-az1947-163:67585] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1bcf89eb2c]
[fv-az1947-163:67585] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1bcf84527e]
[fv-az1947-163:67585] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1bcf8288ff]
[fv-az1947-163:67585] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f1bcfca5ff5]
[fv-az1947-163:67585] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f1bcfcbb0da]
[fv-az1947-163:67585] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f1bcfca5a55]
[fv-az1947-163:67585] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f1bcfca5a6f]
[fv-az1947-163:67585] [ 8] plumed(+0x146dd)[0x55c00782c6dd]
[fv-az1947-163:67585] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1bcf82a1ca]
[fv-az1947-163:67585] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1bcf82a28b]
[fv-az1947-163:67585] [11] plumed(+0x15365)[0x55c00782d365]
[fv-az1947-163:67585] *** End of error message ***
</pre>
{% endraw %}
