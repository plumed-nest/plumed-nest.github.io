**Project ID:** [plumID:21.010]({{ '/' | absolute_url }}eggs/21/010/)  
Stderr for source:  umbrella-sampling_1-2prime/g1-w23-s6.060/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmvrwv9:07133] *** Process received signal ***
[runnervmvrwv9:07133] Signal: Aborted (6)
[runnervmvrwv9:07133] Signal code:  (-6)
[runnervmvrwv9:07133] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efe0e245330]
[runnervmvrwv9:07133] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efe0e29eb2c]
[runnervmvrwv9:07133] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efe0e24527e]
[runnervmvrwv9:07133] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efe0e2288ff]
[runnervmvrwv9:07133] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efe0e6a5ff5]
[runnervmvrwv9:07133] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efe0e6bb0da]
[runnervmvrwv9:07133] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efe0e6a5a55]
[runnervmvrwv9:07133] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efe0e6a5a6f]
[runnervmvrwv9:07133] [ 8] plumed(+0x146dd)[0x5623f61916dd]
[runnervmvrwv9:07133] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efe0e22a1ca]
[runnervmvrwv9:07133] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efe0e22a28b]
[runnervmvrwv9:07133] [11] plumed(+0x15365)[0x5623f6192365]
[runnervmvrwv9:07133] *** End of error message ***
</pre>
{% endraw %}
