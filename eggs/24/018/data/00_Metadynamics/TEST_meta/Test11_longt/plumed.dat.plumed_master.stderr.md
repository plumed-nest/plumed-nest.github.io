**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  00_Metadynamics/TEST_meta/Test11_longt/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmw9dnm:06895] *** Process received signal ***
[runnervmw9dnm:06895] Signal: Aborted (6)
[runnervmw9dnm:06895] Signal code:  (-6)
[runnervmw9dnm:06895] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f89dac45330]
[runnervmw9dnm:06895] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f89dac9eb2c]
[runnervmw9dnm:06895] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f89dac4527e]
[runnervmw9dnm:06895] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f89dac288ff]
[runnervmw9dnm:06895] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f89db0a5ff5]
[runnervmw9dnm:06895] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f89db0bb0da]
[runnervmw9dnm:06895] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f89db0a5a55]
[runnervmw9dnm:06895] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f89db0a5a6f]
[runnervmw9dnm:06895] [ 8] plumed_master(+0x146dd)[0x5589b89776dd]
[runnervmw9dnm:06895] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f89dac2a1ca]
[runnervmw9dnm:06895] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f89dac2a28b]
[runnervmw9dnm:06895] [11] plumed_master(+0x15365)[0x5589b8978365]
[runnervmw9dnm:06895] *** End of error message ***
</pre>
{% endraw %}
