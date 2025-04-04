**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_6d/pca_2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1695-570:11168] *** Process received signal ***
[fv-az1695-570:11168] Signal: Aborted (6)
[fv-az1695-570:11168] Signal code:  (-6)
[fv-az1695-570:11168] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4694245330]
[fv-az1695-570:11168] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f469429eb2c]
[fv-az1695-570:11168] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f469424527e]
[fv-az1695-570:11168] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f46942288ff]
[fv-az1695-570:11168] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f46946a5ff5]
[fv-az1695-570:11168] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f46946bb0da]
[fv-az1695-570:11168] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f46946a5a55]
[fv-az1695-570:11168] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f46946a5a6f]
[fv-az1695-570:11168] [ 8] plumed_master(+0x146dd)[0x5651949b66dd]
[fv-az1695-570:11168] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f469422a1ca]
[fv-az1695-570:11168] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f469422a28b]
[fv-az1695-570:11168] [11] plumed_master(+0x15365)[0x5651949b7365]
[fv-az1695-570:11168] *** End of error message ***
</pre>
{% endraw %}
