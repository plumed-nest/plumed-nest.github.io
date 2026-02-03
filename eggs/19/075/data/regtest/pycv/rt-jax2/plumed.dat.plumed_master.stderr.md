**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-jax2/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmkj6or:11533] *** Process received signal ***
[runnervmkj6or:11533] Signal: Aborted (6)
[runnervmkj6or:11533] Signal code:  (-6)
[runnervmkj6or:11533] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f29bd445330]
[runnervmkj6or:11533] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f29bd49eb2c]
[runnervmkj6or:11533] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f29bd44527e]
[runnervmkj6or:11533] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f29bd4288ff]
[runnervmkj6or:11533] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f29bd8a5ff5]
[runnervmkj6or:11533] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f29bd8bb0da]
[runnervmkj6or:11533] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f29bd8a5a55]
[runnervmkj6or:11533] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f29bd8a5a6f]
[runnervmkj6or:11533] [ 8] plumed_master(+0x146dd)[0x55f333a3d6dd]
[runnervmkj6or:11533] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f29bd42a1ca]
[runnervmkj6or:11533] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f29bd42a28b]
[runnervmkj6or:11533] [11] plumed_master(+0x15365)[0x55f333a3e365]
[runnervmkj6or:11533] *** End of error message ***
</pre>
{% endraw %}
