**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[pkrvmbietmlfzoi:08773] *** Process received signal ***
[pkrvmbietmlfzoi:08773] Signal: Aborted (6)
[pkrvmbietmlfzoi:08773] Signal code:  (-6)
[pkrvmbietmlfzoi:08773] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7e83c45330]
[pkrvmbietmlfzoi:08773] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7e83c9eb2c]
[pkrvmbietmlfzoi:08773] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7e83c4527e]
[pkrvmbietmlfzoi:08773] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7e83c288ff]
[pkrvmbietmlfzoi:08773] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7e840a5ff5]
[pkrvmbietmlfzoi:08773] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7e840bb0da]
[pkrvmbietmlfzoi:08773] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7e840a5a55]
[pkrvmbietmlfzoi:08773] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7e840a5a6f]
[pkrvmbietmlfzoi:08773] [ 8] plumed(+0x146dd)[0x55a64e24f6dd]
[pkrvmbietmlfzoi:08773] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7e83c2a1ca]
[pkrvmbietmlfzoi:08773] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7e83c2a28b]
[pkrvmbietmlfzoi:08773] [11] plumed(+0x15365)[0x55a64e250365]
[pkrvmbietmlfzoi:08773] *** End of error message ***
</pre>
{% endraw %}
