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
[pkrvmbietmlfzoi:64092] *** Process received signal ***
[pkrvmbietmlfzoi:64092] Signal: Aborted (6)
[pkrvmbietmlfzoi:64092] Signal code:  (-6)
[pkrvmbietmlfzoi:64092] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd549645330]
[pkrvmbietmlfzoi:64092] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd54969eb2c]
[pkrvmbietmlfzoi:64092] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd54964527e]
[pkrvmbietmlfzoi:64092] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd5496288ff]
[pkrvmbietmlfzoi:64092] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd549aa5ff5]
[pkrvmbietmlfzoi:64092] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd549abb0da]
[pkrvmbietmlfzoi:64092] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd549aa5a55]
[pkrvmbietmlfzoi:64092] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd549aa5a6f]
[pkrvmbietmlfzoi:64092] [ 8] plumed(+0x146dd)[0x5654d9d056dd]
[pkrvmbietmlfzoi:64092] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd54962a1ca]
[pkrvmbietmlfzoi:64092] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd54962a28b]
[pkrvmbietmlfzoi:64092] [11] plumed(+0x15365)[0x5654d9d06365]
[pkrvmbietmlfzoi:64092] *** End of error message ***
</pre>
{% endraw %}
