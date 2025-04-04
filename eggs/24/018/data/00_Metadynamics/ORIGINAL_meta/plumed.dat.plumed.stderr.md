**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/ORIGINAL_meta/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1360-658:06449] *** Process received signal ***
[fv-az1360-658:06449] Signal: Aborted (6)
[fv-az1360-658:06449] Signal code:  (-6)
[fv-az1360-658:06449] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2972c45330]
[fv-az1360-658:06449] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2972c9eb2c]
[fv-az1360-658:06449] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2972c4527e]
[fv-az1360-658:06449] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2972c288ff]
[fv-az1360-658:06449] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f29730a5ff5]
[fv-az1360-658:06449] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f29730bb0da]
[fv-az1360-658:06449] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f29730a5a55]
[fv-az1360-658:06449] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f29730a5a6f]
[fv-az1360-658:06449] [ 8] plumed(+0x146dd)[0x555917a006dd]
[fv-az1360-658:06449] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2972c2a1ca]
[fv-az1360-658:06449] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2972c2a28b]
[fv-az1360-658:06449] [11] plumed(+0x15365)[0x555917a01365]
[fv-az1360-658:06449] *** End of error message ***
</pre>
{% endraw %}
