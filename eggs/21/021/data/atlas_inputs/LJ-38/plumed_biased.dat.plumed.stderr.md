**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/LJ-38/plumed_biased.dat   
Download: [zipped raw stdout](plumed_biased.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_biased.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1695-570:10789] *** Process received signal ***
[fv-az1695-570:10789] Signal: Aborted (6)
[fv-az1695-570:10789] Signal code:  (-6)
[fv-az1695-570:10789] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbf6e445330]
[fv-az1695-570:10789] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbf6e49eb2c]
[fv-az1695-570:10789] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbf6e44527e]
[fv-az1695-570:10789] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbf6e4288ff]
[fv-az1695-570:10789] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbf6e8a5ff5]
[fv-az1695-570:10789] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbf6e8bb0da]
[fv-az1695-570:10789] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbf6e8a5a55]
[fv-az1695-570:10789] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbf6e8a5a6f]
[fv-az1695-570:10789] [ 8] plumed(+0x146dd)[0x55616893c6dd]
[fv-az1695-570:10789] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbf6e42a1ca]
[fv-az1695-570:10789] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbf6e42a28b]
[fv-az1695-570:10789] [11] plumed(+0x15365)[0x55616893d365]
[fv-az1695-570:10789] *** End of error message ***
</pre>
{% endraw %}
