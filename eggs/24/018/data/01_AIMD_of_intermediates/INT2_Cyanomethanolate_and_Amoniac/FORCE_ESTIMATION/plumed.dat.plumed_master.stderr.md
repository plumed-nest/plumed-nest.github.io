**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2_Cyanomethanolate_and_Amoniac/FORCE_ESTIMATION/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1280-696:06084] *** Process received signal ***
[fv-az1280-696:06084] Signal: Aborted (6)
[fv-az1280-696:06084] Signal code:  (-6)
[fv-az1280-696:06084] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7b86445330]
[fv-az1280-696:06084] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7b8649eb2c]
[fv-az1280-696:06084] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7b8644527e]
[fv-az1280-696:06084] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7b864288ff]
[fv-az1280-696:06084] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7b868a5ff5]
[fv-az1280-696:06084] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7b868bb0da]
[fv-az1280-696:06084] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7b868a5a55]
[fv-az1280-696:06084] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7b868a5a6f]
[fv-az1280-696:06084] [ 8] plumed_master(+0x146dd)[0x55ee514546dd]
[fv-az1280-696:06084] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7b8642a1ca]
[fv-az1280-696:06084] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7b8642a28b]
[fv-az1280-696:06084] [11] plumed_master(+0x15365)[0x55ee51455365]
[fv-az1280-696:06084] *** End of error message ***
</pre>
{% endraw %}
