**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w20-s5.412/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmtnos:37059] *** Process received signal ***
[runnervmmtnos:37059] Signal: Aborted (6)
[runnervmmtnos:37059] Signal code:  (-6)
[runnervmmtnos:37059] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8d91445330]
[runnervmmtnos:37059] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8d9149eb2c]
[runnervmmtnos:37059] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8d9144527e]
[runnervmmtnos:37059] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8d914288ff]
[runnervmmtnos:37059] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8d918a5ff5]
[runnervmmtnos:37059] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8d918bb0da]
[runnervmmtnos:37059] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8d918a5a55]
[runnervmmtnos:37059] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8d918a5a6f]
[runnervmmtnos:37059] [ 8] plumed(+0x146dd)[0x56119c42d6dd]
[runnervmmtnos:37059] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8d9142a1ca]
[runnervmmtnos:37059] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8d9142a28b]
[runnervmmtnos:37059] [11] plumed(+0x15365)[0x56119c42e365]
[runnervmmtnos:37059] *** End of error message ***
</pre>
{% endraw %}
