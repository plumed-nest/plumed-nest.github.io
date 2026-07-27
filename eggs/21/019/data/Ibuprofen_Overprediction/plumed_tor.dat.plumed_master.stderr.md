**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_tor.dat   
Download: [zipped raw stdout](plumed_tor.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed_tor.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS141=9314,9319,9310,9313" is not known.
[runnervmvrwv9:08929] *** Process received signal ***
[runnervmvrwv9:08929] Signal: Aborted (6)
[runnervmvrwv9:08929] Signal code:  (-6)
[runnervmvrwv9:08929] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7ff12e245330]
[runnervmvrwv9:08929] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7ff12e29eb2c]
[runnervmvrwv9:08929] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7ff12e24527e]
[runnervmvrwv9:08929] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7ff12e2288ff]
[runnervmvrwv9:08929] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7ff12e6a5ff5]
[runnervmvrwv9:08929] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7ff12e6bb0da]
[runnervmvrwv9:08929] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7ff12e6a5a55]
[runnervmvrwv9:08929] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7ff12e6a5a6f]
[runnervmvrwv9:08929] [ 8] plumed_master(+0x146dd)[0x56538f62c6dd]
[runnervmvrwv9:08929] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7ff12e22a1ca]
[runnervmvrwv9:08929] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7ff12e22a28b]
[runnervmvrwv9:08929] [11] plumed_master(+0x15365)[0x56538f62d365]
[runnervmvrwv9:08929] *** End of error message ***
</pre>
{% endraw %}
