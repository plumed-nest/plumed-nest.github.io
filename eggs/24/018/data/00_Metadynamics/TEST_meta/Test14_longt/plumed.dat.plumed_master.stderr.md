**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test14_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[pkrvmbietmlfzoi:07780] *** Process received signal ***
[pkrvmbietmlfzoi:07780] Signal: Aborted (6)
[pkrvmbietmlfzoi:07780] Signal code:  (-6)
[pkrvmbietmlfzoi:07780] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7858845330]
[pkrvmbietmlfzoi:07780] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f785889eb2c]
[pkrvmbietmlfzoi:07780] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f785884527e]
[pkrvmbietmlfzoi:07780] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f78588288ff]
[pkrvmbietmlfzoi:07780] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7858ca5ff5]
[pkrvmbietmlfzoi:07780] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7858cbb0da]
[pkrvmbietmlfzoi:07780] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7858ca5a55]
[pkrvmbietmlfzoi:07780] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7858ca5a6f]
[pkrvmbietmlfzoi:07780] [ 8] plumed_master(+0x146dd)[0x55f987ea96dd]
[pkrvmbietmlfzoi:07780] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f785882a1ca]
[pkrvmbietmlfzoi:07780] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f785882a28b]
[pkrvmbietmlfzoi:07780] [11] plumed_master(+0x15365)[0x55f987eaa365]
[pkrvmbietmlfzoi:07780] *** End of error message ***
</pre>
{% endraw %}
