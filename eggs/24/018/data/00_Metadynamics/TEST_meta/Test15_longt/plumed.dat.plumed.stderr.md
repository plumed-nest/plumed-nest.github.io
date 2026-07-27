**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test15_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmvrwv9:05508] *** Process received signal ***
[runnervmvrwv9:05508] Signal: Aborted (6)
[runnervmvrwv9:05508] Signal code:  (-6)
[runnervmvrwv9:05508] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f266c245330]
[runnervmvrwv9:05508] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f266c29eb2c]
[runnervmvrwv9:05508] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f266c24527e]
[runnervmvrwv9:05508] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f266c2288ff]
[runnervmvrwv9:05508] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f266c6a5ff5]
[runnervmvrwv9:05508] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f266c6bb0da]
[runnervmvrwv9:05508] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f266c6a5a55]
[runnervmvrwv9:05508] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f266c6a5a6f]
[runnervmvrwv9:05508] [ 8] plumed(+0x146dd)[0x55868c3a46dd]
[runnervmvrwv9:05508] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f266c22a1ca]
[runnervmvrwv9:05508] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f266c22a28b]
[runnervmvrwv9:05508] [11] plumed(+0x15365)[0x55868c3a5365]
[runnervmvrwv9:05508] *** End of error message ***
</pre>
{% endraw %}
