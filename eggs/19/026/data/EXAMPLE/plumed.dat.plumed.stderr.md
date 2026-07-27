**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[runnervmvrwv9:07507] *** Process received signal ***
[runnervmvrwv9:07507] Signal: Aborted (6)
[runnervmvrwv9:07507] Signal code:  (-6)
[runnervmvrwv9:07507] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7fcee45330]
[runnervmvrwv9:07507] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7fcee9eb2c]
[runnervmvrwv9:07507] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7fcee4527e]
[runnervmvrwv9:07507] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7fcee288ff]
[runnervmvrwv9:07507] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7fcf2a5ff5]
[runnervmvrwv9:07507] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7fcf2bb0da]
[runnervmvrwv9:07507] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7fcf2a5a55]
[runnervmvrwv9:07507] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7fcf2a5a6f]
[runnervmvrwv9:07507] [ 8] plumed(+0x146dd)[0x55fdd1e4b6dd]
[runnervmvrwv9:07507] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7fcee2a1ca]
[runnervmvrwv9:07507] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7fcee2a28b]
[runnervmvrwv9:07507] [11] plumed(+0x15365)[0x55fdd1e4c365]
[runnervmvrwv9:07507] *** End of error message ***
</pre>
{% endraw %}
