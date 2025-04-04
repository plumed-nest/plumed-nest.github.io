**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_3d/pca_2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1695-570:10999] *** Process received signal ***
[fv-az1695-570:10999] Signal: Aborted (6)
[fv-az1695-570:10999] Signal code:  (-6)
[fv-az1695-570:10999] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f17e0845330]
[fv-az1695-570:10999] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f17e089eb2c]
[fv-az1695-570:10999] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f17e084527e]
[fv-az1695-570:10999] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f17e08288ff]
[fv-az1695-570:10999] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f17e0ca5ff5]
[fv-az1695-570:10999] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f17e0cbb0da]
[fv-az1695-570:10999] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f17e0ca5a55]
[fv-az1695-570:10999] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f17e0ca5a6f]
[fv-az1695-570:10999] [ 8] plumed(+0x146dd)[0x55b9e098a6dd]
[fv-az1695-570:10999] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f17e082a1ca]
[fv-az1695-570:10999] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f17e082a28b]
[fv-az1695-570:10999] [11] plumed(+0x15365)[0x55b9e098b365]
[fv-az1695-570:10999] *** End of error message ***
</pre>
{% endraw %}
