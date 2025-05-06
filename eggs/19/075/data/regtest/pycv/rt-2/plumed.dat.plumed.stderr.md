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
[fv-az1696-883:67441] *** Process received signal ***
[fv-az1696-883:67441] Signal: Aborted (6)
[fv-az1696-883:67441] Signal code:  (-6)
[fv-az1696-883:67441] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f914a245330]
[fv-az1696-883:67441] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f914a29eb2c]
[fv-az1696-883:67441] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f914a24527e]
[fv-az1696-883:67441] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f914a2288ff]
[fv-az1696-883:67441] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f914a6a5ff5]
[fv-az1696-883:67441] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f914a6bb0da]
[fv-az1696-883:67441] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f914a6a5a55]
[fv-az1696-883:67441] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f914a6a5a6f]
[fv-az1696-883:67441] [ 8] plumed(+0x146dd)[0x55892e0e46dd]
[fv-az1696-883:67441] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f914a22a1ca]
[fv-az1696-883:67441] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f914a22a28b]
[fv-az1696-883:67441] [11] plumed(+0x15365)[0x55892e0e5365]
[fv-az1696-883:67441] *** End of error message ***
</pre>
{% endraw %}
