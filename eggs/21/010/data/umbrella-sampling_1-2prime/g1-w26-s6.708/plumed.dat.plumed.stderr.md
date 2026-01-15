**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w26-s6.708/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmtnos:37365] *** Process received signal ***
[runnervmmtnos:37365] Signal: Aborted (6)
[runnervmmtnos:37365] Signal code:  (-6)
[runnervmmtnos:37365] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2aca245330]
[runnervmmtnos:37365] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2aca29eb2c]
[runnervmmtnos:37365] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2aca24527e]
[runnervmmtnos:37365] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2aca2288ff]
[runnervmmtnos:37365] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f2aca6a5ff5]
[runnervmmtnos:37365] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f2aca6bb0da]
[runnervmmtnos:37365] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f2aca6a5a55]
[runnervmmtnos:37365] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f2aca6a5a6f]
[runnervmmtnos:37365] [ 8] plumed(+0x146dd)[0x55b2d8b266dd]
[runnervmmtnos:37365] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2aca22a1ca]
[runnervmmtnos:37365] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2aca22a28b]
[runnervmmtnos:37365] [11] plumed(+0x15365)[0x55b2d8b27365]
[runnervmmtnos:37365] *** End of error message ***
</pre>
{% endraw %}
