**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[fv-az1947-163:67637] *** Process received signal ***
[fv-az1947-163:67637] Signal: Aborted (6)
[fv-az1947-163:67637] Signal code:  (-6)
[fv-az1947-163:67637] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fabafa45330]
[fv-az1947-163:67637] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fabafa9eb2c]
[fv-az1947-163:67637] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fabafa4527e]
[fv-az1947-163:67637] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fabafa288ff]
[fv-az1947-163:67637] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fabafea5ff5]
[fv-az1947-163:67637] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fabafebb0da]
[fv-az1947-163:67637] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fabafea5a55]
[fv-az1947-163:67637] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fabafea5a6f]
[fv-az1947-163:67637] [ 8] plumed(+0x146dd)[0x563cd01ba6dd]
[fv-az1947-163:67637] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fabafa2a1ca]
[fv-az1947-163:67637] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fabafa2a28b]
[fv-az1947-163:67637] [11] plumed(+0x15365)[0x563cd01bb365]
[fv-az1947-163:67637] *** End of error message ***
</pre>
{% endraw %}
