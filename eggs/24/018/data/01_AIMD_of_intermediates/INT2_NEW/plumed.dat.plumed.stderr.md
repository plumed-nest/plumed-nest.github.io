**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2_NEW/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1267-279:61330] *** Process received signal ***
[fv-az1267-279:61330] Signal: Aborted (6)
[fv-az1267-279:61330] Signal code:  (-6)
[fv-az1267-279:61330] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f981f845330]
[fv-az1267-279:61330] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f981f89eb2c]
[fv-az1267-279:61330] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f981f84527e]
[fv-az1267-279:61330] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f981f8288ff]
[fv-az1267-279:61330] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f981fca5ff5]
[fv-az1267-279:61330] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f981fcbb0da]
[fv-az1267-279:61330] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f981fca5a55]
[fv-az1267-279:61330] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f981fca5a6f]
[fv-az1267-279:61330] [ 8] plumed(+0x146dd)[0x556bed6416dd]
[fv-az1267-279:61330] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f981f82a1ca]
[fv-az1267-279:61330] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f981f82a28b]
[fv-az1267-279:61330] [11] plumed(+0x15365)[0x556bed642365]
[fv-az1267-279:61330] *** End of error message ***
</pre>
{% endraw %}
