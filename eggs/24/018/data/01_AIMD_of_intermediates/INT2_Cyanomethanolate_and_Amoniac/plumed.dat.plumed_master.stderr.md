**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2_Cyanomethanolate_and_Amoniac/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1280-696:06135] *** Process received signal ***
[fv-az1280-696:06135] Signal: Aborted (6)
[fv-az1280-696:06135] Signal code:  (-6)
[fv-az1280-696:06135] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7415c45330]
[fv-az1280-696:06135] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7415c9eb2c]
[fv-az1280-696:06135] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7415c4527e]
[fv-az1280-696:06135] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7415c288ff]
[fv-az1280-696:06135] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f74160a5ff5]
[fv-az1280-696:06135] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f74160bb0da]
[fv-az1280-696:06135] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f74160a5a55]
[fv-az1280-696:06135] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f74160a5a6f]
[fv-az1280-696:06135] [ 8] plumed_master(+0x146dd)[0x55c10dc416dd]
[fv-az1280-696:06135] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7415c2a1ca]
[fv-az1280-696:06135] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7415c2a28b]
[fv-az1280-696:06135] [11] plumed_master(+0x15365)[0x55c10dc42365]
[fv-az1280-696:06135] *** End of error message ***
</pre>
{% endraw %}
