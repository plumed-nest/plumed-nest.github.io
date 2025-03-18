**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test12_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1267-279:60722] *** Process received signal ***
[fv-az1267-279:60722] Signal: Aborted (6)
[fv-az1267-279:60722] Signal code:  (-6)
[fv-az1267-279:60722] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8e0fe45330]
[fv-az1267-279:60722] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8e0fe9eb2c]
[fv-az1267-279:60722] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8e0fe4527e]
[fv-az1267-279:60722] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8e0fe288ff]
[fv-az1267-279:60722] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8e102a5ff5]
[fv-az1267-279:60722] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8e102bb0da]
[fv-az1267-279:60722] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8e102a5a55]
[fv-az1267-279:60722] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8e102a5a6f]
[fv-az1267-279:60722] [ 8] plumed_master(+0x146dd)[0x5568083f86dd]
[fv-az1267-279:60722] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8e0fe2a1ca]
[fv-az1267-279:60722] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8e0fe2a28b]
[fv-az1267-279:60722] [11] plumed_master(+0x15365)[0x5568083f9365]
[fv-az1267-279:60722] *** End of error message ***
</pre>
{% endraw %}
