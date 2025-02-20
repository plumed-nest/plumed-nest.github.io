**Project ID:** [plumID:21.021]({{ '/' | absolute_url }}eggs/21/021/)  
Stderr for source:  atlas_inputs/LJ-38/plumed_biased.dat   
Download: [zipped raw stdout](plumed_biased.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_biased.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATLAS" is not known.
[fv-az1720-841:08755] *** Process received signal ***
[fv-az1720-841:08755] Signal: Aborted (6)
[fv-az1720-841:08755] Signal code:  (-6)
[fv-az1720-841:08755] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9e36445330]
[fv-az1720-841:08755] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9e3649eb2c]
[fv-az1720-841:08755] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9e3644527e]
[fv-az1720-841:08755] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9e364288ff]
[fv-az1720-841:08755] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9e368a5ff5]
[fv-az1720-841:08755] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9e368bb0da]
[fv-az1720-841:08755] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9e368a5a55]
[fv-az1720-841:08755] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9e368a5a6f]
[fv-az1720-841:08755] [ 8] plumed_master(+0x146dd)[0x55ae98cb96dd]
[fv-az1720-841:08755] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9e3642a1ca]
[fv-az1720-841:08755] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9e3642a28b]
[fv-az1720-841:08755] [11] plumed_master(+0x15365)[0x55ae98cba365]
[fv-az1720-841:08755] *** End of error message ***
</pre>
{% endraw %}
