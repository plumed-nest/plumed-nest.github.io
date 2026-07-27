**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_mo.dat   
Download: [zipped raw stdout](plumed_mo.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_mo.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS285=9378,9382" is not known.
[runnervmvrwv9:08862] *** Process received signal ***
[runnervmvrwv9:08862] Signal: Aborted (6)
[runnervmvrwv9:08862] Signal code:  (-6)
[runnervmvrwv9:08862] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f540c645330]
[runnervmvrwv9:08862] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f540c69eb2c]
[runnervmvrwv9:08862] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f540c64527e]
[runnervmvrwv9:08862] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f540c6288ff]
[runnervmvrwv9:08862] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f540caa5ff5]
[runnervmvrwv9:08862] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f540cabb0da]
[runnervmvrwv9:08862] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f540caa5a55]
[runnervmvrwv9:08862] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f540caa5a6f]
[runnervmvrwv9:08862] [ 8] plumed(+0x146dd)[0x55e9faa726dd]
[runnervmvrwv9:08862] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f540c62a1ca]
[runnervmvrwv9:08862] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f540c62a28b]
[runnervmvrwv9:08862] [11] plumed(+0x15365)[0x55e9faa73365]
[runnervmvrwv9:08862] *** End of error message ***
</pre>
{% endraw %}
