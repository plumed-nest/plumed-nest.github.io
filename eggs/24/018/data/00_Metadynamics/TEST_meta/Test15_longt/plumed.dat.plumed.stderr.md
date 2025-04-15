**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test15_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1693-957:61765] *** Process received signal ***
[fv-az1693-957:61765] Signal: Aborted (6)
[fv-az1693-957:61765] Signal code:  (-6)
[fv-az1693-957:61765] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7586c45330]
[fv-az1693-957:61765] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7586c9eb2c]
[fv-az1693-957:61765] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7586c4527e]
[fv-az1693-957:61765] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7586c288ff]
[fv-az1693-957:61765] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f75870a5ff5]
[fv-az1693-957:61765] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f75870bb0da]
[fv-az1693-957:61765] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f75870a5a55]
[fv-az1693-957:61765] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f75870a5a6f]
[fv-az1693-957:61765] [ 8] plumed(+0x146dd)[0x55a05a68f6dd]
[fv-az1693-957:61765] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7586c2a1ca]
[fv-az1693-957:61765] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7586c2a28b]
[fv-az1693-957:61765] [11] plumed(+0x15365)[0x55a05a690365]
[fv-az1693-957:61765] *** End of error message ***
</pre>
{% endraw %}
