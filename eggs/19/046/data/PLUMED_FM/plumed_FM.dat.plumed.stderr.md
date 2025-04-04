**Project ID:** [plumID:19.046]({{ '/' | absolute_url }}eggs/19/046/)  
Stderr for source:  PLUMED_FM/plumed_FM.dat   
Download: [zipped raw stdout](plumed_FM.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_FM.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "FPS" is not known.
[fv-az1719-476:13630] *** Process received signal ***
[fv-az1719-476:13630] Signal: Aborted (6)
[fv-az1719-476:13630] Signal code:  (-6)
[fv-az1719-476:13630] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa138c45330]
[fv-az1719-476:13630] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa138c9eb2c]
[fv-az1719-476:13630] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa138c4527e]
[fv-az1719-476:13630] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa138c288ff]
[fv-az1719-476:13630] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa1390a5ff5]
[fv-az1719-476:13630] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa1390bb0da]
[fv-az1719-476:13630] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa1390a5a55]
[fv-az1719-476:13630] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa1390a5a6f]
[fv-az1719-476:13630] [ 8] plumed(+0x146dd)[0x560575eeb6dd]
[fv-az1719-476:13630] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa138c2a1ca]
[fv-az1719-476:13630] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa138c2a28b]
[fv-az1719-476:13630] [11] plumed(+0x15365)[0x560575eec365]
[fv-az1719-476:13630] *** End of error message ***
</pre>
{% endraw %}
