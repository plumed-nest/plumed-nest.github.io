**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_mo.dat   
Download: [zipped raw stdout](plumed_mo.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_mo.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS285=9378,9382" is not known.
[fv-az797-511:07607] *** Process received signal ***
[fv-az797-511:07607] Signal: Aborted (6)
[fv-az797-511:07607] Signal code:  (-6)
[fv-az797-511:07607] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff082045330]
[fv-az797-511:07607] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff08209eb2c]
[fv-az797-511:07607] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff08204527e]
[fv-az797-511:07607] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff0820288ff]
[fv-az797-511:07607] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff0824a5ff5]
[fv-az797-511:07607] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff0824bb0da]
[fv-az797-511:07607] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff0824a5a55]
[fv-az797-511:07607] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff0824a5a6f]
[fv-az797-511:07607] [ 8] plumed_master(+0x146dd)[0x55de807d06dd]
[fv-az797-511:07607] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff08202a1ca]
[fv-az797-511:07607] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff08202a28b]
[fv-az797-511:07607] [11] plumed_master(+0x15365)[0x55de807d1365]
[fv-az797-511:07607] *** End of error message ***
</pre>
{% endraw %}
