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
[fv-az1377-740:64380] *** Process received signal ***
[fv-az1377-740:64380] Signal: Aborted (6)
[fv-az1377-740:64380] Signal code:  (-6)
[fv-az1377-740:64380] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3cd6445330]
[fv-az1377-740:64380] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3cd649eb2c]
[fv-az1377-740:64380] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3cd644527e]
[fv-az1377-740:64380] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3cd64288ff]
[fv-az1377-740:64380] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3cd68a5ff5]
[fv-az1377-740:64380] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3cd68bb0da]
[fv-az1377-740:64380] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3cd68a5a55]
[fv-az1377-740:64380] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3cd68a5a6f]
[fv-az1377-740:64380] [ 8] plumed(+0x146dd)[0x559d34e006dd]
[fv-az1377-740:64380] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3cd642a1ca]
[fv-az1377-740:64380] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3cd642a28b]
[fv-az1377-740:64380] [11] plumed(+0x15365)[0x559d34e01365]
[fv-az1377-740:64380] *** End of error message ***
</pre>
{% endraw %}
