**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[pkrvmbietmlfzoi:08789] *** Process received signal ***
[pkrvmbietmlfzoi:08789] Signal: Aborted (6)
[pkrvmbietmlfzoi:08789] Signal code:  (-6)
[pkrvmbietmlfzoi:08789] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f63c6445330]
[pkrvmbietmlfzoi:08789] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f63c649eb2c]
[pkrvmbietmlfzoi:08789] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f63c644527e]
[pkrvmbietmlfzoi:08789] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f63c64288ff]
[pkrvmbietmlfzoi:08789] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f63c68a5ff5]
[pkrvmbietmlfzoi:08789] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f63c68bb0da]
[pkrvmbietmlfzoi:08789] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f63c68a5a55]
[pkrvmbietmlfzoi:08789] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f63c68a5a6f]
[pkrvmbietmlfzoi:08789] [ 8] plumed_master(+0x146dd)[0x55ed2b7676dd]
[pkrvmbietmlfzoi:08789] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f63c642a1ca]
[pkrvmbietmlfzoi:08789] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f63c642a28b]
[pkrvmbietmlfzoi:08789] [11] plumed_master(+0x15365)[0x55ed2b768365]
[pkrvmbietmlfzoi:08789] *** End of error message ***
</pre>
{% endraw %}
