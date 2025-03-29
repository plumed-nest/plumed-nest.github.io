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
[fv-az1701-508:61235] *** Process received signal ***
[fv-az1701-508:61235] Signal: Aborted (6)
[fv-az1701-508:61235] Signal code:  (-6)
[fv-az1701-508:61235] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f48c2245330]
[fv-az1701-508:61235] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f48c229eb2c]
[fv-az1701-508:61235] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f48c224527e]
[fv-az1701-508:61235] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f48c22288ff]
[fv-az1701-508:61235] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f48c26a5ff5]
[fv-az1701-508:61235] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f48c26bb0da]
[fv-az1701-508:61235] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f48c26a5a55]
[fv-az1701-508:61235] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f48c26a5a6f]
[fv-az1701-508:61235] [ 8] plumed(+0x146dd)[0x5654164336dd]
[fv-az1701-508:61235] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f48c222a1ca]
[fv-az1701-508:61235] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f48c222a28b]
[fv-az1701-508:61235] [11] plumed(+0x15365)[0x565416434365]
[fv-az1701-508:61235] *** End of error message ***
</pre>
{% endraw %}
