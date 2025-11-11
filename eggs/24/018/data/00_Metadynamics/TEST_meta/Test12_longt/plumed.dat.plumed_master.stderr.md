**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test12_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmw9dnm:06949] *** Process received signal ***
[runnervmw9dnm:06949] Signal: Aborted (6)
[runnervmw9dnm:06949] Signal code:  (-6)
[runnervmw9dnm:06949] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f8d1d645330]
[runnervmw9dnm:06949] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f8d1d69eb2c]
[runnervmw9dnm:06949] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f8d1d64527e]
[runnervmw9dnm:06949] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f8d1d6288ff]
[runnervmw9dnm:06949] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f8d1daa5ff5]
[runnervmw9dnm:06949] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f8d1dabb0da]
[runnervmw9dnm:06949] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f8d1daa5a55]
[runnervmw9dnm:06949] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f8d1daa5a6f]
[runnervmw9dnm:06949] [ 8] plumed_master(+0x146dd)[0x55e9cec8d6dd]
[runnervmw9dnm:06949] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f8d1d62a1ca]
[runnervmw9dnm:06949] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f8d1d62a28b]
[runnervmw9dnm:06949] [11] plumed_master(+0x15365)[0x55e9cec8e365]
[runnervmw9dnm:06949] *** End of error message ***
</pre>
{% endraw %}
