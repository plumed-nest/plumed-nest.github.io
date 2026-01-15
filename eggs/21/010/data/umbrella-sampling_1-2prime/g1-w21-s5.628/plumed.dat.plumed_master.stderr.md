**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w21-s5.628/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmtnos:37126] *** Process received signal ***
[runnervmmtnos:37126] Signal: Aborted (6)
[runnervmmtnos:37126] Signal code:  (-6)
[runnervmmtnos:37126] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3516c45330]
[runnervmmtnos:37126] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3516c9eb2c]
[runnervmmtnos:37126] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3516c4527e]
[runnervmmtnos:37126] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3516c288ff]
[runnervmmtnos:37126] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f35170a5ff5]
[runnervmmtnos:37126] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f35170bb0da]
[runnervmmtnos:37126] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f35170a5a55]
[runnervmmtnos:37126] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f35170a5a6f]
[runnervmmtnos:37126] [ 8] plumed_master(+0x146dd)[0x5569fe51f6dd]
[runnervmmtnos:37126] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3516c2a1ca]
[runnervmmtnos:37126] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3516c2a28b]
[runnervmmtnos:37126] [11] plumed_master(+0x15365)[0x5569fe520365]
[runnervmmtnos:37126] *** End of error message ***
</pre>
{% endraw %}
