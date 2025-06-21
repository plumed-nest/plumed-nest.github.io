**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test11_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmxyh4eaekms:06438] *** Process received signal ***
[pkrvmxyh4eaekms:06438] Signal: Aborted (6)
[pkrvmxyh4eaekms:06438] Signal code:  (-6)
[pkrvmxyh4eaekms:06438] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8e10245330]
[pkrvmxyh4eaekms:06438] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8e1029eb2c]
[pkrvmxyh4eaekms:06438] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8e1024527e]
[pkrvmxyh4eaekms:06438] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8e102288ff]
[pkrvmxyh4eaekms:06438] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8e106a5ff5]
[pkrvmxyh4eaekms:06438] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8e106bb0da]
[pkrvmxyh4eaekms:06438] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8e106a5a55]
[pkrvmxyh4eaekms:06438] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8e106a5a6f]
[pkrvmxyh4eaekms:06438] [ 8] plumed_master(+0x146dd)[0x56177e3056dd]
[pkrvmxyh4eaekms:06438] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8e1022a1ca]
[pkrvmxyh4eaekms:06438] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8e1022a28b]
[pkrvmxyh4eaekms:06438] [11] plumed_master(+0x15365)[0x56177e306365]
[pkrvmxyh4eaekms:06438] *** End of error message ***
</pre>
{% endraw %}
