**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/di_pept/plumed_biased.dat   
Download: [zipped raw stdout](plumed_biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1695-570:11255] *** Process received signal ***
[fv-az1695-570:11255] Signal: Aborted (6)
[fv-az1695-570:11255] Signal code:  (-6)
[fv-az1695-570:11255] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f5d16045330]
[fv-az1695-570:11255] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f5d1609eb2c]
[fv-az1695-570:11255] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f5d1604527e]
[fv-az1695-570:11255] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f5d160288ff]
[fv-az1695-570:11255] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f5d164a5ff5]
[fv-az1695-570:11255] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f5d164bb0da]
[fv-az1695-570:11255] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f5d164a5a55]
[fv-az1695-570:11255] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f5d164a5a6f]
[fv-az1695-570:11255] [ 8] plumed(+0x146dd)[0x55ad4e27a6dd]
[fv-az1695-570:11255] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f5d1602a1ca]
[fv-az1695-570:11255] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f5d1602a28b]
[fv-az1695-570:11255] [11] plumed(+0x15365)[0x55ad4e27b365]
[fv-az1695-570:11255] *** End of error message ***
</pre>
{% endraw %}
