**Project ID:** [plumID:23.032]({{ '/' | absolute_url }}eggs/23/032/)  
Stderr for source:  pt/plumedpt.dat   
Download: [zipped raw stdout](plumedpt.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumedpt.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTORCH_MODEL_CV" is not known.
[pkrvmbietmlfzoi:07587] *** Process received signal ***
[pkrvmbietmlfzoi:07587] Signal: Aborted (6)
[pkrvmbietmlfzoi:07587] Signal code:  (-6)
[pkrvmbietmlfzoi:07587] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f72dde45330]
[pkrvmbietmlfzoi:07587] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f72dde9eb2c]
[pkrvmbietmlfzoi:07587] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f72dde4527e]
[pkrvmbietmlfzoi:07587] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f72dde288ff]
[pkrvmbietmlfzoi:07587] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f72de2a5ff5]
[pkrvmbietmlfzoi:07587] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f72de2bb0da]
[pkrvmbietmlfzoi:07587] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f72de2a5a55]
[pkrvmbietmlfzoi:07587] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f72de2a5a6f]
[pkrvmbietmlfzoi:07587] [ 8] plumed(+0x146dd)[0x55e5f7e446dd]
[pkrvmbietmlfzoi:07587] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f72dde2a1ca]
[pkrvmbietmlfzoi:07587] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f72dde2a28b]
[pkrvmbietmlfzoi:07587] [11] plumed(+0x15365)[0x55e5f7e45365]
[pkrvmbietmlfzoi:07587] *** End of error message ***
</pre>
{% endraw %}
