**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w24-s6.276/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmmtnos:37263] *** Process received signal ***
[runnervmmtnos:37263] Signal: Aborted (6)
[runnervmmtnos:37263] Signal code:  (-6)
[runnervmmtnos:37263] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff5dba45330]
[runnervmmtnos:37263] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff5dba9eb2c]
[runnervmmtnos:37263] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff5dba4527e]
[runnervmmtnos:37263] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff5dba288ff]
[runnervmmtnos:37263] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff5dbea5ff5]
[runnervmmtnos:37263] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff5dbebb0da]
[runnervmmtnos:37263] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff5dbea5a55]
[runnervmmtnos:37263] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff5dbea5a6f]
[runnervmmtnos:37263] [ 8] plumed(+0x146dd)[0x55b741e1f6dd]
[runnervmmtnos:37263] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff5dba2a1ca]
[runnervmmtnos:37263] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff5dba2a28b]
[runnervmmtnos:37263] [11] plumed(+0x15365)[0x55b741e20365]
[runnervmmtnos:37263] *** End of error message ***
</pre>
{% endraw %}
