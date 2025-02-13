**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[fv-az1693-854:11785] *** Process received signal ***
[fv-az1693-854:11785] Signal: Aborted (6)
[fv-az1693-854:11785] Signal code:  (-6)
[fv-az1693-854:11785] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff99a445330]
[fv-az1693-854:11785] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff99a49eb2c]
[fv-az1693-854:11785] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff99a44527e]
[fv-az1693-854:11785] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff99a4288ff]
[fv-az1693-854:11785] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff99a8a5ff5]
[fv-az1693-854:11785] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff99a8bb0da]
[fv-az1693-854:11785] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff99a8a5a55]
[fv-az1693-854:11785] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff99a8a5a6f]
[fv-az1693-854:11785] [ 8] plumed(+0x146dd)[0x5625efcc86dd]
[fv-az1693-854:11785] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff99a42a1ca]
[fv-az1693-854:11785] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff99a42a28b]
[fv-az1693-854:11785] [11] plumed(+0x15365)[0x5625efcc9365]
[fv-az1693-854:11785] *** End of error message ***
</pre>
{% endraw %}
