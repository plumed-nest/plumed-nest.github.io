**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[runnervmmtnos:40043] *** Process received signal ***
[runnervmmtnos:40043] Signal: Aborted (6)
[runnervmmtnos:40043] Signal code:  (-6)
[runnervmmtnos:40043] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fe5d6e45330]
[runnervmmtnos:40043] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fe5d6e9eb2c]
[runnervmmtnos:40043] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fe5d6e4527e]
[runnervmmtnos:40043] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fe5d6e288ff]
[runnervmmtnos:40043] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fe5d72a5ff5]
[runnervmmtnos:40043] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fe5d72bb0da]
[runnervmmtnos:40043] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fe5d72a5a55]
[runnervmmtnos:40043] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fe5d72a5a6f]
[runnervmmtnos:40043] [ 8] plumed(+0x146dd)[0x556d10b626dd]
[runnervmmtnos:40043] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fe5d6e2a1ca]
[runnervmmtnos:40043] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fe5d6e2a28b]
[runnervmmtnos:40043] [11] plumed(+0x15365)[0x556d10b63365]
[runnervmmtnos:40043] *** End of error message ***
</pre>
{% endraw %}
