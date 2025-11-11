**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[runnervmw9dnm:11807] *** Process received signal ***
[runnervmw9dnm:11807] Signal: Aborted (6)
[runnervmw9dnm:11807] Signal code:  (-6)
[runnervmw9dnm:11807] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb8e6e45330]
[runnervmw9dnm:11807] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb8e6e9eb2c]
[runnervmw9dnm:11807] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb8e6e4527e]
[runnervmw9dnm:11807] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb8e6e288ff]
[runnervmw9dnm:11807] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb8e72a5ff5]
[runnervmw9dnm:11807] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb8e72bb0da]
[runnervmw9dnm:11807] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb8e72a5a55]
[runnervmw9dnm:11807] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb8e72a5a6f]
[runnervmw9dnm:11807] [ 8] plumed_master(+0x146dd)[0x5637514736dd]
[runnervmw9dnm:11807] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb8e6e2a1ca]
[runnervmw9dnm:11807] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb8e6e2a28b]
[runnervmw9dnm:11807] [11] plumed_master(+0x15365)[0x563751474365]
[runnervmw9dnm:11807] *** End of error message ***
</pre>
{% endraw %}
