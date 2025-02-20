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
[fv-az1444-322:05937] *** Process received signal ***
[fv-az1444-322:05937] Signal: Aborted (6)
[fv-az1444-322:05937] Signal code:  (-6)
[fv-az1444-322:05937] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fd0dc245330]
[fv-az1444-322:05937] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fd0dc29eb2c]
[fv-az1444-322:05937] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fd0dc24527e]
[fv-az1444-322:05937] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fd0dc2288ff]
[fv-az1444-322:05937] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fd0dc6a5ff5]
[fv-az1444-322:05937] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fd0dc6bb0da]
[fv-az1444-322:05937] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fd0dc6a5a55]
[fv-az1444-322:05937] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fd0dc6a5a6f]
[fv-az1444-322:05937] [ 8] plumed(+0x146dd)[0x560b3dda26dd]
[fv-az1444-322:05937] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fd0dc22a1ca]
[fv-az1444-322:05937] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fd0dc22a28b]
[fv-az1444-322:05937] [11] plumed(+0x15365)[0x560b3dda3365]
[fv-az1444-322:05937] *** End of error message ***
</pre>
{% endraw %}
