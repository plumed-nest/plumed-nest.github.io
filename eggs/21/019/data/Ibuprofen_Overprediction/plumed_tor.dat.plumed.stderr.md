**Project ID:** [plumID:21.019]({{ '/' | absolute_url }}eggs/21/019/)  
Stderr for source:  Ibuprofen_Overprediction/plumed_tor.dat   
Download: [zipped raw stdout](plumed_tor.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed_tor.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "ATOMS141=9314,9319,9310,9313" is not known.
[runnervmvrwv9:08913] *** Process received signal ***
[runnervmvrwv9:08913] Signal: Aborted (6)
[runnervmvrwv9:08913] Signal code:  (-6)
[runnervmvrwv9:08913] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f7e92e45330]
[runnervmvrwv9:08913] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f7e92e9eb2c]
[runnervmvrwv9:08913] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f7e92e4527e]
[runnervmvrwv9:08913] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f7e92e288ff]
[runnervmvrwv9:08913] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f7e932a5ff5]
[runnervmvrwv9:08913] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f7e932bb0da]
[runnervmvrwv9:08913] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f7e932a5a55]
[runnervmvrwv9:08913] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f7e932a5a6f]
[runnervmvrwv9:08913] [ 8] plumed(+0x146dd)[0x56471b3ad6dd]
[runnervmvrwv9:08913] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f7e92e2a1ca]
[runnervmvrwv9:08913] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f7e92e2a28b]
[runnervmvrwv9:08913] [11] plumed(+0x15365)[0x56471b3ae365]
[runnervmvrwv9:08913] *** End of error message ***
</pre>
{% endraw %}
