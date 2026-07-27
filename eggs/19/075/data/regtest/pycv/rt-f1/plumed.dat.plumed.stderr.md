**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-f1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONFUNCTION" is not known.
[runnervmvrwv9:10232] *** Process received signal ***
[runnervmvrwv9:10232] Signal: Aborted (6)
[runnervmvrwv9:10232] Signal code:  (-6)
[runnervmvrwv9:10232] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7efd41e45330]
[runnervmvrwv9:10232] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7efd41e9eb2c]
[runnervmvrwv9:10232] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7efd41e4527e]
[runnervmvrwv9:10232] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7efd41e288ff]
[runnervmvrwv9:10232] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7efd422a5ff5]
[runnervmvrwv9:10232] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7efd422bb0da]
[runnervmvrwv9:10232] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7efd422a5a55]
[runnervmvrwv9:10232] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7efd422a5a6f]
[runnervmvrwv9:10232] [ 8] plumed(+0x146dd)[0x55d0fa13b6dd]
[runnervmvrwv9:10232] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7efd41e2a1ca]
[runnervmvrwv9:10232] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7efd41e2a28b]
[runnervmvrwv9:10232] [11] plumed(+0x15365)[0x55d0fa13c365]
[runnervmvrwv9:10232] *** End of error message ***
</pre>
{% endraw %}
