**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w14-s4.116/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervm76f27:09650] *** Process received signal ***
[runnervm76f27:09650] Signal: Aborted (6)
[runnervm76f27:09650] Signal code:  (-6)
[runnervm76f27:09650] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb6dc845330]
[runnervm76f27:09650] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb6dc89ec0c]
[runnervm76f27:09650] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb6dc84527e]
[runnervm76f27:09650] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb6dc8288ff]
[runnervm76f27:09650] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb6dcca5ff5]
[runnervm76f27:09650] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb6dccbb0da]
[runnervm76f27:09650] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb6dcca5a55]
[runnervm76f27:09650] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb6dcca5a6f]
[runnervm76f27:09650] [ 8] plumed_master(+0x146dd)[0x5585c47826dd]
[runnervm76f27:09650] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb6dc82a1ca]
[runnervm76f27:09650] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb6dc82a28b]
[runnervm76f27:09650] [11] plumed_master(+0x15365)[0x5585c4783365]
[runnervm76f27:09650] *** End of error message ***
</pre>
{% endraw %}
