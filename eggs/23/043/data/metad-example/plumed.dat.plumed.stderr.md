**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[runnervmkj6or:05285] *** Process received signal ***
[runnervmkj6or:05285] Signal: Aborted (6)
[runnervmkj6or:05285] Signal code:  (-6)
[runnervmkj6or:05285] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fc6e3245330]
[runnervmkj6or:05285] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fc6e329eb2c]
[runnervmkj6or:05285] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fc6e324527e]
[runnervmkj6or:05285] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fc6e32288ff]
[runnervmkj6or:05285] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fc6e36a5ff5]
[runnervmkj6or:05285] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fc6e36bb0da]
[runnervmkj6or:05285] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fc6e36a5a55]
[runnervmkj6or:05285] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fc6e36a5a6f]
[runnervmkj6or:05285] [ 8] plumed(+0x146dd)[0x55de3f25c6dd]
[runnervmkj6or:05285] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fc6e322a1ca]
[runnervmkj6or:05285] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fc6e322a28b]
[runnervmkj6or:05285] [11] plumed(+0x15365)[0x55de3f25d365]
[runnervmkj6or:05285] *** End of error message ***
</pre>
{% endraw %}
