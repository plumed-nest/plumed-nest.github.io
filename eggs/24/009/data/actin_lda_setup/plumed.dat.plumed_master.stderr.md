**Project ID:** [plumID:24.009]({{ '/' | absolute_url }}eggs/24/009/)  
Stderr for source:  actin_lda_setup/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "LDA_PROJ" is not known.
[pkrvmbietmlfzoi:62395] *** Process received signal ***
[pkrvmbietmlfzoi:62395] Signal: Aborted (6)
[pkrvmbietmlfzoi:62395] Signal code:  (-6)
[pkrvmbietmlfzoi:62395] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f736b445330]
[pkrvmbietmlfzoi:62395] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f736b49eb2c]
[pkrvmbietmlfzoi:62395] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f736b44527e]
[pkrvmbietmlfzoi:62395] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f736b4288ff]
[pkrvmbietmlfzoi:62395] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f736b8a5ff5]
[pkrvmbietmlfzoi:62395] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f736b8bb0da]
[pkrvmbietmlfzoi:62395] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f736b8a5a55]
[pkrvmbietmlfzoi:62395] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f736b8a5a6f]
[pkrvmbietmlfzoi:62395] [ 8] plumed_master(+0x146dd)[0x555ad68df6dd]
[pkrvmbietmlfzoi:62395] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f736b42a1ca]
[pkrvmbietmlfzoi:62395] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f736b42a28b]
[pkrvmbietmlfzoi:62395] [11] plumed_master(+0x15365)[0x555ad68e0365]
[pkrvmbietmlfzoi:62395] *** End of error message ***
</pre>
{% endraw %}
