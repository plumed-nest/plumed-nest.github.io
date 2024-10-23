**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w14-s4.116/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[fv-az585-767:07563] *** Process received signal ***
[fv-az585-767:07563] Signal: Aborted (6)
[fv-az585-767:07563] Signal code:  (-6)
[fv-az585-767:07563] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x42520)[0x7f18bf042520]
[fv-az585-767:07563] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x12c)[0x7f18bf0969fc]
[fv-az585-767:07563] [ 2] /lib/x86_64-linux-gnu/libc.so.6(raise+0x16)[0x7f18bf042476]
[fv-az585-767:07563] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xd3)[0x7f18bf0287f3]
[fv-az585-767:07563] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa2b9e)[0x7f18bf4a2b9e]
[fv-az585-767:07563] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae20c)[0x7f18bf4ae20c]
[fv-az585-767:07563] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xae277)[0x7f18bf4ae277]
[fv-az585-767:07563] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(__cxa_rethrow+0x4b)[0x7f18bf4ae52b]
[fv-az585-767:07563] [ 8] plumed(+0x14254)[0x5629199f1254]
[fv-az585-767:07563] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x29d90)[0x7f18bf029d90]
[fv-az585-767:07563] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x80)[0x7f18bf029e40]
[fv-az585-767:07563] [11] plumed(+0x14eb5)[0x5629199f1eb5]
[fv-az585-767:07563] *** End of error message ***
</pre>
{% endraw %}
