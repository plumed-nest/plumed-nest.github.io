**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w10-s3.252/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmtnos:36491] *** Process received signal ***
[runnervmmtnos:36491] Signal: Aborted (6)
[runnervmmtnos:36491] Signal code:  (-6)
[runnervmmtnos:36491] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fa463245330]
[runnervmmtnos:36491] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fa46329eb2c]
[runnervmmtnos:36491] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fa46324527e]
[runnervmmtnos:36491] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fa4632288ff]
[runnervmmtnos:36491] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fa4636a5ff5]
[runnervmmtnos:36491] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fa4636bb0da]
[runnervmmtnos:36491] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fa4636a5a55]
[runnervmmtnos:36491] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fa4636a5a6f]
[runnervmmtnos:36491] [ 8] plumed(+0x146dd)[0x5582a669d6dd]
[runnervmmtnos:36491] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fa46322a1ca]
[runnervmmtnos:36491] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fa46322a28b]
[runnervmmtnos:36491] [11] plumed(+0x15365)[0x5582a669e365]
[runnervmmtnos:36491] *** End of error message ***
</pre>
{% endraw %}
