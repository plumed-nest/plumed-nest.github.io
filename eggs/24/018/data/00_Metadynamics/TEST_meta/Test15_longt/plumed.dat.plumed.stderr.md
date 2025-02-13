**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test15_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az1280-696:05696] *** Process received signal ***
[fv-az1280-696:05696] Signal: Aborted (6)
[fv-az1280-696:05696] Signal code:  (-6)
[fv-az1280-696:05696] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7b10245330]
[fv-az1280-696:05696] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7b1029eb2c]
[fv-az1280-696:05696] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7b1024527e]
[fv-az1280-696:05696] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7b102288ff]
[fv-az1280-696:05696] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7b106a5ff5]
[fv-az1280-696:05696] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7b106bb0da]
[fv-az1280-696:05696] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7b106a5a55]
[fv-az1280-696:05696] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7b106a5a6f]
[fv-az1280-696:05696] [ 8] plumed(+0x146dd)[0x560e277d86dd]
[fv-az1280-696:05696] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7b1022a1ca]
[fv-az1280-696:05696] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7b1022a28b]
[fv-az1280-696:05696] [11] plumed(+0x15365)[0x560e277d9365]
[fv-az1280-696:05696] *** End of error message ***
</pre>
{% endraw %}
