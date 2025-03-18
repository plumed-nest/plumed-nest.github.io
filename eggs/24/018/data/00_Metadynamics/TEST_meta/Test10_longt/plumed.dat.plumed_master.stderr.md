**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test10_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1267-279:60620] *** Process received signal ***
[fv-az1267-279:60620] Signal: Aborted (6)
[fv-az1267-279:60620] Signal code:  (-6)
[fv-az1267-279:60620] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f1469c45330]
[fv-az1267-279:60620] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f1469c9eb2c]
[fv-az1267-279:60620] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f1469c4527e]
[fv-az1267-279:60620] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f1469c288ff]
[fv-az1267-279:60620] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f146a0a5ff5]
[fv-az1267-279:60620] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f146a0bb0da]
[fv-az1267-279:60620] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f146a0a5a55]
[fv-az1267-279:60620] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f146a0a5a6f]
[fv-az1267-279:60620] [ 8] plumed_master(+0x146dd)[0x562f2b38b6dd]
[fv-az1267-279:60620] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f1469c2a1ca]
[fv-az1267-279:60620] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f1469c2a28b]
[fv-az1267-279:60620] [11] plumed_master(+0x15365)[0x562f2b38c365]
[fv-az1267-279:60620] *** End of error message ***
</pre>
{% endraw %}
