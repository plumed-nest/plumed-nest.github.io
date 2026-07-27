**Project ID:** [plumID:24.018]({{ '/' | absolute_url }}eggs/24/018/)  
Stderr for source:  01_AIMD_of_intermediates/INT2_Cyanomethanolate_and_Amoniac/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "HILLS" is not known.
[runnervmvrwv9:05937] *** Process received signal ***
[runnervmvrwv9:05937] Signal: Aborted (6)
[runnervmvrwv9:05937] Signal code:  (-6)
[runnervmvrwv9:05937] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f97b4e45330]
[runnervmvrwv9:05937] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f97b4e9eb2c]
[runnervmvrwv9:05937] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f97b4e4527e]
[runnervmvrwv9:05937] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f97b4e288ff]
[runnervmvrwv9:05937] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f97b52a5ff5]
[runnervmvrwv9:05937] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f97b52bb0da]
[runnervmvrwv9:05937] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f97b52a5a55]
[runnervmvrwv9:05937] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f97b52a5a6f]
[runnervmvrwv9:05937] [ 8] plumed_master(+0x146dd)[0x55bbee5c26dd]
[runnervmvrwv9:05937] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f97b4e2a1ca]
[runnervmvrwv9:05937] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f97b4e2a28b]
[runnervmvrwv9:05937] [11] plumed_master(+0x15365)[0x55bbee5c3365]
[runnervmvrwv9:05937] *** End of error message ***
</pre>
{% endraw %}
