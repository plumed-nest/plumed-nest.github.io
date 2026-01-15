**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w27-s6.924/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmtnos:37416] *** Process received signal ***
[runnervmmtnos:37416] Signal: Aborted (6)
[runnervmmtnos:37416] Signal code:  (-6)
[runnervmmtnos:37416] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f884ba45330]
[runnervmmtnos:37416] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f884ba9eb2c]
[runnervmmtnos:37416] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f884ba4527e]
[runnervmmtnos:37416] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f884ba288ff]
[runnervmmtnos:37416] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f884bea5ff5]
[runnervmmtnos:37416] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f884bebb0da]
[runnervmmtnos:37416] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f884bea5a55]
[runnervmmtnos:37416] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f884bea5a6f]
[runnervmmtnos:37416] [ 8] plumed(+0x146dd)[0x55af30b0f6dd]
[runnervmmtnos:37416] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f884ba2a1ca]
[runnervmmtnos:37416] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f884ba2a28b]
[runnervmmtnos:37416] [11] plumed(+0x15365)[0x55af30b10365]
[runnervmmtnos:37416] *** End of error message ***
</pre>
{% endraw %}
