**Project ID:** [plumID:23.026]({{ '/' | absolute_url }}eggs/23/026/)  
Stderr for source:  plumed_model_pulling.dat   
Download: [zipped raw stdout](plumed_model_pulling.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_model_pulling.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmw9dnm:06338] *** Process received signal ***
[runnervmw9dnm:06338] Signal: Aborted (6)
[runnervmw9dnm:06338] Signal code:  (-6)
[runnervmw9dnm:06338] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f3d68045330]
[runnervmw9dnm:06338] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f3d6809eb2c]
[runnervmw9dnm:06338] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f3d6804527e]
[runnervmw9dnm:06338] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f3d680288ff]
[runnervmw9dnm:06338] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f3d684a5ff5]
[runnervmw9dnm:06338] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f3d684bb0da]
[runnervmw9dnm:06338] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f3d684a5a55]
[runnervmw9dnm:06338] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f3d684a5a6f]
[runnervmw9dnm:06338] [ 8] plumed_master(+0x146dd)[0x55f8001636dd]
[runnervmw9dnm:06338] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f3d6802a1ca]
[runnervmw9dnm:06338] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f3d6802a28b]
[runnervmw9dnm:06338] [11] plumed_master(+0x15365)[0x55f800164365]
[runnervmw9dnm:06338] *** End of error message ***
</pre>
{% endraw %}
