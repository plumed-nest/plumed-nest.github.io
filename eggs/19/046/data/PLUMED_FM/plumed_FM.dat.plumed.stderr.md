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
[fv-az585-767:11360] *** Process received signal ***
[fv-az585-767:11360] Signal: Aborted (6)
[fv-az585-767:11360] Signal code:  (-6)
[fv-az585-767:11360] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7ff5f8642520]
[fv-az585-767:11360] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7ff5f86969fc]
[fv-az585-767:11360] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7ff5f8642476]
[fv-az585-767:11360] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7ff5f86287f3]
[fv-az585-767:11360] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7ff5f8aa2b9e]
[fv-az585-767:11360] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7ff5f8aae20c]
[fv-az585-767:11360] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7ff5f8aae277]
[fv-az585-767:11360] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7ff5f8aae52b]
[fv-az585-767:11360] [ 8] plumed(+0x14254)[0x56539cbfb254]
[fv-az585-767:11360] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7ff5f8629d90]
[fv-az585-767:11360] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7ff5f8629e40]
[fv-az585-767:11360] [11] plumed(+0x14eb5)[0x56539cbfbeb5]
[fv-az585-767:11360] *** End of error message ***
</pre>
{% endraw %}
