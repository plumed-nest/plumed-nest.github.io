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
[pkrvmbietmlfzoi:07196] *** Process received signal ***
[pkrvmbietmlfzoi:07196] Signal: Aborted (6)
[pkrvmbietmlfzoi:07196] Signal code:  (-6)
[pkrvmbietmlfzoi:07196] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f4474c45330]
[pkrvmbietmlfzoi:07196] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f4474c9eb2c]
[pkrvmbietmlfzoi:07196] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f4474c4527e]
[pkrvmbietmlfzoi:07196] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f4474c288ff]
[pkrvmbietmlfzoi:07196] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f44750a5ff5]
[pkrvmbietmlfzoi:07196] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f44750bb0da]
[pkrvmbietmlfzoi:07196] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f44750a5a55]
[pkrvmbietmlfzoi:07196] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f44750a5a6f]
[pkrvmbietmlfzoi:07196] [ 8] plumed_master(+0x146dd)[0x5565945d56dd]
[pkrvmbietmlfzoi:07196] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f4474c2a1ca]
[pkrvmbietmlfzoi:07196] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f4474c2a28b]
[pkrvmbietmlfzoi:07196] [11] plumed_master(+0x15365)[0x5565945d6365]
[pkrvmbietmlfzoi:07196] *** End of error message ***
</pre>
{% endraw %}
