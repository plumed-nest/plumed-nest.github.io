**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test10_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1267-279:60604] *** Process received signal ***
[fv-az1267-279:60604] Signal: Aborted (6)
[fv-az1267-279:60604] Signal code:  (-6)
[fv-az1267-279:60604] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f15fb845330]
[fv-az1267-279:60604] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f15fb89eb2c]
[fv-az1267-279:60604] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f15fb84527e]
[fv-az1267-279:60604] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f15fb8288ff]
[fv-az1267-279:60604] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f15fbca5ff5]
[fv-az1267-279:60604] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f15fbcbb0da]
[fv-az1267-279:60604] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f15fbca5a55]
[fv-az1267-279:60604] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f15fbca5a6f]
[fv-az1267-279:60604] [ 8] plumed(+0x146dd)[0x55d1eefe46dd]
[fv-az1267-279:60604] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f15fb82a1ca]
[fv-az1267-279:60604] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f15fb82a28b]
[fv-az1267-279:60604] [11] plumed(+0x15365)[0x55d1eefe5365]
[fv-az1267-279:60604] *** End of error message ***
</pre>
{% endraw %}
