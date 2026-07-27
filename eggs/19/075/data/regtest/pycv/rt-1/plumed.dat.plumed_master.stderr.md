**Project ID:** [plumID:19.075]({{ '/' | absolute_url }}eggs/19/075/)  
Stderr for source:  regtest/pycv/rt-1/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "PYTHONCV" is not known.
[runnervmvrwv9:10090] *** Process received signal ***
[runnervmvrwv9:10090] Signal: Aborted (6)
[runnervmvrwv9:10090] Signal code:  (-6)
[runnervmvrwv9:10090] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f05c4445330]
[runnervmvrwv9:10090] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f05c449eb2c]
[runnervmvrwv9:10090] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f05c444527e]
[runnervmvrwv9:10090] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f05c44288ff]
[runnervmvrwv9:10090] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f05c48a5ff5]
[runnervmvrwv9:10090] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f05c48bb0da]
[runnervmvrwv9:10090] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f05c48a5a55]
[runnervmvrwv9:10090] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f05c48a5a6f]
[runnervmvrwv9:10090] [ 8] plumed_master(+0x146dd)[0x5612b22656dd]
[runnervmvrwv9:10090] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f05c442a1ca]
[runnervmvrwv9:10090] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f05c442a28b]
[runnervmvrwv9:10090] [11] plumed_master(+0x15365)[0x5612b2266365]
[runnervmvrwv9:10090] *** End of error message ***
</pre>
{% endraw %}
