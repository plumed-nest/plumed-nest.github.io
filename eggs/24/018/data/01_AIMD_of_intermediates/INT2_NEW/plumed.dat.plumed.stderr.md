**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2_NEW/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmvrwv9:05973] *** Process received signal ***
[runnervmvrwv9:05973] Signal: Aborted (6)
[runnervmvrwv9:05973] Signal code:  (-6)
[runnervmvrwv9:05973] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f067f045330]
[runnervmvrwv9:05973] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f067f09eb2c]
[runnervmvrwv9:05973] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f067f04527e]
[runnervmvrwv9:05973] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f067f0288ff]
[runnervmvrwv9:05973] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f067f4a5ff5]
[runnervmvrwv9:05973] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f067f4bb0da]
[runnervmvrwv9:05973] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f067f4a5a55]
[runnervmvrwv9:05973] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f067f4a5a6f]
[runnervmvrwv9:05973] [ 8] plumed(+0x146dd)[0x560282eba6dd]
[runnervmvrwv9:05973] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f067f02a1ca]
[runnervmvrwv9:05973] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f067f02a28b]
[runnervmvrwv9:05973] [11] plumed(+0x15365)[0x560282ebb365]
[runnervmvrwv9:05973] *** End of error message ***
</pre>
{% endraw %}
