**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-jax2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmvrwv9:10387] *** Process received signal ***
[runnervmvrwv9:10387] Signal: Aborted (6)
[runnervmvrwv9:10387] Signal code:  (-6)
[runnervmvrwv9:10387] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f927b445330]
[runnervmvrwv9:10387] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f927b49eb2c]
[runnervmvrwv9:10387] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f927b44527e]
[runnervmvrwv9:10387] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f927b4288ff]
[runnervmvrwv9:10387] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f927b8a5ff5]
[runnervmvrwv9:10387] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f927b8bb0da]
[runnervmvrwv9:10387] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f927b8a5a55]
[runnervmvrwv9:10387] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f927b8a5a6f]
[runnervmvrwv9:10387] [ 8] plumed(+0x146dd)[0x55fe212316dd]
[runnervmvrwv9:10387] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f927b42a1ca]
[runnervmvrwv9:10387] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f927b42a28b]
[runnervmvrwv9:10387] [11] plumed(+0x15365)[0x55fe21232365]
[runnervmvrwv9:10387] *** End of error message ***
</pre>
{% endraw %}
