**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_3d/res/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1695-570:11066] *** Process received signal ***
[fv-az1695-570:11066] Signal: Aborted (6)
[fv-az1695-570:11066] Signal code:  (-6)
[fv-az1695-570:11066] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f88c4c45330]
[fv-az1695-570:11066] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f88c4c9eb2c]
[fv-az1695-570:11066] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f88c4c4527e]
[fv-az1695-570:11066] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f88c4c288ff]
[fv-az1695-570:11066] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f88c50a5ff5]
[fv-az1695-570:11066] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f88c50bb0da]
[fv-az1695-570:11066] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f88c50a5a55]
[fv-az1695-570:11066] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f88c50a5a6f]
[fv-az1695-570:11066] [ 8] plumed_master(+0x146dd)[0x562ebfa666dd]
[fv-az1695-570:11066] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f88c4c2a1ca]
[fv-az1695-570:11066] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f88c4c2a28b]
[fv-az1695-570:11066] [11] plumed_master(+0x15365)[0x562ebfa67365]
[fv-az1695-570:11066] *** End of error message ***
</pre>
{% endraw %}
