**Project ID:** [plumID:19.046]({{ '/' | absolute_url }}eggs/19/046/)  
Stderr for source:  PLUMED_FM/plumed_FM.dat   
Download: [zipped raw stdout](plumed_FM.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_FM.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "FPS" is not known.
[runnervmw9dnm:11645] *** Process received signal ***
[runnervmw9dnm:11645] Signal: Aborted (6)
[runnervmw9dnm:11645] Signal code:  (-6)
[runnervmw9dnm:11645] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fb3d6645330]
[runnervmw9dnm:11645] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fb3d669eb2c]
[runnervmw9dnm:11645] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fb3d664527e]
[runnervmw9dnm:11645] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fb3d66288ff]
[runnervmw9dnm:11645] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fb3d6aa5ff5]
[runnervmw9dnm:11645] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fb3d6abb0da]
[runnervmw9dnm:11645] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fb3d6aa5a55]
[runnervmw9dnm:11645] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fb3d6aa5a6f]
[runnervmw9dnm:11645] [ 8] plumed_master(+0x146dd)[0x5645a357f6dd]
[runnervmw9dnm:11645] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fb3d662a1ca]
[runnervmw9dnm:11645] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fb3d662a28b]
[runnervmw9dnm:11645] [11] plumed_master(+0x15365)[0x5645a3580365]
[runnervmw9dnm:11645] *** End of error message ***
</pre>
{% endraw %}
