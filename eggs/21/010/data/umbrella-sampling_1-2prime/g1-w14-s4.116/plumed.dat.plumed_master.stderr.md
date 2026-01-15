**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w14-s4.116/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmtnos:36714] *** Process received signal ***
[runnervmmtnos:36714] Signal: Aborted (6)
[runnervmmtnos:36714] Signal code:  (-6)
[runnervmmtnos:36714] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f6cbc845330]
[runnervmmtnos:36714] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f6cbc89eb2c]
[runnervmmtnos:36714] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f6cbc84527e]
[runnervmmtnos:36714] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f6cbc8288ff]
[runnervmmtnos:36714] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f6cbcca5ff5]
[runnervmmtnos:36714] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f6cbccbb0da]
[runnervmmtnos:36714] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f6cbcca5a55]
[runnervmmtnos:36714] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f6cbcca5a6f]
[runnervmmtnos:36714] [ 8] plumed_master(+0x146dd)[0x55e1d3dc36dd]
[runnervmmtnos:36714] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f6cbc82a1ca]
[runnervmmtnos:36714] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f6cbc82a28b]
[runnervmmtnos:36714] [11] plumed_master(+0x15365)[0x55e1d3dc4365]
[runnervmmtnos:36714] *** End of error message ***
</pre>
{% endraw %}
