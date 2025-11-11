**Project ID:** [plumID:23.043]({{ '/' | absolute_url }}eggs/23/043/)  
Stderr for source:  metad-example/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "SPHERICAL_EXPANSION" is not known.
[runnervmw9dnm:07655] *** Process received signal ***
[runnervmw9dnm:07655] Signal: Aborted (6)
[runnervmw9dnm:07655] Signal code:  (-6)
[runnervmw9dnm:07655] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9585845330]
[runnervmw9dnm:07655] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f958589eb2c]
[runnervmw9dnm:07655] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f958584527e]
[runnervmw9dnm:07655] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f95858288ff]
[runnervmw9dnm:07655] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9585ca5ff5]
[runnervmw9dnm:07655] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9585cbb0da]
[runnervmw9dnm:07655] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9585ca5a55]
[runnervmw9dnm:07655] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9585ca5a6f]
[runnervmw9dnm:07655] [ 8] plumed_master(+0x146dd)[0x55b3c658b6dd]
[runnervmw9dnm:07655] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f958582a1ca]
[runnervmw9dnm:07655] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f958582a28b]
[runnervmw9dnm:07655] [11] plumed_master(+0x15365)[0x55b3c658c365]
[runnervmw9dnm:07655] *** End of error message ***
</pre>
{% endraw %}
