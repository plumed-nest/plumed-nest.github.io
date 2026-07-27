**Project ID:** [plumID:19.026]({{ '/' | absolute_url }}eggs/19/026/)  
Stderr for source:  EXAMPLE/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HBOND_COORD" is not known.
[runnervmvrwv9:07522] *** Process received signal ***
[runnervmvrwv9:07522] Signal: Aborted (6)
[runnervmvrwv9:07522] Signal code:  (-6)
[runnervmvrwv9:07522] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f9b83e45330]
[runnervmvrwv9:07522] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f9b83e9eb2c]
[runnervmvrwv9:07522] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f9b83e4527e]
[runnervmvrwv9:07522] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f9b83e288ff]
[runnervmvrwv9:07522] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f9b842a5ff5]
[runnervmvrwv9:07522] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f9b842bb0da]
[runnervmvrwv9:07522] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f9b842a5a55]
[runnervmvrwv9:07522] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f9b842a5a6f]
[runnervmvrwv9:07522] [ 8] plumed_master(+0x146dd)[0x556b77e9f6dd]
[runnervmvrwv9:07522] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f9b83e2a1ca]
[runnervmvrwv9:07522] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f9b83e2a28b]
[runnervmvrwv9:07522] [11] plumed_master(+0x15365)[0x556b77ea0365]
[runnervmvrwv9:07522] *** End of error message ***
</pre>
{% endraw %}
