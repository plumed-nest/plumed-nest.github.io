**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test13_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1267-279:60774] *** Process received signal ***
[fv-az1267-279:60774] Signal: Aborted (6)
[fv-az1267-279:60774] Signal code:  (-6)
[fv-az1267-279:60774] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa02f245330]
[fv-az1267-279:60774] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa02f29eb2c]
[fv-az1267-279:60774] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa02f24527e]
[fv-az1267-279:60774] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa02f2288ff]
[fv-az1267-279:60774] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa02f6a5ff5]
[fv-az1267-279:60774] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa02f6bb0da]
[fv-az1267-279:60774] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa02f6a5a55]
[fv-az1267-279:60774] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa02f6a5a6f]
[fv-az1267-279:60774] [ 8] plumed_master(+0x146dd)[0x55e3b7e566dd]
[fv-az1267-279:60774] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa02f22a1ca]
[fv-az1267-279:60774] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa02f22a28b]
[fv-az1267-279:60774] [11] plumed_master(+0x15365)[0x55e3b7e57365]
[fv-az1267-279:60774] *** End of error message ***
</pre>
{% endraw %}
