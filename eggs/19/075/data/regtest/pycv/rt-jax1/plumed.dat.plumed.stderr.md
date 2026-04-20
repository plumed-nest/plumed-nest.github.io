**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-jax1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre>
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmeorf1:09799] *** Process received signal ***
[runnervmeorf1:09799] Signal: Aborted (6)
[runnervmeorf1:09799] Signal code:  (-6)
[runnervmeorf1:09799] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f34bfc45330]
[runnervmeorf1:09799] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f34bfc9eb2c]
[runnervmeorf1:09799] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f34bfc4527e]
[runnervmeorf1:09799] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f34bfc288ff]
[runnervmeorf1:09799] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f34c00a5ff5]
[runnervmeorf1:09799] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f34c00bb0da]
[runnervmeorf1:09799] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f34c00a5a55]
[runnervmeorf1:09799] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f34c00a5a6f]
[runnervmeorf1:09799] [ 8] plumed(+0x146dd)[0x558c5a5e46dd]
[runnervmeorf1:09799] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f34bfc2a1ca]
[runnervmeorf1:09799] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f34bfc2a28b]
[runnervmeorf1:09799] [11] plumed(+0x15365)[0x558c5a5e5365]
[runnervmeorf1:09799] *** End of error message ***
</pre>
{% endraw %}
