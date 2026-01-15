**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[runnervmmtnos:40058] *** Process received signal ***
[runnervmmtnos:40058] Signal: Aborted (6)
[runnervmmtnos:40058] Signal code:  (-6)
[runnervmmtnos:40058] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdcfd445330]
[runnervmmtnos:40058] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdcfd49eb2c]
[runnervmmtnos:40058] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdcfd44527e]
[runnervmmtnos:40058] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdcfd4288ff]
[runnervmmtnos:40058] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdcfd8a5ff5]
[runnervmmtnos:40058] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdcfd8bb0da]
[runnervmmtnos:40058] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdcfd8a5a55]
[runnervmmtnos:40058] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdcfd8a5a6f]
[runnervmmtnos:40058] [ 8] plumed_master(+0x146dd)[0x563e388c76dd]
[runnervmmtnos:40058] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdcfd42a1ca]
[runnervmmtnos:40058] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdcfd42a28b]
[runnervmmtnos:40058] [11] plumed_master(+0x15365)[0x563e388c8365]
[runnervmmtnos:40058] *** End of error message ***
</pre>
{% endraw %}
