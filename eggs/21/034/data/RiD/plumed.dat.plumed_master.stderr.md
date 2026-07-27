**Project ID:** [plumID:21.034]({{ '/' | absolute_url }}eggs/21/034/)  
Stderr for source:  RiD/plumed.dat   
Download: [zipped raw stdout](plumed.dat.plumed_master.stdout.txt.zip) - [zipped raw stderr](plumed.dat.plumed_master.stderr.txt.zip) 
{% raw %}
<pre style="overflow:scroll;">
#! Only the first 1000 rows of the error file are shown below
#! To inspect the full error file, please download the zipped raw stderr file above
terminate called after throwing an instance of 'PLMD::Plumed::Exception'
what():
Action "DEEPFE" is not known.
[runnervmvrwv9:09504] *** Process received signal ***
[runnervmvrwv9:09504] Signal: Aborted (6)
[runnervmvrwv9:09504] Signal code:  (-6)
[runnervmvrwv9:09504] [ 0] /lib/x86_64-linux-gnu/libc.so.6(+0x45330)[0x7f2754e45330]
[runnervmvrwv9:09504] [ 1] /lib/x86_64-linux-gnu/libc.so.6(pthread_kill+0x11c)[0x7f2754e9eb2c]
[runnervmvrwv9:09504] [ 2] /lib/x86_64-linux-gnu/libc.so.6(gsignal+0x1e)[0x7f2754e4527e]
[runnervmvrwv9:09504] [ 3] /lib/x86_64-linux-gnu/libc.so.6(abort+0xdf)[0x7f2754e288ff]
[runnervmvrwv9:09504] [ 4] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5ff5)[0x7f27552a5ff5]
[runnervmvrwv9:09504] [ 5] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xbb0da)[0x7f27552bb0da]
[runnervmvrwv9:09504] [ 6] /lib/x86_64-linux-gnu/libstdc++.so.6(_ZSt10unexpectedv+0x0)[0x7f27552a5a55]
[runnervmvrwv9:09504] [ 7] /lib/x86_64-linux-gnu/libstdc++.so.6(+0xa5a6f)[0x7f27552a5a6f]
[runnervmvrwv9:09504] [ 8] plumed_master(+0x146dd)[0x564bcfdb06dd]
[runnervmvrwv9:09504] [ 9] /lib/x86_64-linux-gnu/libc.so.6(+0x2a1ca)[0x7f2754e2a1ca]
[runnervmvrwv9:09504] [10] /lib/x86_64-linux-gnu/libc.so.6(__libc_start_main+0x8b)[0x7f2754e2a28b]
[runnervmvrwv9:09504] [11] plumed_master(+0x15365)[0x564bcfdb1365]
[runnervmvrwv9:09504] *** End of error message ***
</pre>
{% endraw %}
