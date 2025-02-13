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
[fv-az1280-696:05555] *** Process received signal ***
[fv-az1280-696:05555] Signal: Aborted (6)
[fv-az1280-696:05555] Signal code:  (-6)
[fv-az1280-696:05555] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f785b045330]
[fv-az1280-696:05555] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f785b09eb2c]
[fv-az1280-696:05555] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f785b04527e]
[fv-az1280-696:05555] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f785b0288ff]
[fv-az1280-696:05555] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f785b4a5ff5]
[fv-az1280-696:05555] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f785b4bb0da]
[fv-az1280-696:05555] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f785b4a5a55]
[fv-az1280-696:05555] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f785b4a5a6f]
[fv-az1280-696:05555] [ 8] plumed_master(+0x146dd)[0x55f0ed8936dd]
[fv-az1280-696:05555] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f785b02a1ca]
[fv-az1280-696:05555] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f785b02a28b]
[fv-az1280-696:05555] [11] plumed_master(+0x15365)[0x55f0ed894365]
[fv-az1280-696:05555] *** End of error message ***
</pre>
{% endraw %}
