**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "DEEPFE" is not known.
[runnervmmklqx:09550] *** Process received signal ***
[runnervmmklqx:09550] Signal: Aborted (6)
[runnervmmklqx:09550] Signal code:  (-6)
[runnervmmklqx:09550] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f438fc45330]
[runnervmmklqx:09550] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f438fc9eb2c]
[runnervmmklqx:09550] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f438fc4527e]
[runnervmmklqx:09550] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f438fc288ff]
[runnervmmklqx:09550] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f43900a5ff5]
[runnervmmklqx:09550] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f43900bb0da]
[runnervmmklqx:09550] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f43900a5a55]
[runnervmmklqx:09550] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f43900a5a6f]
[runnervmmklqx:09550] [ 8] plumed(+0x146dd)[0x55ac889906dd]
[runnervmmklqx:09550] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f438fc2a1ca]
[runnervmmklqx:09550] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f438fc2a28b]
[runnervmmklqx:09550] [11] plumed(+0x15365)[0x55ac88991365]
[runnervmmklqx:09550] *** End of error message ***
</pre>
{% endraw %}
