**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-jax1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmkj6or:11482] *** Process received signal ***
[runnervmkj6or:11482] Signal: Aborted (6)
[runnervmkj6or:11482] Signal code:  (-6)
[runnervmkj6or:11482] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f88c7c45330]
[runnervmkj6or:11482] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f88c7c9eb2c]
[runnervmkj6or:11482] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f88c7c4527e]
[runnervmkj6or:11482] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f88c7c288ff]
[runnervmkj6or:11482] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f88c80a5ff5]
[runnervmkj6or:11482] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f88c80bb0da]
[runnervmkj6or:11482] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f88c80a5a55]
[runnervmkj6or:11482] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f88c80a5a6f]
[runnervmkj6or:11482] [ 8] plumed_master(+0x146dd)[0x56047cc6a6dd]
[runnervmkj6or:11482] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f88c7c2a1ca]
[runnervmkj6or:11482] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f88c7c2a28b]
[runnervmkj6or:11482] [11] plumed_master(+0x15365)[0x56047cc6b365]
[runnervmkj6or:11482] *** End of error message ***
</pre>
{% endraw %}
