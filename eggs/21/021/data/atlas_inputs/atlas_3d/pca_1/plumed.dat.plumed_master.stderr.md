**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/atlas_3d/pca_1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1695-570:10963] *** Process received signal ***
[fv-az1695-570:10963] Signal: Aborted (6)
[fv-az1695-570:10963] Signal code:  (-6)
[fv-az1695-570:10963] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc4f4845330]
[fv-az1695-570:10963] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc4f489eb2c]
[fv-az1695-570:10963] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc4f484527e]
[fv-az1695-570:10963] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc4f48288ff]
[fv-az1695-570:10963] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc4f4ca5ff5]
[fv-az1695-570:10963] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc4f4cbb0da]
[fv-az1695-570:10963] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc4f4ca5a55]
[fv-az1695-570:10963] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc4f4ca5a6f]
[fv-az1695-570:10963] [ 8] plumed_master(+0x146dd)[0x55c33db0e6dd]
[fv-az1695-570:10963] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc4f482a1ca]
[fv-az1695-570:10963] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc4f482a28b]
[fv-az1695-570:10963] [11] plumed_master(+0x15365)[0x55c33db0f365]
[fv-az1695-570:10963] *** End of error message ***
</pre>
{% endraw %}
