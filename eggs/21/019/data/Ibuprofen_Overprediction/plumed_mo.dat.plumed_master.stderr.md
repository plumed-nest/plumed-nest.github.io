**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_mo.dat   
Download: [zipped raw stdout](plumed_mo.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_mo.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS285=9378,9382" is not known.
[runnervmvrwv9:08878] *** Process received signal ***
[runnervmvrwv9:08878] Signal: Aborted (6)
[runnervmvrwv9:08878] Signal code:  (-6)
[runnervmvrwv9:08878] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fbacc245330]
[runnervmvrwv9:08878] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fbacc29eb2c]
[runnervmvrwv9:08878] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fbacc24527e]
[runnervmvrwv9:08878] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fbacc2288ff]
[runnervmvrwv9:08878] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fbacc6a5ff5]
[runnervmvrwv9:08878] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fbacc6bb0da]
[runnervmvrwv9:08878] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fbacc6a5a55]
[runnervmvrwv9:08878] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fbacc6a5a6f]
[runnervmvrwv9:08878] [ 8] plumed_master(+0x146dd)[0x55cf5d4cf6dd]
[runnervmvrwv9:08878] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fbacc22a1ca]
[runnervmvrwv9:08878] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fbacc22a28b]
[runnervmvrwv9:08878] [11] plumed_master(+0x15365)[0x55cf5d4d0365]
[runnervmvrwv9:08878] *** End of error message ***
</pre>
{% endraw %}
