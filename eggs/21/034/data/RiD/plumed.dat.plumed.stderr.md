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
[runnervmvrwv9:09489] *** Process received signal ***
[runnervmvrwv9:09489] Signal: Aborted (6)
[runnervmvrwv9:09489] Signal code:  (-6)
[runnervmvrwv9:09489] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7fdc80245330]
[runnervmvrwv9:09489] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7fdc8029eb2c]
[runnervmvrwv9:09489] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7fdc8024527e]
[runnervmvrwv9:09489] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7fdc802288ff]
[runnervmvrwv9:09489] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7fdc806a5ff5]
[runnervmvrwv9:09489] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7fdc806bb0da]
[runnervmvrwv9:09489] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7fdc806a5a55]
[runnervmvrwv9:09489] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7fdc806a5a6f]
[runnervmvrwv9:09489] [ 8] plumed(+0x146dd)[0x55698787b6dd]
[runnervmvrwv9:09489] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7fdc8022a1ca]
[runnervmvrwv9:09489] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7fdc8022a28b]
[runnervmvrwv9:09489] [11] plumed(+0x15365)[0x55698787c365]
[runnervmvrwv9:09489] *** End of error message ***
</pre>
{% endraw %}
