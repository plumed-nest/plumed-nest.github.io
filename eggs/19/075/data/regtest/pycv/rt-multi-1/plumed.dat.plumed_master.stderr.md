**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-multi-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[pkrvmbietmlfzoi:09766] *** Process received signal ***
[pkrvmbietmlfzoi:09766] Signal: Aborted (6)
[pkrvmbietmlfzoi:09766] Signal code:  (-6)
[pkrvmbietmlfzoi:09766] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f538a245330]
[pkrvmbietmlfzoi:09766] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f538a29eb2c]
[pkrvmbietmlfzoi:09766] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f538a24527e]
[pkrvmbietmlfzoi:09766] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f538a2288ff]
[pkrvmbietmlfzoi:09766] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f538a6a5ff5]
[pkrvmbietmlfzoi:09766] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f538a6bb0da]
[pkrvmbietmlfzoi:09766] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f538a6a5a55]
[pkrvmbietmlfzoi:09766] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f538a6a5a6f]
[pkrvmbietmlfzoi:09766] [ 8] plumed_master(+0x146dd)[0x561766f6f6dd]
[pkrvmbietmlfzoi:09766] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f538a22a1ca]
[pkrvmbietmlfzoi:09766] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f538a22a28b]
[pkrvmbietmlfzoi:09766] [11] plumed_master(+0x15365)[0x561766f70365]
[pkrvmbietmlfzoi:09766] *** End of error message ***
</pre>
{% endraw %}
